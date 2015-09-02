# Toggle Selection

Simple module exposing function that deselects current browser selection and returns function that restores selection.

```
var deselect = require('toggle-selection');
var reselect = deselect(); // remove all selection
// … 
// do something with current selection, text, etc;
// …
reselect(); // restore selection
```

All credits go to [@shvaikalesh](https://github.com/shvaikalesh).