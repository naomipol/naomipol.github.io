## Classes

<dl>
<dt><a href="#Message">Message</a></dt>
<dd></dd>
<dt><a href="#Form">Form</a></dt>
<dd></dd>
<dt><a href="#Proc">Proc</a></dt>
<dd></dd>
<dt><a href="#ProcError">ProcError</a></dt>
<dd></dd>
</dl>

## Functions

<dl>
<dt><a href="#priorityReady">priorityReady(localJson)</a></dt>
<dd><p>Called when GWT has loaded and API can be used.</p>
</dd>
<dt><a href="#login">login(configuration, successCallback, errorCallback)</a></dt>
<dd><p>Initalization</p>
</dd>
<dt><a href="#formStart">formStart(form, onShowMessgeFunc, onUpdateFieldsFunc, dname, successCallback, errorCallback, autoRetrieveFirstRows)</a></dt>
<dd><p>Start a form.
Should be called once for each form.</p>
</dd>
<dt><a href="#procStart">procStart(name, type, progressCallback, dname, successCallback, errorCallback)</a></dt>
<dd><p>Start a procedure/report.</p>
</dd>
</dl>

## Typedefs

<dl>
<dt><a href="#LoginSuccessCallback">LoginSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#LoginErrorCallback">LoginErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#FormStartSuccessCallback">FormStartSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#FormStartErrorCallback">FormStartErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#SetActiveRowSuccessCallback">SetActiveRowSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#SetActiveRowErrorCallback">SetActiveRowErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#ChooseSuccessCallback">ChooseSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#ChooseErrorCallback">ChooseErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#SearchActionSuccessCallback">SearchActionSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#SearchActionErrorCallback">SearchActionErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#FieldUpdateSuccessCallback">FieldUpdateSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#FieldUpdateErrorCallback">FieldUpdateErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#SaveRowSuccessCallback">SaveRowSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#SaveRowErrorCallback">SaveRowErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#StartSubFormSuccessCallback">StartSubFormSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#StartSubFormErrorCallback">StartSubFormErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#GetRowsSuccessCallback">GetRowsSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#GetRowsErrorCallback">GetRowsErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#NewRowSuccessCallback">NewRowSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#NewRowErrorCallback">NewRowErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#EndCurrentFormSuccessCallback">EndCurrentFormSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#EndCurrentFormErrorCallback">EndCurrentFormErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#UndoSuccessCallback">UndoSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#UndoErrorCallback">UndoErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#DelRowSuccessCallback">DelRowSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#DelRowErrorCallback">DelRowErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#ClearRowsSuccessCallback">ClearRowsSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#ClearRowsErrorCallback">ClearRowsErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#SetSearchFilterSuccessCallback">SetSearchFilterSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#SetSearchFilterErrorCallback">SetSearchFilterErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#SetSimpleSearchFilterSuccessCallback">SetSimpleSearchFilterSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#SetSimpleSearchFilterErrorCallback">SetSimpleSearchFilterErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#ClearSearchFilterSuccessCallback">ClearSearchFilterSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#ClearSearchFilterErrorCallback">ClearSearchFilterErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#ActivateStartSuccessCallback">ActivateStartSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#ActivateStartErrorCallback">ActivateStartErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#ActivateEndSuccessCallback">ActivateEndSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#ActivateEndErrorCallback">ActivateEndErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#UploadFileSuccessCallback">UploadFileSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#UploadFileErrorCallback">UploadFileErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#GetFileUrlSuccessCallback">GetFileUrlSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#GetFileUrlErrorCallback">GetFileUrlErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#addTextSuccessCallback">addTextSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#addTextErrorCallback">addTextErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#isAliveSuccessCallback">isAliveSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#isAliveErrorCallback">isAliveErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#ProcSuccessCallback">ProcSuccessCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#ProcProgressCallback">ProcProgressCallback</a> : <code>function</code></dt>
<dd><p>This callback is used to update progress bar (called only when the procedure starts a program that reports progress).
Note that if the procedure activates a process that doesn&#39;t report progress, or delays for other reason (for example:
long running query), this callback WOULD NOT be called.
So, it is recommended to use some action indicator always! Change it to a percentage indicator when this
callback is called.</p>
</dd>
<dt><a href="#ProcErrorCallback">ProcErrorCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#ProcOpenChooseCallback">ProcOpenChooseCallback</a> : <code>function</code></dt>
<dd></dd>
<dt><a href="#ProcSearchActionCallback">ProcSearchActionCallback</a> : <code>function</code></dt>
<dd></dd>
</dl>

<a name="Message"></a>

## Message
**Kind**: global class  

