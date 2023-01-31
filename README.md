<h1 align="center">欢迎使用中国色 👋</h1>
<p>
  <a href="https://www.npmjs.com/package/colorofchina" target="_blank">
    <img alt="Version" src="https://img.shields.io/npm/v/colorofchina.svg">
  </a>
  <a href="https://github.com/heixinyouzi/ChineseColor#readme" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/heixinyouzi/ChineseColor/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
  <a href="https://github.com/heixinyouzi/ChineseColor/blob/master/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/github/license/heixinyouzi/chinesecolor" />
  </a>
</p>


### 🏠 [Homepage](https://github.com/heixinyouzi/ChineseColor#readme)



# 使用方法

## 安装

```sh
npm install colorofchina
```
## 1.vue2

####  >> css: main.js 中添加 

``` javascript
// 引入中国色样式
import 'colorofchina'
```

####  >> less: main.js 中添加 

``` javascript
// 引入中国色样式
import 'colorofchina/color.less'
```

####  >> scss: main.js 中添加

``` javascript
// 引入中国色样式
import 'colorofchina/color.scss'
```


## 2.vue3+vite

####  >> css: main 中添加

``` javascript
// 引入中国色样式
import 'colorofchina'
```

####  >> less: vite.config.js 中添加 

``` javascript
css:{
    preprocessorOptions:{
      less:{
        additionalData:'@import "colorofchina/color.less";'
      }
    }
  },
```
####  >> scss: vite.config.js 中添加

``` javascript
css:{
    preprocessorOptions:{
      scss:{
        additionalData:'@import "colorofchina/color.scss";'
      }
    }
  }
```


## Author

👤 **黑心柚子**

- Github: [@heixinyouzi](https://github.com/heixinyouzi)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/heixinyouzi/ChineseColor/issues).

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2023 [黑心柚子](https://github.com/heixinyouzi).<br />
This project is [MIT](https://github.com/heixinyouzi/ChineseColor/blob/master/LICENSE) licensed.

---

_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
