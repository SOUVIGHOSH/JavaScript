# The “script” tag
JavaScript programs can be inserted almost anywhere into an HTML document using the <script> tag.
The <script> tag contains JavaScript code which is automatically executed when the browser processes the tag.
We can also add external script, we can add using src, we provide absolute/relative/full url, We can also provide multiple scipt tag , the benefit is the 
external script gets cached.
If src is set, the script content is ignored.  
  
# Statements
A semicolon may be omitted in most cases when a line break exists.
In most cases, a newline implies a semicolon. But “in most cases” does not mean “always”!
But there are situations where JavaScript “fails” to assume a semicolon where it is really needed.
```
  alert("Hello")

[1, 2].forEach(alert);
  ```
This does not work, only hello prints as js does not add semicolon before [].  
  
#Comments
  we can use // for single line /* */ for multiline comment.
