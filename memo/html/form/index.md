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

## input type  
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
