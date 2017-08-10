# codeBase64
A  JavaScript plug-in that can encode and decode characters with Base64.<br>

### Illustration
This plug-in can used for characters that UNICODE is between 0000 0000 and 0000 FFFF.<br>
Include Number, English, Chinese, Korean and so on.<br>
And you can set the Secret Key by your own situation.

### Example
I write a simple demo for example.[Online Demo](https://youyou-happy.github.io/codeBase64/example/index.html)<br>
If you do not fill Secret Key, the default is null. Result will encode or decode your input directly.

### Usage
To use codeBase64, the following files should always be included.<br>
```html
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
<script type="text/javascript" src="codeBase64.js"></script>
```
Suppose we want to encode a string, then decode it. If you do not fill Secret Key, the default is null. Result will encode or decode your input directly. CodeBase64 makes it as simple as:<br>
```javascript
var result = codeBase64.encode('hello'[,headKey,endKey]);
var str = codeBase64.decode(result[,headKey,endKey]);
```
