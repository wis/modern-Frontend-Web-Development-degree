# Node.js Asynchrony, Control-flow and Error handling

## Asynchrony
- ***any* object or function** that *represents* an *asynchronous* ***value* or *error***.
-### Examples:
```js
// Callbacks
function callback(err,value) {
    if(err) { // do somthing with err
        return;
    }
    // do somthing with value
}
// Promises
promise.then(val => {

}, err => {

});

```

