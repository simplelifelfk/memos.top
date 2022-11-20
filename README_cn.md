<p align="center"><a href="https://usememos.com"><img height="64px" src="https://raw.githubusercontent.com/eallion/memos.top/main/assets/img/logo-full.webp" alt="✍️ memos" /></a></p>

<p align="center">Memos Top. 通过 Memos API 渲染的静态网页.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Memos-Top-orange" />
  <img src="https://img.shields.io/badge/Author-eallion-brightgreen" />
  <a href="https://github.com/eallion/memos.top/releases" target="_blank"><img alt="GitHub all releases" src="https://img.shields.io/github/downloads/eallion/memos.top/total"></a>
</p>

<p align="center">
  <a href="https://memos.top/">Live Demo</a> •
  <a href="https://eallion.com/memos" target="_blank" rel="noopener noreferrer" class="pure-menu-link">I'm Feeling Lucky ✍</a>
</p>

<p align="center">
  <a href="https://memos.top/" target="_blank"><img alt="Memos Top" src="https://raw.githubusercontent.com/eallion/memos.top/main/screenshot.png"></a>
</p>

中文 | [English](./README.md)

### 前端框架

> 暗黑模式自适应  
> 移动端自适应  

 - [**Memos**](https://github.com/usememos/memos)
 - [BaguetteBox.js](https://github.com/feimosi/baguetteBox.js)
 - [Github-markdown-css](https://github.com/sindresorhus/github-markdown-css)
 - [Markedjs](https://github.com/markedjs/marked)
 - [Moment](https://github.com/moment/moment)
 - [Pangu.js](https://github.com/vinta/pangu.js)
 - [Pure.CSS](https://purecss.io/)
 - [Vanilla-lazyload](https://github.com/verlok/vanilla-lazyload)
 - [Vercel](https://vercel.com)

### 使用方法

1. 从 [Release](https://github.com/eallion/memos.top/releases) 页面下载，或者`clone`本仓库：

```bash
git clone https://github.com/eallion/memos.top
```

2. 设置

在 `index.html` 文件中调整以下设置：

```html
    <script type="text/javascript">
        var memos = {
            host: 'https://demo.usememos.com/',  //修改为自己部署 Memos 的网址，末尾有 / 斜杠
            limit: '10',  //默认每次显示 10条
            creatorId: '101',  //默认为 101用户 https://demo.usememos.com/u/101
            domId: '#memos',  //默认为 #memos
            username: 'memos',  //发布者 ID 自定义
            name: 'Official Demo',  //发布者全称自定义
        }

    </script>
```

3. 网站图标和头像(*可选*)

 在 `assets/img` 目录中，替换成自己的图标和头像。
 - `logo.webp` 是网站图标，显示在浏览器标签上。
 - `avatar.jpg` 是头像，显示在每条 Memos 的左侧。

4. 上传

上传 `index.html` 文件 `assets` 目录及目录中的所有文件到网站根目录。

### 部署到 GitHub Pages

> Demo: <https://www.memos.top>

1. Fork 本仓库
2. 按照 #[使用方法.2]() 设置自己的 API
3. 转到自己的 `memos.top` 仓库的设置 - `Setting` - `Pages` - `Deploy from a branch` - `Branch(main/root)`

### 部署到 Vercel

> Demo: <https://memos.top>

1. Fork 本仓库 
2. 按照 #[使用方法.2]() 设置自己的 API
3. 进入自己的 Vercel 面板
4. 新建一个 Project ，导入 GitHub 上的仓库
5. 按默认设置不用改动，直接点`Deploy`
6. 中国大陆可能需要绑定一个自定义域名才能访问 Vercel

### 关于更新

一般情况下不会更新，除非上游 Memos 有大的改动。一些简单的 Bug 自己调整一下就可以了。

### [许可证](https://github.com/me-shaon/GLWTPL)
```
GLWT（Good Luck With That，祝你好运）公共许可证
版权所有© 每个人，除了作者

任何人都被允许复制、分发、修改、合并、销售、出版、再授权或
任何其它操作，但风险自负。

作者对这个项目中的代码一无所知。
代码处于可用或不可用状态，没有第三种情况。


                祝你好运公共许可证
            复制、分发和修改的条款和条件

0 ：在不导致作者被指责或承担责任的情况下，你可以做任何你想
要做的事情。

无论是在合同行为、侵权行为或其它因使用本软件产生的情形，作
者不对任何索赔、损害承担责任。

祖宗保佑。
```