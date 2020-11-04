[TOC]

# Blog
Blog

## Static Pages
### [1. Index Page](index.html)
- [x] Navigation
- [x] Content
- [x] Footer

### [2. Blog Page](blog.html)
- [x] Frame
- [x] Content
- [x] Button Action

### [3. Types Page](types.html)
### [4. Tags Page](tags.html)
### [5. Archive Page](archive.html)
### [6. About Page](about.html)


## 插件
[Editor, Markdown](https://pandao.github.io/editor.md/)
1. 引入 CSS
2. 引入 js
3. 定义 div element，添加一些测试的内容
4. 初始化 js，
    * 注意初始化 lib 目录
    * 设置 z-index
    * 只在客户端，手机端可能用不了

[Content arange, typo.css](https://github.com/sofish/typo.css)
1. 引入 CSS，`<link rel="stylesheet" href="./static/css/typo.css">`
2. add `class = typo typo-selectoin`, 文章内容部分。可能出现和 static/css 相互冲突的情况，要做一些改变
    * Add prefix, add `.typo` in the beginning of line #40 in `typo.css`
    * table, `class="ui table"`, 使用 sementic ui 的 table，以便自适应手机端
    
[Animation, animate.css](https://daneden.github.io/animate.css/)
    * [Usage](https://animate.style/#usage), `<h1 class="animate__animated animate__bounce">An animated element</h1>`,
    使用的时候，必须加上 `animate_annimated animate_<animate action>`, 前缀 `animate_annimated` 不可少。
    
[Code Highlight, prism](https://github.com/PrismJS/prism)
