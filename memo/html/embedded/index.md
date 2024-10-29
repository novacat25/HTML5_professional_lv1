# Description
- About 'Embedded Contents'

## Elements
- `<iframe>`  

### Picture
- `<img>`  
- `<picture>`  
- `<svg>`  

### Audio / Video
- `<source>`  
    - a void element: no content, no closing tag  
- type  
    - `<audio>`  
    - `<video>`  
- Why do we use `<source>`?  
    - `<audio>` or `<video>` only can set the one source.  
    - Instead, `<source>` can set different video/audio sources.  

### Elements used in `<audio>` and `<video>`  
- Both  
    - src  
    - Boolean attributes  
        - controls, autoplay, loop, muted  
        - controls: It shows us a control bar.  
    - Enumerated attributes  
        - preload  
            - auto  
            - metadata  
            - none  
- only in `<audio>`  
    - poster  
    - width, height  

### `<track>`
Example  
`<track kind="captions" src="english.vtt" srclang="en" label="English" default>`  
`<track kind="captions" src="japanese.vtt" srclang="ja" label="Japanese">`

### Drawing
- `<canvas>`  

### ETC
- `<object>`  
- `<math>`  
- `<map>`  