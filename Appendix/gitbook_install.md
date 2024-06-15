# GitBook 安装

## 搭建步骤

> 搭建教程详见：https://segmentfault.com/a/1190000017960359

### 1. 配置好本地Git环境

### 2. 安装node.js，建议安装v8.11.1版本，由于gitbook依赖库版本比较低，安装高版本NodeJS会导致安装gitbook出错。

> Node. Js下载链接：https://nodejs.org/en/blog/release/v8.11.1

### 3. 安装gitbook并初始化

```
#创建gitbook安装目录并切换到该目录
mkdir gitbook
cd gitbook

# 安装gitbook-cli
npm install gitbook-cli -g

# 查看gitbook版本，查看版本时会进行安装
gitbook -V

# 初始化gitbook
gitbook init

# 启动gitbook服务，即可访问http://localhost:4000/
gitbook serve

```

### 4. 编辑电子书内容

```
# 文档格式为Markdown
# 将文档加入目录中，示例如下 

# Summary
* [Introduction](README.md)
* [C++](./C++/README.md)
    - [面向对象](./C++/test.md)
* [QT](./Qt/README.md)
* [QML](./QML/README.md)
* [附录](./Appendix/README.md)
    - [GitBook安装](./Appendix/gitbook_install.md)
    - [GitBook插件](./Appendix/gitbook_plugins.md)
    - [Markdown语法](./Appendix/markdown_syntax.md)
```

### 5. gitbook部署到github

```
# 在github上创建一个仓库
# 

```
