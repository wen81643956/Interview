# 什么是 this?

`this`是一个 javascript 的关键字，this 概括来说可以在两种环境下访问。一是全局环境，一是函数内。

## this 的指向

-   node 全局环境中指向 `global` 对象

    ```js
    this === global // true
    ```

-   node 的 js 文件模块中指向 `module.exports`

    ```js
    this === module.exports //true
    ```

-   浏览器全局环境中指向 `Window` 对象

    ```js
    this === Window //true
    ```

-   es 模块全局范围内指向 `undefined`
    ```js
    this === undefined //true
    ```
