# Yew 中文文档

[Build Status travis]: https://api.travis-ci.com/zzy/yew-zh-cn.svg?branch=master
[travis]: https://travis-ci.com/zzy/yew-zh-cn

**Yew** 是一个设计先进的 [Rust](https://www.rust-lang.org/) 框架，目的是使用 [WebAssembly](https://webassembly.org/) 来创建多线程的前端 web 应用。

- **基于组件的框架**，可以轻松的创建交互式 UI。拥有 [React](https://reactjs.org/) 或 [Elm](https://elm-lang.org/) 等框架经验的开发人员在使用 Yew 时会感到得心应手。
- **高性能** ，前端开发者可以轻易的将工作分流至后端来减少 DOM API 的调用，从而达到异常出色的性能。
- **支持与 JavaScript 交互** ，允许开发者使用 NPM 包，并与现有的 JavaScript 应用程序结合。

> 💥 **跟随官方 next 版本**，跟随 Yew 官方协议。
> 
> 通常，官方站点 yew.rs 访问是很通畅的。但笔者每周总有那么几次，着急查阅时，无法打开页面。因此，本仓库存在的目的仅是希望解决此问题，方便国内阅读。
> 
> **当前文档的中文版，是由 [sansx 老师](https://github.com/sansx)翻译的。谢谢！**
> 
> 此仓库构建工具为 [Rust 生态的 mdBook](https://mdbook.budshome.com)，和官方不同（官方为 node 生态的 Docusaurus 2）。

**感谢 Yew 团队的无私奉献！**

## 在线阅读

在线阅读地址：[**《Yew 中文文档》** - https://yew.budshome.com](https://yew.budshome.com)。

## 离线阅读

如果你喜欢本地阅读方式，可以使用 mdBook（[中文文档](https://mdbook.budshome.com)） 进行书籍构建：

> 构建时需要安装一些 crate，中国大陆推荐[更换默认的 Cargo 源为国内镜像源](https://cargo.budshome.com/reference/source-replacement.html)。

```bash
$ git clone https://github.com/zzy/yew-zh-cn
$ cd yew-zh-cn
$ cargo install mdbook # 指定版本使用参数：--vers "0.3.5"
$ mdbook serve --open # 或者 mdbook build
```

也可以直接用你喜欢的浏览器从 `book` 子目录打开 `index.html` 文件。

```bash
$ xdg-open ./book/index.html # linux
$ start .\book\index.html    # windows
$ open ./book/index.html     # mac
```

## 贡献

祝你学习愉快，欢迎参与：提交问题，发送 PR。
