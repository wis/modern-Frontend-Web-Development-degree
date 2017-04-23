# Node.js Asynchrony, Control-flow and Error handling

## Asynchrony
- ***any* object or function** that *represents* an *asynchronous* ***value* or *error***.

### Examples:
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


![alt text][gif]

[gif]: https://raw.githubusercontent.com/wesamco/modern-Frontend-Web-Development-degree/master/notes/node.js/asynchrony/credits-to-Wassim-Chegham%E2%80%8F.gif "Callbacks vs Promises vs async & await operators -credits to Wassim Chegham‏"




