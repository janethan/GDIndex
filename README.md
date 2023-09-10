# GDIndex

一共两套搭建模板`worker`和`worker1`，建议使用`worker1`。

### 搭建方法：
- 根据`build-worker.js`里的中文提示修改一下，然后发布到CF的workers项目里就能运行了。
>注意：
`clientId`、`clientSecret`和`redirectURI`这三项必改，`jsURL`后面的链接改不改都行。
其中`redirectURI`必须是在 [谷歌OAuth 同意屏幕](https://console.cloud.google.com/apis/credentials/consent) 和 [谷歌API凭据](https://console.cloud.google.com/apis/credentials) 里添加过的域名，支持自定义域名或CF帐号里（类似于`abcde.workers.dev`）的三级域名。
