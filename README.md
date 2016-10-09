# nanoclipboard

nanoclipboard is a JavaScript library for copy text to the clipboard. nanoclipboard has no dependencies.

## Usage
```js
var clipboard = new NanoClipboard("#btn");

clipboard.onSuccess = function(text) {
	alert("Copied: " + text);
};

clipboard.onError = function(text) {
	window.prompt("Ctrl+C: ", text);
};

```

## CDN
nanoclipboard's CDN provided by [jsDelivr CDN](https://www.jsdelivr.com)

> https://www.jsdelivr.com/projects/nanoclipboard

## Demo
- [basic-copy.html](https://rawgit.com/bornbit/nanoclipboard/master/demo/basic-copy.html)
- [input-copy.html](https://rawgit.com/bornbit/nanoclipboard/master/demo/input-copy.html)

## License

[MIT](https://github.com/bornbit/nanoclipboard/blob/master/LICENSE) License