* [Message](#Message)
    * [.message](#Message+message) : <code>string</code>
    * [.messagetype](#Message+messagetype) : <code>string</code>

<a name="Message+message"></a>

### message.message : <code>string</code>
Message text

**Kind**: instance property of <code>[Message](#Message)</code>  
<a name="Message+messagetype"></a>

### message.messagetype : <code>string</code>
Message type

**Kind**: instance property of <code>[Message](#Message)</code>  
<a name="Form"></a>

## Form
**Kind**: global class  

* [Form](#Form)
    * _instance_
        * [.setActiveRow(row, onSuccess, onError)](#Form+setActiveRow)
        * [.choose(fieldName, fieldVale, onSuccess, onError)](#Form+choose)
        * [.searchAction(action, searchText, onSuccess, onError)](#Form+searchAction)
        * [.fieldUpdate(fieldName, fieldValue, onSuccess, onError)](#Form+fieldUpdate)
        * [.warningConfirm(okCancel)](#Form+warningConfirm)
        * [.saveRow(backToParentForm, onSuccess, onError)](#Form+saveRow)
        * [.startSubForm(formName, onShowMessgeFunc, onUpdateFieldsFunc, onSuccess, onError)](#Form+startSubForm)
        * [.getRows(fromRow, onSuccess, onError)](#Form+getRows)
        * [.newRow(onSuccess, onError)](#Form+newRow)
        * [.endCurrentForm(onSuccess, onError)](#Form+endCurrentForm)
        * [.undo(onSuccess, onError)](#Form+undo)
        * [.delRow(onSuccess, onError)](#Form+delRow)
        * [.clearRows(onSuccess, onError)](#Form+clearRows)
        * [.setSearchFilter(filter, onSuccess, onError)](#Form+setSearchFilter)
        * [.setSimpleSearchFilter(filter, onSuccess, onError)](#Form+setSimpleSearchFilter)
        * [.clearSearchFilter(onSuccess, onError)](#Form+clearSearchFilter)
        * [.activateEnd(onSuccess, onError)](#Form+activateEnd)
        * [.uploadFile(fieldName, fieldValue, file, onSuccess, onError)](#Form+uploadFile)
        * [.cancelFileUpload()](#Form+cancelFileUpload)
        * [.getFileUrl(filename, onSuccess, onError)](#Form+getFileUrl)
        * [.saveText(text, addFlag, signatureFlag, secondaryLanguageFlag, onSuccess, onError)](#Form+saveText)
        * [.isAlive(onSuccess, onError)](#Form+isAlive)
    * _static_
        * [.activateStart(ename, type, progressCallback, successCallback, errorCallback)](#Form.activateStart)

<a name="Form+setActiveRow"></a>

### form.setActiveRow(row, onSuccess, onError)
Goto row.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| row | <code>number</code> | Row number. |
| onSuccess | <code>[SetActiveRowSuccessCallback](#SetActiveRowSuccessCallback)</code> | called on success. |
| onError | <code>[SetActiveRowErrorCallback](#SetActiveRowErrorCallback)</code> | called on error. |

<a name="Form+choose"></a>

### form.choose(fieldName, fieldVale, onSuccess, onError)
Open choose/search in specified field.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| fieldName | <code>string</code> | Name of field (for example CUSTNAME). |
| fieldVale | <code>string</code> | Current value in field. |
| onSuccess | <code>[ChooseSuccessCallback](#ChooseSuccessCallback)</code> | called on success. |
| onError | <code>[ChooseErrorCallback](#ChooseErrorCallback)</code> | called on error. |

<a name="Form+searchAction"></a>

### form.searchAction(action, searchText, onSuccess, onError)
Perform an action in search dialog.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| action | <code>number</code> | One of: Next(1),Prev(2),TypeChange(3),TextChange(4),StartChange(5),IgnoreCaseChanged(6) |
| searchText | <code>string</code> | the text to search for. |
| onSuccess | <code>[SearchActionSuccessCallback](#SearchActionSuccessCallback)</code> | called on success. |
| onError | <code>[SearchActionErrorCallback](#SearchActionErrorCallback)</code> | called on error. |

<a name="Form+fieldUpdate"></a>

### form.fieldUpdate(fieldName, fieldValue, onSuccess, onError)
Update value in field.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| fieldName | <code>string</code> | Name of field. |
| fieldValue | <code>string</code> | Current value in field. |
| onSuccess | <code>[FieldUpdateSuccessCallback](#FieldUpdateSuccessCallback)</code> | called on success. |
| onError | <code>[FieldUpdateErrorCallback](#FieldUpdateErrorCallback)</code> | called on error. |

<a name="Form+warningConfirm"></a>

### form.warningConfirm(okCancel)
Confirm a warning message.After returning from the server this function calls 'onSuccess' / 'onError' function of the last API call.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| okCancel | <code>boolean</code> | 1: ok, 0: cancel |

<a name="Form+saveRow"></a>

### form.saveRow(backToParentForm, onSuccess, onError)
Save changes in current active row.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| backToParentForm | <code>number</code> | 0: stay in current row after save, 1: For Sub-Form only. go back to parent form and set active row to parent row. |
| onSuccess | <code>[SaveRowSuccessCallback](#SaveRowSuccessCallback)</code> | called on success. |
| onError | <code>[SaveRowErrorCallback](#SaveRowErrorCallback)</code> | called on error. |

<a name="Form+startSubForm"></a>

### form.startSubForm(formName, onShowMessgeFunc, onUpdateFieldsFunc, onSuccess, onError)
Starts a Sub-Form and sets the position of the active row to the first row of the Sub-Form.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| formName | <code>string</code> | for example: ORDERITEMS. |
| onShowMessgeFunc | <code>object</code> | callback function for handling error and warning messages (If null the main form callback is called). |
| onUpdateFieldsFunc | <code>object</code> | callback function for handling field updates (If null the main form callback is called). |
| onSuccess | <code>[StartSubFormSuccessCallback](#StartSubFormSuccessCallback)</code> | called on success. |
| onError | <code>[StartSubFormErrorCallback](#StartSubFormErrorCallback)</code> | called on error. |

<a name="Form+getRows"></a>

### form.getRows(fromRow, onSuccess, onError)
Returns rows data of current form.Note: GetRows without a filter returns rows that have already been retrieved. It doesn't retrieve new rows.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| fromRow | <code>number</code> | The position of the first row to be retrieved. |
| onSuccess | <code>[GetRowsSuccessCallback](#GetRowsSuccessCallback)</code> | called on success. |
| onError | <code>[GetRowsErrorCallback](#GetRowsErrorCallback)</code> | called on error. |

<a name="Form+newRow"></a>

### form.newRow(onSuccess, onError)
Opens a new row in the current form. Set the position of the active row to this row.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| onSuccess | <code>[NewRowSuccessCallback](#NewRowSuccessCallback)</code> | called on success. |
| onError | <code>[NewRowErrorCallback](#NewRowErrorCallback)</code> | called on error. |

<a name="Form+endCurrentForm"></a>

### form.endCurrentForm(onSuccess, onError)
Exits the current form. On a Sub-Form sets the active row to the parent row.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| onSuccess | <code>[EndCurrentFormSuccessCallback](#EndCurrentFormSuccessCallback)</code> | called on success. |
| onError | <code>[EndCurrentFormErrorCallback](#EndCurrentFormErrorCallback)</code> | called on error. |

<a name="Form+undo"></a>

### form.undo(onSuccess, onError)
Undo unsaved changes in current row.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| onSuccess | <code>[UndoSuccessCallback](#UndoSuccessCallback)</code> | called on success. |
| onError | <code>[UndoErrorCallback](#UndoErrorCallback)</code> | called on error. |

<a name="Form+delRow"></a>

### form.delRow(onSuccess, onError)
Deletes current row.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| onSuccess | <code>[DelRowSuccessCallback](#DelRowSuccessCallback)</code> | called on success. |
| onError | <code>[DelRowErrorCallback](#DelRowErrorCallback)</code> | called on error. |

<a name="Form+clearRows"></a>

### form.clearRows(onSuccess, onError)
Clear all rows in a top level form. Doesn't delete rows!

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| onSuccess | <code>[ClearRowsSuccessCallback](#ClearRowsSuccessCallback)</code> | called on success. |
| onError | <code>[ClearRowsErrorCallback](#ClearRowsErrorCallback)</code> | called on error. |

<a name="Form+setSearchFilter"></a>

### form.setSearchFilter(filter, onSuccess, onError)
Sets a search filter in top level form.Following calls to GetRows() function will use this filter until cleared or replaced by another filter.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| filter | <code>Object</code> | the filter is an Object of the form: <pre> { 	or: (number),  ignorecase: (number), 	QueryValues: 	[{ 		field: (string), 		fromval: (string), 		toval:	(string), 		op:	(string), 		sort: (number), 		isdesc: (number), 	}, 	{ 		... 	}] } 	 or: 0: and, 1: or (operator to be used between ALL conditions). ignorecase: 0: case sensitive, 1: case insensitive. field: field name (for example: CUSTNAME) fromval: value toval: to value - if tovalue is not empty then condition is always: field >= fromval AND field <= toval, 					 if tovalue is empty, then condition is: field op fromval. op: one of "=", "<", "<=", ">", ">=", "<>" sort: 0: no sort, other value: position of field in ORDER BY. isdesc: 0: ASC, 1: DESC   Note: Filter MUST include all fields. Note: every field can appear only once in the filter. Note: The search is from the beginning of form field values.  		 values such as "*100", the "*" in the beginning will be ignored.   </pre> |
| onSuccess | <code>[SetSearchFilterSuccessCallback](#SetSearchFilterSuccessCallback)</code> | called on success. |
| onError | <code>[SetSearchFilterErrorCallback](#SetSearchFilterErrorCallback)</code> | called on error. |

<a name="Form+setSimpleSearchFilter"></a>

### form.setSimpleSearchFilter(filter, onSuccess, onError)
Sets a simple search filter in top level form.Following calls to GetRows() function will use this filter until cleared or replaced by another filter.Note: The search is from the beginning of form field values. 		 values such as "*100", the "*" in the beginning will be ignored.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| filter | <code>string</code> | string to be searched for in the fields marked as search fields. |
| onSuccess | <code>[SetSimpleSearchFilterSuccessCallback](#SetSimpleSearchFilterSuccessCallback)</code> | called on success. |
| onError | <code>[SetSimpleSearchFilterErrorCallback](#SetSimpleSearchFilterErrorCallback)</code> | called on error. |

<a name="Form+clearSearchFilter"></a>

### form.clearSearchFilter(onSuccess, onError)
Clears search filter for the top level form.Following calls to GetRows() will not use a filter.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| onSuccess | <code>[ClearSearchFilterSuccessCallback](#ClearSearchFilterSuccessCallback)</code> | called on success. |
| onError | <code>[ClearSearchFilterErrorCallback](#ClearSearchFilterErrorCallback)</code> | called on error. |

<a name="Form+activateEnd"></a>

### form.activateEnd(onSuccess, onError)
Should be called after a direct activation (which runs in foreground) ends,In order to refresh form data.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| onSuccess | <code>[ActivateEndSuccessCallback](#ActivateEndSuccessCallback)</code> | called on success. |
| onError | <code>[ActivateEndErrorCallback](#ActivateEndErrorCallback)</code> | called on error. |

<a name="Form+uploadFile"></a>

### form.uploadFile(fieldName, fieldValue, file, onSuccess, onError)
Upload a file in an attachment field to server.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| fieldName | <code>string</code> | name of attachment field. |
| fieldValue | <code>string</code> | current value in attachment field. |
| file | <code>Object</code> | A File Object (This object can be obtained from a <input type="text"> HTML tag in the page). |
| onSuccess | <code>[UploadFileSuccessCallback](#UploadFileSuccessCallback)</code> | called on success and progress. |
| onError | <code>[UploadFileErrorCallback](#UploadFileErrorCallback)</code> | called on error. |

<a name="Form+cancelFileUpload"></a>

### form.cancelFileUpload()
Cancels current file uploading.After canceling te {UploadFileSuccessCallback}onSuccess callback is called from the 'UploadFile' request.The values of {ResultObj} result are :  progress = -1 , isLast=1, file="".

**Kind**: instance method of <code>[Form](#Form)</code>  
<a name="Form+getFileUrl"></a>

### form.getFileUrl(filename, onSuccess, onError)
Translate attachment path to URL.For example: ../../system/mail/201611/enxjf/1.pdf ==> https://servername/primail/201611/enxjf/1.pdf

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| filename | <code>string</code> | the Attachment path. |
| onSuccess | <code>[GetFileUrlSuccessCallback](#GetFileUrlSuccessCallback)</code> | called on success. |
| onError | <code>[GetFileUrlErrorCallback](#GetFileUrlErrorCallback)</code> | called on error. |

<a name="Form+saveText"></a>

### form.saveText(text, addFlag, signatureFlag, secondaryLanguageFlag, onSuccess, onError)
add text to text form.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| text | <code>string</code> | the new text to add (may be plain text or html). |
| addFlag | <code>boolean</code> | add new text to existing text (1), or add new text and delete existing text (0). |
| signatureFlag | <code>boolean</code> | Automatically add user signature (1). Don't add signature (0). |
| secondaryLanguageFlag | <code>boolean</code> | Signature in primary system language (0), or secondary system language (1). |
| onSuccess | <code>[addTextSuccessCallback](#addTextSuccessCallback)</code> | called on success. |
| onError | <code>[addTextErrorCallback](#addTextErrorCallback)</code> | called on error. |

<a name="Form+isAlive"></a>

### form.isAlive(onSuccess, onError)
Check if form is alive.

**Kind**: instance method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| onSuccess | <code>[isAliveSuccessCallback](#isAliveSuccessCallback)</code> | called on success. |
| onError | <code>[isAliveErrorCallback](#isAliveErrorCallback)</code> | called on error. |

<a name="Form.activateStart"></a>

### Form.activateStart(ename, type, progressCallback, successCallback, errorCallback)
Start a Direct activation.

**Kind**: static method of <code>[Form](#Form)</code>  

| Param | Type | Description |
| --- | --- | --- |
| ename | <code>string</code> | Name of procedure/report. |
| type | <code>string</code> | Type ("R" for report, "P" for procedure) |
| progressCallback | <code>[ProcProgressCallback](#ProcProgressCallback)</code> | notify progress. |
| successCallback | <code>[ProcSuccessCallback](#ProcSuccessCallback)</code> | called on success. |
| errorCallback | <code>[ProcErrorCallback](#ProcErrorCallback)</code> | called on error. |

<a name="Proc"></a>

## Proc
**Kind**: global class  

* [Proc](#Proc)
    * [.message(ok, successCallback, errorCallback)](#Proc+message)
    * [.reportOptions(ok, selectedFormat, successCallback, errorCallback)](#Proc+reportOptions)
    * [.reportOptions(ok, selectedFormat, pdf, successCallback, errorCallback)](#Proc+reportOptions)
    * [.inputFields(ok, data, successCallback, errorCallback)](#Proc+inputFields)
    * [.inputOptions(ok, selection, successCallback, errorCallback)](#Proc+inputOptions)
    * [.inputHelp(ok, successCallback, errorCallback)](#Proc+inputHelp)
    * [.continueProc(successCallback, errorCallback)](#Proc+continueProc)
    * [.cancel(successCallback, errorCallback)](#Proc+cancel)
    * [.choose(fieldId, value, data, successCallback, errorCallback)](#Proc+choose)
    * [.searchAction(fieldId, value, action, data, successCallback, errorCallback)](#Proc+searchAction)

<a name="Proc+message"></a>

### proc.message(ok, successCallback, errorCallback)
Call after a message is approved or canceled.

**Kind**: instance method of <code>[Proc](#Proc)</code>  

| Param | Type | Description |
| --- | --- | --- |
| ok | <code>number</code> | 1: OK, 0: Cancel (If only one button can send either). |
| successCallback | <code>[ProcSuccessCallback](#ProcSuccessCallback)</code> | called on success. |
| errorCallback | <code>[ProcErrorCallback](#ProcErrorCallback)</code> | called on error. |

<a name="Proc+reportOptions"></a>

### proc.reportOptions(ok, selectedFormat, successCallback, errorCallback)
Call after reportOptions step

**Kind**: instance method of <code>[Proc](#Proc)</code>  

| Param | Type | Description |
| --- | --- | --- |
| ok | <code>number</code> | 1: OK, 0: Cancel. |
| selectedFormat | <code>number</code> | selected format. |
| successCallback | <code>[ProcSuccessCallback](#ProcSuccessCallback)</code> | called on success. |
| errorCallback | <code>[ProcErrorCallback](#ProcErrorCallback)</code> | called on error. |

<a name="Proc+reportOptions"></a>

### proc.reportOptions(ok, selectedFormat, pdf, successCallback, errorCallback)
Call after documentOptions step

**Kind**: instance method of <code>[Proc](#Proc)</code>  

| Param | Type | Description |
| --- | --- | --- |
| ok | <code>number</code> | 1: OK, 0: Cancel. |
| selectedFormat | <code>number</code> | selected format. |
| pdf | <code>number</code> | 1: PDF, 2: HTML. |
| successCallback | <code>[ProcSuccessCallback](#ProcSuccessCallback)</code> | called on success. |
| errorCallback | <code>[ProcErrorCallback](#ProcErrorCallback)</code> | called on error. |

<a name="Proc+inputFields"></a>

### proc.inputFields(ok, data, successCallback, errorCallback)
Call after inputFields step

**Kind**: instance method of <code>[Proc](#Proc)</code>  

| Param | Type | Description |
| --- | --- | --- |
| ok | <code>number</code> | 1: OK, 0: Cancel. |
| data | <code>Object</code> | Input fields data (JSON): <pre> { 		EditFields: [ 		{ 			field: (number) - field ID 			value: (string) - field value 			op:	(number) - operator ID 			value2: (string) - value2 			op2: (number) - operator2 ID 		} 		... 		] } </pre> |
| successCallback | <code>[ProcSuccessCallback](#ProcSuccessCallback)</code> | called on success. |
| errorCallback | <code>[ProcErrorCallback](#ProcErrorCallback)</code> | called on error. |

<a name="Proc+inputOptions"></a>

### proc.inputOptions(ok, selection, successCallback, errorCallback)
Call after inputOptions step

**Kind**: instance method of <code>[Proc](#Proc)</code>  

| Param | Type | Description |
| --- | --- | --- |
| ok | <code>number</code> | 1: OK, 0: Cancel. |
| selection | <code>number</code> | selected option ID. |
| successCallback | <code>[ProcSuccessCallback](#ProcSuccessCallback)</code> | called on success. |
| errorCallback | <code>[ProcErrorCallback](#ProcErrorCallback)</code> | called on error. |

<a name="Proc+inputHelp"></a>

### proc.inputHelp(ok, successCallback, errorCallback)
Call after inputHelp step

**Kind**: instance method of <code>[Proc](#Proc)</code>  

| Param | Type | Description |
| --- | --- | --- |
| ok | <code>number</code> | 1: OK, 0: Cancel. |
| successCallback | <code>[ProcSuccessCallback](#ProcSuccessCallback)</code> | called on success. |
| errorCallback | <code>[ProcErrorCallback](#ProcErrorCallback)</code> | called on error. |

<a name="Proc+continueProc"></a>

### proc.continueProc(successCallback, errorCallback)
Call after every other step

**Kind**: instance method of <code>[Proc](#Proc)</code>  

| Param | Type | Description |
| --- | --- | --- |
| successCallback | <code>[ProcSuccessCallback](#ProcSuccessCallback)</code> | called on success. |
| errorCallback | <code>[ProcErrorCallback](#ProcErrorCallback)</code> | called on error. |

<a name="Proc+cancel"></a>

### proc.cancel(successCallback, errorCallback)
Cancel procedure.

**Kind**: instance method of <code>[Proc](#Proc)</code>  

| Param | Type | Description |
| --- | --- | --- |
| successCallback | <code>[ProcSuccessCallback](#ProcSuccessCallback)</code> | called on success. |
| errorCallback | <code>[ProcErrorCallback](#ProcErrorCallback)</code> | called on error. |

<a name="Proc+choose"></a>

### proc.choose(fieldId, value, data, successCallback, errorCallback)
Open Choose or Search.

**Kind**: instance method of <code>[Proc](#Proc)</code>  

| Param | Type | Description |
| --- | --- | --- |
| fieldId | <code>number</code> | ID of field. |
| value | <code>string</code> | current value in field. |
| data | <code>Object</code> | Data in all fields (Choose/Search may be dependent on other fields values). <pre> { 		ChooseFields: [ 		{ 			field: (number) - field ID 			value: (string) - field value 		} 		... 		] } </pre> |
| successCallback | <code>[ProcOpenChooseCallback](#ProcOpenChooseCallback)</code> | called on success. |
| errorCallback | <code>[ProcErrorCallback](#ProcErrorCallback)</code> | called on error. |

<a name="Proc+searchAction"></a>

### proc.searchAction(fieldId, value, action, data, successCallback, errorCallback)
Perform action in search dialog.

**Kind**: instance method of <code>[Proc](#Proc)</code>  

| Param | Type | Description |
| --- | --- | --- |
| fieldId | <code>number</code> | ID of field. |
| value | <code>string</code> | current value in field. |
| action | <code>number</code> | One of: Next(1),Prev(2),TypeChange(3),TextChange(4),StartChange(5),IgnoreCaseChanged(6) |
| data | <code>Object</code> | Data in all fields (Search may be dependent on other fields values). <pre> { 		ChooseFields: [ 		{ 			field: (number) - field ID 			value: (string) - field value 		} 		... 		] } </pre> |
| successCallback | <code>[ProcSearchActionCallback](#ProcSearchActionCallback)</code> | called on success. |
| errorCallback | <code>[ProcErrorCallback](#ProcErrorCallback)</code> | called on error. |

<a name="ProcError"></a>

## ProcError
**Kind**: global class  

* [ProcError](#ProcError)
    * [.type](#ProcError+type) : <code>string</code>
    * [.text](#ProcError+text) : <code>string</code>

<a name="ProcError+type"></a>

### procError.type : <code>string</code>
type of error ("NotSupported" / "ServerBusy" / "Error")

**Kind**: instance property of <code>[ProcError](#ProcError)</code>  
<a name="ProcError+text"></a>

### procError.text : <code>string</code>
Error text

**Kind**: instance property of <code>[ProcError](#ProcError)</code>  
<a name="priorityReady"></a>

## priorityReady(localJson)
Called when GWT has loaded and API can be used.

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| localJson | <code>json</code> | Local Json configuration file.When calling PriInit another file can be loded from a different place. |

<a name="login"></a>

## login(configuration, successCallback, errorCallback)
Initalization

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| configuration | <code>Object</code> | Configuration Object of the form: <pre> { 	url: (string),  tabulaini: (string), 	language: (number),  company: (string),  appname: (string),  username: (string),  password: (string),  devicename: (string) } 	 url: URL to Priority WCF service without the "wcf/wcf/service.svc" part. tabulaini: tabula.ini file name. language: language number. company: The name of the company in Priority. appname: Application Name - (Can be accessed in form triggers using form variable :FORM_APP_NAME) username: Username. password: Password. devicename: Name of device (additional information that is logged in the connection log). </pre> |
| successCallback | <code>[LoginSuccessCallback](#LoginSuccessCallback)</code> | called on success. |
| errorCallback | <code>[LoginErrorCallback](#LoginErrorCallback)</code> | called on error. |

<a name="formStart"></a>

## formStart(form, onShowMessgeFunc, onUpdateFieldsFunc, dname, successCallback, errorCallback, autoRetrieveFirstRows)
Start a form.Should be called once for each form.

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| form | <code>string</code> | Name of form. |
| onShowMessgeFunc | <code>object</code> | callback function for handling error and warning messages. |
| onUpdateFieldsFunc | <code>object</code> | callback function for handling field updates. |
| dname | <code>string</code> | name of company in which form is started. |
| successCallback | <code>[FormStartSuccessCallback](#FormStartSuccessCallback)</code> | called on success. |
| errorCallback | <code>[FormStartErrorCallback](#FormStartErrorCallback)</code> | called on error. |
| autoRetrieveFirstRows | <code>number</code> | 1: after starting the form, first rows are retrieved.                                         else: this function only starts the form. |

<a name="procStart"></a>

## procStart(name, type, progressCallback, dname, successCallback, errorCallback)
Start a procedure/report.

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| name | <code>string</code> | Name of procedure/report. |
| type | <code>string</code> | Type ("R" for report, "P" for procedure) |
| progressCallback | <code>[ProcProgressCallback](#ProcProgressCallback)</code> | notify progress. |
| dname | <code>string</code> | company name in which the procedure should run. |
| successCallback | <code>[ProcSuccessCallback](#ProcSuccessCallback)</code> | called on success. |
| errorCallback | <code>[ProcErrorCallback](#ProcErrorCallback)</code> | called on error. |

<a name="LoginSuccessCallback"></a>

## LoginSuccessCallback : <code>function</code>
**Kind**: global typedef  
<a name="LoginErrorCallback"></a>

## LoginErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |

<a name="FormStartSuccessCallback"></a>

## FormStartSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| form | <code>[Form](#Form)</code> | Form Object. |
| formData. | <code>Object</code> |  |

<a name="FormStartErrorCallback"></a>

## FormStartErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="SetActiveRowSuccessCallback"></a>

## SetActiveRowSuccessCallback : <code>function</code>
**Kind**: global typedef  
<a name="SetActiveRowErrorCallback"></a>

## SetActiveRowErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="ChooseSuccessCallback"></a>

## ChooseSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>ResultObj</code> | Choose Object/Search Object/null |
| type | <code>String</code> | "Choose" / "Search" / "None". |

<a name="ChooseErrorCallback"></a>

## ChooseErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="SearchActionSuccessCallback"></a>

## SearchActionSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>ResultObj</code> | Search object. |

<a name="SearchActionErrorCallback"></a>

## SearchActionErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="FieldUpdateSuccessCallback"></a>

## FieldUpdateSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>ResultObj</code> | result object. |

<a name="FieldUpdateErrorCallback"></a>

## FieldUpdateErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="SaveRowSuccessCallback"></a>

## SaveRowSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>ResultObj</code> | result object. |

<a name="SaveRowErrorCallback"></a>

## SaveRowErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="StartSubFormSuccessCallback"></a>

## StartSubFormSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| form | <code>[Form](#Form)</code> | Form Object. |
| result | <code>ResultObj</code> | result object. |

<a name="StartSubFormErrorCallback"></a>

## StartSubFormErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="GetRowsSuccessCallback"></a>

## GetRowsSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>ResultObj</code> | result object. |

<a name="GetRowsErrorCallback"></a>

## GetRowsErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="NewRowSuccessCallback"></a>

## NewRowSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>ResultObj</code> | result object. |

<a name="NewRowErrorCallback"></a>

## NewRowErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="EndCurrentFormSuccessCallback"></a>

## EndCurrentFormSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>ResultObj</code> | result object. |

<a name="EndCurrentFormErrorCallback"></a>

## EndCurrentFormErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="UndoSuccessCallback"></a>

## UndoSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>ResultObj</code> | result object. |

<a name="UndoErrorCallback"></a>

## UndoErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="DelRowSuccessCallback"></a>

## DelRowSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>ResultObj</code> | result object. |

<a name="DelRowErrorCallback"></a>

## DelRowErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="ClearRowsSuccessCallback"></a>

## ClearRowsSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>ResultObj</code> | result object. |

<a name="ClearRowsErrorCallback"></a>

## ClearRowsErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="SetSearchFilterSuccessCallback"></a>

## SetSearchFilterSuccessCallback : <code>function</code>
**Kind**: global typedef  
<a name="SetSearchFilterErrorCallback"></a>

## SetSearchFilterErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="SetSimpleSearchFilterSuccessCallback"></a>

## SetSimpleSearchFilterSuccessCallback : <code>function</code>
**Kind**: global typedef  
<a name="SetSimpleSearchFilterErrorCallback"></a>

## SetSimpleSearchFilterErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="ClearSearchFilterSuccessCallback"></a>

## ClearSearchFilterSuccessCallback : <code>function</code>
**Kind**: global typedef  
<a name="ClearSearchFilterErrorCallback"></a>

## ClearSearchFilterErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="ActivateStartSuccessCallback"></a>

## ActivateStartSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>ResultObj</code> | result object. |

<a name="ActivateStartErrorCallback"></a>

## ActivateStartErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="ActivateEndSuccessCallback"></a>

## ActivateEndSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>ResultObj</code> | result object. |

<a name="ActivateEndErrorCallback"></a>

## ActivateEndErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="UploadFileSuccessCallback"></a>

## UploadFileSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>ResultObj</code> | result object. a JSON object of the form: <pre> { 	 progress: (number), 	 isLast: (number),			 	 file: (string) }   where: progress: a number between 0 and 100 indicating the progress of the upload. isLast: is upload finished. file: if upload finished, the name of the file that must be placed in the attachment field. 		 (Afterwards FormFieldUpdate API function should be called to notify the server on the change) </pre> |

<a name="UploadFileErrorCallback"></a>

## UploadFileErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="GetFileUrlSuccessCallback"></a>

## GetFileUrlSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>ResultObj</code> | result object. |

<a name="GetFileUrlErrorCallback"></a>

## GetFileUrlErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="addTextSuccessCallback"></a>

## addTextSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>ResultObj</code> | result object. |

<a name="addTextErrorCallback"></a>

## addTextErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="isAliveSuccessCallback"></a>

## isAliveSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>number</code> | 1: alive, 0: not alive. |

<a name="isAliveErrorCallback"></a>

## isAliveErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| errorMessage | <code>string</code> | Error message. |
| isFatal | <code>boolean</code> | Is fatal error. |

<a name="ProcSuccessCallback"></a>

## ProcSuccessCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| data | <code>Object</code> | result data. <pre> data may be of the following structures: 1) Input Dialog with input fields: { 		type: "inputFields", 		input: { 			EditFields: [ 			{ 				columntype: (string) - "Str" / "Rstr" / "Bool" / "Real" / "Int" / "Date8" / "Date10" / "Date14" / "Time5" / "Time6" 				field: (number) - field ID 				helpstring: (string) - field help text 				isboolean: (boolean) - is field boolean 				ispassword: (boolean) - is field password 				mandatory: (boolean) - is field mandatory  				operator: (number) - default operator (saved from last run) 				readonly: (boolean) - is field readonly (values come from choose) 				title: (string) - field title 				value: (string) - default value (saved from last run) 				value1: (string) - default value1 (when operator is "between") 				width: (number) - field width 				zoom: (string - "None" / "Attach" / "Search" / "Choose" / "Zoom" / "Date14" /  								"Date8" / "Date10" / "EMail" / "URL" / "HiddenZoom" / "LinkFile" / "QEdit" / "SpecialAttach" 			} 			... 			],  			Operators: [ 			{ 				name: (string) - operator name 				op: (number) - operator ID 				title: (string) - operator title 			} 			... 			], 			text: (string) - help text 			title: (string) - title of dialog 		} 	} 2) Input dialog with choose field (In web interface shows radio buttons, if more then 8 choose options shows listbox): { 		type: "inputOptions", 		input: { 			Options: [ 			{ 				field: (number) - option ID 				help: (string) - help text 				name: (string) - option name 				selected: (boolean) - is option selected (only one is selected) 				title: (string) - option title 			} 			... 			], 			text: (string) - help text, 			title: (string) - title of dialog 		} 	} 	 	3) help dialog (Show help text with OK, Cancel buttons) 	{ 		type: "inputHelp", 		input: { 			text: (string) - help text, 			title: (string) - title of dialog 		} 	} 	 4) Error/Warning message:  {  	type: "message",  	message: (string) - message text,  	messagetype: (string) - "information" / "warning" / "error"  }    5) New Report dialog:    {  	type: "reportOptions",  	formats: [  	{  		format: (number) - format ID  		selected: (boolean) - is selected  		title:	(string) - format title  	}  	...  	]  }    6) New Document dialog:    {  	type: "documentOptions",  	formats: [  	{  		format: (number) - format ID  		selected: (boolean) - is selected  		title:	(string) - format title  	}  	...  	],  	pdf: (boolean) - is PDF Check box checked   }  		  7) Display URL (Show generated report):    {  	type: "displayUrl",  	Urls: [  	{  		action: "display" (Only supported action currently)  		url: (string) - the URL to display  	}  	...  	]  } 	 8) End (The procedure has ended): { 		type: "end" } 	 </pre> |

<a name="ProcProgressCallback"></a>

## ProcProgressCallback : <code>function</code>
This callback is used to update progress bar (called only when the procedure starts a program that reports progress).Note that if the procedure activates a process that doesn't report progress, or delays for other reason (for example:long running query), this callback WOULD NOT be called.So, it is recommended to use some action indicator always! Change it to a percentage indicator when thiscallback is called.

**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| proc | <code>[Proc](#Proc)</code> | Procedure Object. |
| progress | <code>Number</code> | 0-100. |

<a name="ProcErrorCallback"></a>

## ProcErrorCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| proc | <code>[Proc](#Proc)</code> | Procedure Object. |
| error | <code>[ProcError](#ProcError)</code> | Object.   <pre>      { 		type: (string) - type of message: "NotSupported" / "ServerBusy" / "Error" 		text: (string) - text of message } </pre> |

<a name="ProcOpenChooseCallback"></a>

## ProcOpenChooseCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>Object</code> | A choose or search object |

<a name="ProcSearchActionCallback"></a>

## ProcSearchActionCallback : <code>function</code>
**Kind**: global typedef  

| Param | Type | Description |
| --- | --- | --- |
| result | <code>Object</code> | A search object |

