

# css

有三种选择器：
- `#id`
- `.class`
- `label`



`box-size`: `border-box` / `content-box` (default)

# Javascript

声明变量，有三种：
- `var name = 1` 最原始的，兼容所有浏览器，不指定变量是不是改变
- `let name = 2` 指定变量可以改变
- `const name = 3` 指定变量不可以改变

`DOM`: ` Document Object Model`


类型：
- 数值：
    - 1234
    - 123.2
- 字符串
    - `'string'` / `"string"` / `"'"` / `'"'`
    - ` ``${varible}`` `


 判断语句：
 - `==` vs `===`
    - `true == 1` // true
    - `"" == 0` // true
    - `0 == false` // true
    - `0 === false` // false
    - `NaN === NaN` // false (Not a Number)
    - `isNaN(NaN)` // true
    - false: 0, "", []
    - true: 1, "xx", [0], {}
 - `>` / `<` / `<=` / `>=`
 - `||` / `&&`
 - `true || console.log("not execute")`
 - `false || console.log("will execute")`