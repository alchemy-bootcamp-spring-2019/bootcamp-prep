Control Flow
===

> Managing variation and repetition

## Run to Completion

Follow the thread of execution...

### Keywords

Structure:

```js
keyword(condition) {
    // controlled code
}
```

### Conditional

* `if`

```js
const a = 2
if(a === 2){
    a = 5;
}
```
* `else if`

```js
    function elseIf(a) {
        if(a === 2) {
            return 'A is equal to 2.';
        }
        else if (a ===3) {
            return 'A is equal to 3.';
        }
    }
}
```
* `else`

```js
    function elseIf(a) {
        if(a === 2) {
            return 'A is equal to 2.'
        }
        else {
            return 'A did not meet any of the given conditions';
        }
    }
}
```

### Loop

* `while`

```js 
while (i < 10) {
  console.log("The number is " + i);
  i++;
}
```
* `for`

```js 
for(i = 0; i =< 10; i++) {
    console.log("The current count is", i)
}

## Outcome

Commit with page that logs even numbers up to 100
