# picgo-uploads for typora


Install:

> npm install picgo -g
npm WARN deprecated request@2.88.2: request has been deprecated,  see https://github.com/request/request/issues/3142
npm WARN deprecated mkdirp@0.5.4: Legacy versions of mkdirp are  no longer supported. Please update to mkdirp 1.x. (Note that the  API surface has changed to use Promises in 1.x.)
C:\Users\ambse\AppData\Local\nvs\default\picgo ->  C:\Users\ambse\AppData\Local\nvs\default\node_modules\picgo\bin\picgo


> ejs@2.7.4 postinstall  C:\Users\ambse\AppData\Local\nvs\default\node_modules\picgo\node_modules\ejs
> node ./postinstall.js


Thank you for installing EJS: built with the Jake JavaScript  build tool (https://jakejs.com/)


+ picgo@1.4.7
added 424 packages from 266 contributors in 40.531s

Check install:

> picgo --version
1.4.7

Config file location: 

> cat C:\Users\ambse\.picgo\config.json
{
  "picBed": {
    "current": "smms",
    "smms": {
      "token": "#############################"
    }
  },
  "picgoPlugins": {}
}


source:  https://picgo.github.io/PicGo-Core-Doc/zh/guide/config.html#picbed

Working config:

{
  "picBed": {
    "current": "smms",
    "smms": {
      "token": "##############################"
    }
  },
  "picgoPlugins": {}
}

Test run:

> picgo upload .\aws-bill.png
[PicGo INFO]: Before transform
[PicGo INFO]: Transforming...
[PicGo INFO]: Before upload
[PicGo INFO]: Uploading...
[PicGo SUCCESS]:
https://i.loli.net/2020/03/24/5r2YLAlWF7NK4qb.png



GITHUB CONFIG

{
  "repo": "nonbeing/picgo-uploads", // 仓库名，格式是username/reponame
  "token": "##################", // github token
  "path": "", // 自定义存储路径，比如img/
  "customUrl": "", // 自定义域名，注意要加http://或者https://
  "branch": "" // 分支名，默认是master
}

full config: working with GitHub:


