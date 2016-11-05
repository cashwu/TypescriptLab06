# Lab 06

## 練習步驟

1. 安裝 jQuery 定義檔

1. 使用 jQuery 定義檔

    ```
    /// <reference path="scripts/typings/jquery/jquery.d.ts" />

    var dom = $('#content');
    dom.html('Hello Definition Type');
    ```

1. 自己產生定義檔

    ```
    tsc --declaration file.ts
    ```


