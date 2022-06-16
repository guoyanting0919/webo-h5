## 說明
* 本專案使用 bootstarp 5 (存放於跟目錄底下且資料夾名為 bootstrap，如更換位置請修改 assets/scss/all.scss 內相關資料位置並重新編譯)
* 修改主題複製/更變 assets/scss/helpers/_variables.scss，並依情況更變 all.scss 內路徑，並重新編譯
* 重新編譯的 CSS 檔案放在 assets/css
* Icon 等固定圖片放置於 assets/img

### live sass 的設定方法
* 打開 VSCode 內的 setting.json
```
"liveSassCompile.settings.formats": [
    {
        "savePath": "assets/css"
    }
], //scss 儲存設定
"liveSassCompile.settings.excludeList": [
    "**/bootstrap5/**",
], //scss 除外設定
```
