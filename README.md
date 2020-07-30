# eslint


Unexpected trailing comma

[要求或禁止使用拖尾逗号 (comma-dangle)](http://eslint.cn/docs/rules/comma-dangle)

```js
  rules: {
    "comma-dangle": ["error", "always"],
  },
```

Missing space before function parentheses

https://eslint.org/docs/rules/space-before-function-paren

` "space-before-function-paren": ["error", "always"],`

> Missing trailing comma

"rules": { "trailing-comma": false }

http://eslint.org/docs/rules/comma-dangle                
Missing trailing comma

`"comma-dangle": ["error", "ignore"],`

✘  http://eslint.org/docs/rules/space-before-function-paren  
Missing space before function parentheses

✘ 10 problems (10 errors, 0 warnings)

"space-before-function-paren": ["error", "ignore"],
"space-before-function-paren": 'off',

## Linting tool

 .eslintignore
和git一樣的使用方式，ESLint也提供ignore讓我們設定哪些檔案可以被忽略。

```js
lib/
```