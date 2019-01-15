### jscs
---
https://github.com/jscs-dev/node-jscs

https://www.npmjs.com/package/jscs

```
"disallowAnonymousFunctions" : true
```

```js
var a = function foo(){
};
$('#foo').click(function bar(){
});

var a = function(){
};
$('#foo').click(function(){
});


```

```
```


