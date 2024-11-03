# Description
It is used for an interactive action: button, textbox, or etc.

# Attributes
## About displaying data
- size  
- dirname

## About data
- accept
    - only be used with input type="file"  
    - (ex)  
    `<input type="file" accept="image/jpeg" multiple required />`
- name
- placeholder
- value

## About a form
- form: set the formId  
- formaction="URL"  
- formenctype="an encoding type"  
- formmethod="GET" or formmethod="POST"  
- formnovalidate(boolean attribute): It ignores the validation of a form.    
- formtarget(_self, _blank, _parent, _top,...)


## About a validation/length
- pattern="a JS regex"
- max, min  
- maxlength, minlength  
- required

# Input Types=""
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
    - alt: an alternative if the browser can't show the image.  
    - src  
    - width, height

### ETC 
- file   
    - accept="MIME type"  
    - multiple(boolean attribute): It allows users to select multifle files.  
    - required  
    - name=""  
- hidden