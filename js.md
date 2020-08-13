# Javascript

### variables

```js
// 3 ways to make variables
var hi = 'hello'
let hi = 'hello' // let is better
const hi = 'hello' // consts cant change
```
**variable types**
```js
// simple types
let hi = 'hello' // string
let num = 10 // number
let bool = true // boolean

// compound types (you can mix-and-match types)
let arr = [1,2,3,'hi'] // array
arr[3] // equals 'hi'

let obj = { // object 
    hi: 'hello',
    n: 1001,
    b: false,
    funky: function(){
        // you can even put functions inside
    }
}
obj.funky() // will run the funky function
obj.n // equals 1001
obj['n'] // ALSO equals 1001 !!!

// functions are also variables!
var funky = function(){
    console.log('a funky function')
}
```
