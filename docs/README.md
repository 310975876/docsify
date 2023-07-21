
> 键盘是我的舞台，Bug是我的伴奏。

## 安装docsify
```npm
npm i docsify-cli -g
```
## 初始化
```
docsify init ./docs
```
## 本地预览
```
docsify serve docs
```
## 手动初始化
如果不喜欢 npm 或者觉得安装工具太麻烦，我们可以直接手动创建一个 index.html 文件。

index.html
```html
<!DOCTYPE html>
<html>
<head>
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <meta charset="UTF-8">
  <link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify/themes/vue.css">
</head>
<body>
  <div id="app"></div>
  <script>
    window.$docsify = {
      //...
    }
  </script>
  <script src="//cdn.jsdelivr.net/npm/docsify/lib/docsify.min.js"></script>
</body>
</html>
```