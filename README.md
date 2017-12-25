# v8codecov

_v8codecov is a tool to extract JSON Objects for V8 Code Coverage for JS and CSS. Chrome DevTools Protocol Viewer APIs are used for the same._

> v8codecov takes your website name as input and throws correspoding V8 Code Coverage Objects for JS and CSS.

## Example usage
```javascript
var codecov = require('v8codecov');
codecov('https://news.ycombinator.com');
```