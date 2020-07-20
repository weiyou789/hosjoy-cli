# HosjoyCli

一个快速上手的前端脚手架, 轻松创建项目模板, 实现0配置, 快速开发。

## Features

- 支持多类型项目模板, 模板都会集成代码扫描, 工作流等, 具体查看模板github地址。
- 支持添加项目模板, 删除项目模板(flok 作为自己的工具推荐使用)
- 支持自动检测脚手架更新

## Installation & Quick start

### 安装

Windows系统安装
```
$ npm i hosjoy-cli -g
```

Mac下安装
```
$ sudo npm i hosjoy-cli -g
```

### 查看帮助信息

```
$ hosjoy-cli
```


### 创建项目

```
# 指定项目名字创建项目
$ hosjoy-cli create 模板名<template-name> 项目名字<project-name>

# 在当前目录创建项目
$ hosjoy-cli create 模板名<template-name> .
```

### 查看所有支持的项目模板

```
$ hosjoy-cli list
```

### 添加项目模板

```
$ hosjoy-cli add 模板名<template-name> 模板github仓库地址,支持ssh/https格式<git-repo-address>
```

### 删除项目模板

```
$ hosjoy-cli delete 模板名<template-name>
```
