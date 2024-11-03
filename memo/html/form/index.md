# Description
It is used for an interactive action for submitting information.

## attributes in a `<form>` element
- action
    - Normally, it is used as a URL.  
- autocomplete  
    - on/off  
- method  
    - It defines a HTTP method on the form.  
    - get/post  
- name  
- novalidate  
- target

## Input type  
### Text
- text(default)  
- search
- number

### Data type
- tel  
- url  
- email  
- password  

### Date/Time  
There is no 'year' type.  
- date  
- datetime(UTC)  
- datetime-local  
- time  
- month  
- week  

### Design
- color  

### Interactive  
- checkbox  
- radio  
- button  

### Related to a method
- submit  
- reset    
- image

### ETC 
- file   
- hidden

## Validation  
- Use a regex on an attribute 'pattern'.  
`<input type="text" pattern="\d{2,4}-\d{2,4}-\d{3,4}" maxlength=13">`  

## Input types(HTML -> HTML5)
### HTML
- text, button, image, password    
- checkbox, radio  
- file  
- hidden  
- submit, reset  

### HTML -> HTML5
- search, tel, url, email, number  
- date, datetime, datetime-local, time, month, week  
- color, range  

## Another form elements
### fieldset
- fieldset
    - form: When you assign it as the value of a form's id, the fieldset will be associated with that form.  
    - disabled(boolean attribute)  
    - name
- legend
    - the title of a fieldset

### Label
- How to use?
    - Include the `<input>` element.  
    `<label><input type="checkbox" name="foo_term" />I agree to the Mock term.</label>`  
    - Or, set the value of the 'for' attribute same with the 'id' attribute of input.  
    `<input type="checkbox" name="foo_term" id="foo_term" /><label for="foo_term">I agree to the Mock term.</label>`

### Selectbar
- datalist + option  
    - Datalist suggests some values written on `<option>` elements.
    - It can be used on some input types => text, color, range, time.  
    - The id value of datalist should be same with input's list.  
    - (ex)  
    ```  
    <label for="blood">Choose your blood type:</label>  
    <input list="blood-type" name="blood" id="blood" />   
    <datalist id="blood-type">  
        <option value="A"></option>  
        <option value="B"></option>  
        <option value="O"></option>  
        <option value="AB"></option>  
    </datalist>  
    ```
    - Each option should have its value.
- select + option  
    - A dropdown input.
    - multiple: It allows several options of the select. Cmd or Shift + click.
    - form
    - name
    - required
    - autocomplete
    - autofocus
    - `<option value="test2" selected>`: It makes the default value of the select input.
    - `<option value="test3" disabbled>`: It makes the option disable.
- optgroup
    - It makes a group of options.
- select vs datalist
    - Datalist is for a suggest of the input.
    - Select is for choosing a value of input.