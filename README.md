# Shuffle.js
🌈 Shuffle, a JavaScript GDI Program. 

Add this to any website and watch it get buzzufled.
Written by ChatGPT and revised by me to fix some bugs caused by common things and what not.

Here is the code to run it on any webpage:

```js
javascript:(function(){fetch("https://raw.githubusercontent.com/mffr/shuffle/main/shuffle.js").then(function(r){return r.text()}).then(function(s){eval(s)})})()
```

Or, just run this code in the console:

```js
(function() {
  fetch("https://raw.githubusercontent.com/mffr/shuffle/master/shuffle.js")
    .then(function(response) {
      return response.text();
    })
    .then(function(script) {
      eval(script);
    });
})();
```
