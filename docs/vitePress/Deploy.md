---
title 部署
---
# 部署
本次部署以 `github` 为例。

## 创建仓库
重点：
- 如果第二阶段打包时 `base` 参数为 `/` ，仓库名称应为 `github用户名.github.io`。（以我的账号为例，应为 `tydumpling.github.io`）
- 如果参数为 `/一个单词/` ，仓库名称也要取对应的名称。（如第二阶段我的代码是 `base: '/tydumpling/'`，仓库名称如下图所示）

![创建仓库](https://s1.ax1x.com/2023/02/01/pSBXbdg.png)

## 设置开源
把仓库设为开源

## 选择 github Pages 服务
1. 点击服务选择 `github Pages` 服务。

    ![选择服务](https://s1.ax1x.com/2023/02/01/pSBvp9A.png)

2. 选择分支
   本次项目只有一个主分支，不用操作。
3. 选择部署目录
   如果上传时上传的是整个 `vitepress` 文件夹，此时要设置部署的目录：`docs/.vitepress/dist` 。如果单独上传打包好后的 `dist` 文件夹，则不需要做其他设置，默认以整个仓库为基准路径。

最后打包成功后，会给一个链接，复制打开就能看到成品了。
