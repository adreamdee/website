﻿+++
title = "应用版本"
description = "由于 Choerodon 采用 GitLab 管理分支，所以对于版本的控制也是根据 Feature、Release、Hotfix、Bugfix、custom 等分支在 GitLab 的 CI/CD 进行的, 针对具体分支上提交可以生成相应的版本。"
weight = 3
+++

# 应用版本
 
 由于 Choerodon 采用 GitLab 管理分支，所以对于版本的控制也是根据 Feature、Release、Hotfix 等分支在 GitLab 的 CI/CD 进行的

  - **菜单层次**：项目层
  - **菜单路径**：开发流水线 > 应用版本
  - **默认角色**：项目所有者、项目成员、部署管理员

## 查看应用版本详情

 1. 进入`开发流水线`后，点击 `应用版本` 页签；

 1. 查看应用版本信息。

列表字段

 - 应用版本：迭代升级中对应的不同版本；

 - 应用编码：创建应用的自定义编码；

 - 应用名称：创建应用的自定义名称；

 - 创建时间：应用创建时的时间。
 
## 版本生成命名规则
 
 - 非 tag 版本的版本默认命名为 `年.月.日-时分秒-分支名`。对应 `%Y.%M.%D-%H%Min%S-%branch` 。各变量说明如下：
 
     变量|说明  
     --- | ---
     %TimeStamp|完整的时间戳
     %Y|提交年份
     %M|不以0开头的提交月份
     %Mon|包含0开头的提交月份
     %D|不以0开头的提交日
     %Day|包含0开头的提交月份
     %H|提交小时，24小时制
     %Min|提交分钟
     %S|提交秒
     %branch|分支名称
     %commit|八位的 commit SHA
     
     > 变量的使用以及版本详细逻辑参考 [cibase](https://github.com/choerodon/cibase) 。
     
     > e.g. 分支名为feature-demo，提交时间2018年07月10日19:25:11， 那么得到的版本号为：2018.7.10-192511-feature-demo
  
 - tag 版本的版本默认命名为版本号，参考[语义化版本](https://semver.org/lang/zh-CN/)。版本自定义变量与非 tag 版本相同。
 