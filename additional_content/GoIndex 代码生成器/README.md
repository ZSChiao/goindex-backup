# goindex-installer
[GoIndex](https://github.com/donwa/goindex) 代码生成器

donwa大佬的[GoIndex 代码生成器](https://install.gd.workers.dev/)的开源版本，可以自己部署，解决隐私问题

## 注意
这里使用的还是[Rclone](https://github.com/rclone/rclone)程序提供的OAuth 2.0客户端ID和秘钥，如果你比较介意，可以到[Google API Console](https://console.developers.google.com)申请自己的ID和秘钥并替换使用

## Demo
[https://install.mdrive.workers.dev/](https://install.mdrive.workers.dev/)

## 部署
到[Cloudflare Workers](https://dash.cloudflare.com)创建一个新的Worker，复制[main.js](main.js)中的内容保存并部署即可
