---
created:
  creators:
  - panjy
  description: ZOpen ECM是润普企业内容管理解决方案的基础平台，用于构建内部网、知识管理、文档管理等解决方案。
  modified: '2006-12-29 22:08:38'
  title: ZOpen ECM：企业内容管理平台
creator: panjy
description: ZOpen ECM是润普企业内容管理解决方案的基础平台，用于构建内部网、知识管理、文档管理等解决方案。
title: ZOpen ECM：企业内容管理平台
---
.. image:: zopen-sever-160.jpg/image_preview
   :class: noborder image-right image-noborder

:产品名称:  ZOpen ECM
:许可类型:  商业许可
:发布类型: Plone扩展产品 + 独立打包
:Plone版本: Plone 2.1
:产品版本: 2.1版本
:操作系统: Windows2000/XP/2003
:购买联系: sales@zopen.cn

很多用户，希望在自己的公司用上Plone：

 “ `Plone </technology/zope/AboutPlone>`__ 太迷人了，我希望在我们公司也安装Plone，做个内部网、文档发布，或者知识管理方面的应用...”

但是，他们往往在使用中遇到一些障碍：

* 安全方面的考虑，Plone默认权限策略并不适用企业内部应用。Plone内网的权限策略如何定制才最合适？

* 这样，Plone成为员工的日常工作系统了。这要求Plone有更强易用性，特别是在文档管理方面需要更强的功能。

* 不希望把时间浪费在Plone的中文化设置安装、维护和管理工作上，希望快速地、企业级地部署Plone

* 希望得到商业公司的支持，让系统的运行更加有保障

如果您遇到类似的问题，那么ZOpen ECM是你的选择！

ZOpen ECM是Plone的一个内部网版，它针对企业内部网应用的需求，在Windows平台上的基于Plone定制开发的一个即装即用的中文企业内容管理服务器软件。

.. Contents:: 特性清单：
.. sectnum::

中文全文搜索
=====================
支持对常用的Word/Excel/PPT/PDF等格式文档进行全文搜索，可搜索到文档内部的文字。

和桌面编辑器集成
=========================
.. image:: file-externaleditor.png/image_thumb
   :class: image-right
   :target: file-externaleditor.png/image_view_fullscreen

在网页上点击“编辑”链接，可直接激活word等编辑器进行编辑，可自动保存文件到服务器。

此功能大大简化通常的文件下载、编辑、上传的复杂过程，实现了和桌面编辑器的无缝集成。

文件拖放
=================
.. image:: batch-ftp.png/image_thumb
   :class: image-right
   :target: batch-ftp.png/image_view_fullscreen

在IE浏览器中点击网页上的链接，无需二次登录，可直接激活windows的web文件夹，使用Windows资源管理器查看网站上的文件。

用户可在资源管理器中，进行文件拖放，实现文件批量上传下载。

文档在线查看
================
.. image:: file-preview.png/image_thumb
   :class: image-right
   :target: file-preview.png/image_view_fullscreen

直接在浏览器中查看word、PPT、PDF等格式的文件，用户甚至不必安装相应的桌面编辑软件。

此功能简化了文档的下载、打开的繁琐(耗时)过程，方便文档的查看。

邮件发送
=================
.. image:: sendto.png/image_thumb
   :class: image-right
   :target: sendto.png/image_view_fullscreen

点击网页发送图标，可直接在网站上，通过填写表单发送文件邮件到指定地址。

可查找网站集成的用户邮件地址薄，选择接收用户的邮件地址。用户不必借助任何其他工具，可方便发送文件。


分类管理
=======================
.. image:: viewlet-categoried-listing.png/image_thumb
   :class: image-right
   :target: viewlet-categoried-listing.png/image_view_fullscreen


- 在文件夹上可设置可选的分类
- 可直接继承上层文件夹的可选分类设置
- 所有的Plone标准内容都可设置分类
- 针对分类，进行统计和查询

本地组管理
=================
.. image:: viewlet-local-groups.png/image_thumb
   :class: image-right
   :target: viewlet-local-groups.png/image_view_fullscreen

通常的权限集中管理模式中，所有权限设置均由系统管理维护，导致系统管理员工作任务繁重，由于相互沟通的成本导致管理效率低下。

Plone自身已经提出了权限委托管理的功能，可指派栏目负责人委托权限管理。本地组的功能更加深化了权限委托管理的概念，允许栏目负责人分组管理栏目内用户。

本地组管理的典型应用是项目的组员管理。

企业内部网权限策略
================================
和Plone外网权限策略不同，企业内网通常更加要求注重内容的安全性，同时要求尽量简化权限的管理。

内部网的权限策略
  系统提供“内部”、“公开”、“保密”三种不同的权限策略，满足不同内容的权限管理需要。

支持团队协同工作
  团队工作人员能够修改自己添加的内容，但是不能修改和删除其他人添加的内容。

完全中文化的Plone支持
=========================
rpIntranet产品为Plone提供最完整的中文支持。包括：

- 全中文的web界面
- 中文全文检索
- 中文文件名和中文目录的支持
- 各种中文编码(gb/big5)的支持
- FTP和Webdav访问的中文支持
- 打包的第三方产品中文支持的改进

自动化的系统管理
=====================
- 服务程序以windows服务的形式存在，方便控制和管理
- 安装程序可自动安装ZODB增量循环备份、log日志循环处理

即装即用的Windows安装程序
=============================
- 全中文的Windows标准安装程序
- 打包常用产品的最新稳定版本，部分产品有适度修补
- 安装后，服务器使用ZEO架构，便于系统扩展
