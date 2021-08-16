### Instruction :
1) Open https://popcat.click
2) Open console (F12)
3) Copy code below & run

### Code :
```
var event = new KeyboardEvent('keydown', {
	key: 'g',
	ctrlKey: true
});

setInterval(function(){
	for (i = 0; i < 100; i++) {
		document.dispatchEvent(event);
	}
}, 0);
```

### Screenshot :
[![screenshot.png](screenshot.png)]()
