JavaScript Syntax
===

> Evaluate the basics

## Typing in Console

**Evaluate** JavaScript "on the fly"

### Evaluation

* Primitive Types
    * Numbers
      * const num = 2;
      * typeof num; 
    * Boolean
      * const bool = true;
      * typeof bool;
    * String
      * const str = 'I am a string';
      * typeof str;
* `undefined`
* `null`
   * let someNull = null;
   * someNull = null;
   * someNull;
* Operators
    * Mathematic
        * `+`, `-`, `*`, `/`, `%`
        * 1 + 1;
        * 3 - 2;
        * 3 * 2;
        * 7 / 7;
        * 4 % 2;
        * 4 % 3;
    * Logical
        * `!`, `&&`, `||`
        * ``` 
            function someFunc(a) { 
               if(a != 2) return 'not 2';
            }
            someFunc(3);
          ```
        * ``` 
            function anotherFunc(a) {
               if(a !=2 && a !=3) return 'not equal to 2 AND 3';
            }
            anotherFunc(4);
            ```
        * ```
             function lastFunc(a) {
               if (a !=2 || a !=3) return 'not equal to 2 OR 3'
             }
             lastFunc(3);
          ```
       
* Grouping via `(` `)`
   * (5 + 4) * 2;
   * 1 + (2 * 2);
* Literals
    * Arrays `[` `]`
      * const arr = ['hello', 'goodbye'];
      * arr[1];
      * arr[0];
    * Object `{` `}`
      * const obj = { hi: 'hello', bye: 'goodbye' }
      * obj.hi;
      * obj.bye;
      * Object.keys(obj);

### Remembering Values

Introducing variables...

* `var`, or `let` and `const`
   * assignment
   * reassignment
   * var
      * var three = 3;
      * three = 6;
   * let
      * let five = 5;
      * five = 6;
   * const 
      * const four = 4;
      * four = 12;
      * four;
* names
    * `a-z`
    * `A-Z`
      * const someVariable = 'banana';
    * `$` and `_`
      * const some_variable$ = 'strawberry';
    * `1-9` (not at beginning!)
      * const 1someVariable = 'apple';
      * const someVariable1 = 'apple';
* scope
   * 
   ```
   function scope() { 
      const banana = 'banana';
      return banana;
      }
      
      banana;
      
      scope();
      
   ```
* use place of the stored value!

### Increment/Decrement
* `--`/`++`
* before vs after
   ```
      let count = 1;
      
      count++;
      count;
      
      count--;
      count;
    ```

### Debugging

Stopping script

## Outcome

Use the browser console to evaluate JavaScript
