---
created:
  creators:
  - panjy
  description: Zope和Plone的"标准"中文支持包，即装即用。
  modified: '2006-10-23 20:15:05'
  title: ZopeChinaPak：Zope/Plone中文支持包
creator: panjy
description: Zope和Plone的"标准"中文支持包，即装即用。
title: ZopeChinaPak：Zope/Plone中文支持包
---
:产品名称: Zope/Plone中文支持包（ZopeChinaPak）
:许可类型: GPL开源许可
:发布类型: Zope/Plone补丁
:Zope版本: Zope 2.5以上
:Plone版本: Plone 1.0以上
:操作系统: Windows, Linux, Unix, Mac OS
:下载页面: `点击进入`__

__ http://plone.org/products/zopechinapak


ZopeChinaPak是一个zope/cmf/plone的中文补丁集合, 仅供中文Zope/Plone用户使用。

特性
============
* 即装即用，无需其他设置
* 结构化文本支持中文
* 支持中文ID
* 自动在ZMI中设置management_page_charset属性，支持在ZMI中查看中文。
* 添加中文Plone的站点定制策略：使用了Plone的，创建Plone站点的时候，选择Default Chinese Plone即可。

  - 修改catalog的index，Plone使用CJKSplitter进行断字，支持中文全文检索。同时修改为时间类型的索引为DataIndex。
  - 设置Plone缺省语言为中文

* windows上自动支持gb2312/gbk/gb18030/big5等编码, 无需安装其他的中文编解码模块

* 解决通过ftp/web导致中文文件名乱码的问题

安装
=========
下载，解压缩，拷贝到Zope实例的Products目录即可

- 需要安装 CJKSplitter_
- 参考: `Plone的中文支持`_

.. _CJKSplitter: /products/CJKSplitter
.. _`Plone的中文支持`: http://www.czug.org/docs/plone/plonebook/X_e5_ae_89_e8_a3_85Plone2/wikipage_view

