## 一、git 简介

### 1.1 版本控制系统分类

- 分布式版本控制系统
- 集中式版本控制系统

### 1.2 什么是 git

git  是最先进的分布式版本控制系统。

## 二、git 的基本使用

### 2.1 配置 git

```
git config --global user.name "opendragonhuang"
git config --global user.email "opendragonhuang@outlook.com"
```

- 配置的原因：因为Git是分布式版本控制系统，所以，每个机器都必须自报家门：你的名字和Email地址。
- 作用：为 git 配置用户名和用户的email。
- 参数
  - --global：表示此台计算机上的所以 git 仓库都使用这个配置。

### 2.2 创建版本库

**版本库**：版本库又名为仓库，英文名为 repository，可以简单的理解为一个目录，这个目录里的所以文件都可以被 git 管理起来。每个文件的修改，删除，git 都能跟踪，以便时刻都可以追踪历史，或者在将来的某个时刻还可一将文件”还原“。当版本库创建成功后，版本库所创建的的目录下会多了一个 .git 目录，这个目录便是 git 来跟踪管理版本的。



