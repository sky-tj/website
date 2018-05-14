﻿+++
title = "域名管理"
description = ""
weight = 4
+++


# 域名管理

域名管理可以将您已经预定义好的域名规则在平台中进行配置，使外部能够通过指定的域名访问到系统内部的实例和网络。
<blockquote class="note">
         目前**Web前端**及**普通应用**需配置域名，若不配置域名，不能进行外网访问该前端，只能查看系统提供的pod ip。
      </blockquote>

  - **菜单层次**：项目层
  - **菜单路径**：持续交付>  部署管理 > 资源管理
  - **默认角色**：部署管理员

### 新建域名信息

 1. 点击 `创建域名` ，选择需要配置域名的应用，并输入“域名”、“域名地址”、“路径”及选择网络，点击 `创建` ；

 1. 创建成功后，域名将会出现在域名管理列表中。

### 编辑域名信息

点击页面右侧 ![修改环境按钮](/docs/user-guide/continuos-delivery/Assembly line/image/修改环境按钮.png) 按钮，进入修改域名界面后,对域名信息进行修改,最后`保存`。

### 删除域名信息

点击页面右侧 ![删除网络按钮](/docs/user-guide/continuos-delivery/Assembly line/image/删除网络按钮.png) 按钮，删除该域名。
<blockquote class="warning">
         若删除域名，该条数据将被永久删除，不可恢复!
      </blockquote>