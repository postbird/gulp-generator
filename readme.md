## gulp-generator | gulp 开发脚手架

## 一、说明

自己使用的 gulp 开发脚手架，支持 `less/scss` , 并且支持 `js/css/html/images` 的压缩。

支持 `postcss` 自动兼容多浏览器。

主要用来开发纯静态的 html 网站，建议使用 `live-server` 作为自动刷新和本地服务。

> 需要全局安装 `gulp` 和 `live-server`

```bash
npm i -g gulp live-server
```

## 二、使用

### 克隆项目：

```bash
git clone https://github.com/postbird/gulp-generator.git
```

### 安装依赖

```bash
yarn install

## npm install
```

> 下面两步需要开启两个 bash，一个用来跑 `gulp-task` 另外一个用来跑 `live-server`

### 开启 `gulp-task`

```bash
yarn dev
# npm run dev
```

### 开启本地服务

```bash
yarn server
# npm run servver
```

### 进行开发

会使用默认浏览器开启本地服务，浏览网站。

文件更改后，自动刷新浏览器服务。

### License
 
MIT