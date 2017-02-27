#startForm
```javascript
startForm(formName, updateFormCallback, messagesCallback, successCallback, rejectCallback);
```
or
```javascript
startForm(formName, updateFormCallback, messagesCallback).then(function(form) {
      //success
    },function() {
      //reject
    });
```

###Prameters:

| Param        | Type           | Descripiton  |
| :------------|:---------------| :----------- |
| formName |`string` | The form name to start. The unique uppercase form name in the Priority system. 
| updafeFormCallback | `function`| A callback function, will be called by the api on any updates recieved for the form. See [updateFormCallback](/#updateFormCallback).
| messagesCallback | `function` | A callback function, will be called by the api on any messages recieved for the form operations. See [messagesCallback](/#messagesCallback).
| successCallback | `function` | A success callback that provides the started [`Form`](#/Form) object.
| rejectCallback | `function` | A reject callback that will be called if the operation was rejected.

###updateFormCallback

A callback function passed to the [`startForm`](/#startForm) function.

This callback is called by the api when there are updates recieved from the server of the form rows and fields. Updates are useally recieved when different actions are performed on the form, such as [`updateField`](/#updateField),
[`saveRow`](/#saveRow), [`undoRow`](/#undoRow), [`deleteRow`](/#deleteRow) and more. The concept of the updates will be explained seperatlly for each action.

This callback should be carefully implemented to cover all the 'update' cases, in order to keep your local data always up to date!

This callback provides a literal object with the updated values as the following:
```javascript
{
    "FORM_NAME" :
    {
        "row_index" :
        {
            "FIELD_NAME" : value,
            "ANOTHER_FIELD_NAME" : value
        }
        "another_row_index" ...
    }
}
```
###messagesCallback

A callback passed to the [`startForm`](/#startForm) function.

This callback is called by the api when there are messages recieved from the server. Messages could be recieved at any time, but are useally recieved when form actions are performed.

This callback provides a [`ServerMessage`](/#servermessage) Object. Mainly an error or warning connected to the last action that was performed.

**Note**: 
 - When there is an error for a single action, The error will be returned by the `messagesCallback` and not in the `rejectCallback` of the action that will be invoked as well.
 
 - When there is a warning for a single action, The warning will be returned by the `messagesCallback` and the action will not be completed until the [`approveWarning`](/#approvewarning) or [`cancelWarning`](/#cancelwarning) is called. When an `approve` or `cancel` is called, the action will return to the `successCallback` or `rejectCallback` respectively.

See [`ServerMessage`](/#servermessage) for a detailed explenation of the different messages types.


###Example
```javascript

var customersForm;

function updateFormCallback(updates) {
  if(updates["CUSTOMERS"] != null) {
    Object.assign(customersForm.rows,updates["CUSTOMERS"]);
  }
}

function messagesCallback(serverMessage) {
  alert(serverMessage.message);
}

startForm("CUSTOMERS", updateFormCallback, messagesCallback).then(function(form) {
      customersForm = form;
    },function() {
      //reject
    });
```

