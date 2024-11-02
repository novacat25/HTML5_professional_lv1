# Description
It is used for an interactive action: button, textbox, or etc.

# Attributes
## type
text, button, color, etc  

## About a form
- form: set the formId  
- formaction="URL"  
- formenctype="an encoding type"  
- formmethod="GET" or formmethod="POST"  
- formnovalidate  
- formtarget(_self, _blank, _parent, _top,...)

## About an image
- alt: an alternative 
- src  
- width, height

## About a validation/length
- pattern="a JS regex"
- max, min  
- maxlength, minlength  
- required

## About an option
- disabled  
- readonly  
- checked
    - used on a radio or a checkbox  
- list  

## About displaying data
- size  
- dirname

## About data
- accept
    - only be used with input type="file"  
- name
- placeholder
- value

## Fieldset
- `<label>` element makes the title of a fieldset.
- form: It can connect form id with this attribute.  
- disabled(boolean attribute)