# Description

An element for including exclude resources like PDF, image, etc.

## Attributes

### Required

- type: The content type of the resource(MIME Type)
- data: the URL of the contents as a valid URL.

### ETC

- width/height

### ~~`<param>`(Deprecated)~~

```
<object data="flash.swf" type="application/x-shockwave-flash" width="480" height="300" typemustmatch>
		<param name="movie" value="flash.swf">
		<param name="quality" value="high">
		<p>It is no longer supported.</p>
</object>
```

### Example

`<object type="application/pdf" data="foo.pdf"></object>`
