1 eslint ':label' should be on a new line

```
// 下面的2:error   1:warning    0:off
"vue/max-attributes-per-line": [
      0,
      {
        "singleline": 20,
        "multiline": {
          "max": 1,
          "allowFirstLine": false
        }
      }
    ],
```

参考[]([https://eslint.org/docs/latest/rules/linebreak-style](https://eslint.vuejs.org/rules/max-attributes-per-line.html))
