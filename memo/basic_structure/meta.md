# Description
The role of `<meta>` tag

## Elements
- name: declare metadata  
- http-equiv: defines a pragma directive.  
- content: declare the value for the http-equiv or name attribute.    
ex) `<meta name="description" content="This page is for OOO.">`  
- charset  
    - In HTML5, UTF-8 is the only valid encoding.  
    - `<meta charset="UTF-8">`
  
## Pragma directives
- When `http-equiv` attribute is specified on a meta element.  
- Enumerated attribute(requires some types of a value)  

| State                  | Keyword              | Notes         |
| ---------------------- | -------------------- | ------------- |
| Content Langauge       | content-language     | Non-conforming|
| Encoding delcaration   | content-type         |               |
| Default style          | default-style        |               |
| Refresh                | refresh              |               |
| Cookie setter          | set-cookie           | Non-conforming|
  
## Exmamples
`<meta http-equiv="Cache-Control" content="no-cache">`  
This doesn't allow caches.  
  
`<meta http-equiv="refresh" content="20; URL=new.html">`  
It redirects to new.html after 20 seconds.