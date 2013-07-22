---
created:
  creators:
  - panjy
  description: CJKSplitter让Zope支持中文搜索，是最流行的Zope中文搜索支持模块。
  modified: '2006-02-07 21:33:00'
  title: 'CJKSplitter: Zope中日韩全文索引断字模块'
creator: panjy
description: CJKSplitter让Zope支持中文搜索，是最流行的Zope中文搜索支持模块。
title: 'CJKSplitter: Zope中日韩全文索引断字模块'
---
:产品名称: Zope中日韩全文索引断字模块（CJKSplitter）
:许可类型: GPL开放源代码
:发布类型: Zope支持模块
:Zope版本: Zope 2.5以上版本
:产品版本: 0.7.2
:操作系统: Windows, Linux, Unix, Mac OS
:免费下载: `cjksplitter-0_7_2.tgz`__

__ http://www.zope.org/Members/panjunyong/CJKSplitter

CJKSplitter 是一个基于ZCTextIndex支持中日韩三语的全文检索断字模块，他使用unicode存储索引书籍，使用了一个简单但可用的二词算法，而不是采用词典方式。和从前的词典方式比较，他的索引数据更大但匹配更精确。

特性清单
==========
* 完全和标准的英文Splitter兼容

* 支持多种编码，包括：

  - 'CJK splitter' : 支持unicode/utf-8编码，此断字方法和0.1版本兼容

  - 'CJK GB splitter' : 支持unicode/gb18030/gbk/gb2312/mbcs 编码.

  - 'CJK BIG5 splitter' : 支持unicode/big5/mbcs编码

* 支持Archetypes最新版本中的unicode存储方法，自动识别处理unicode编码

* 支持英文模糊查询，如，可查 zop*

* 支持中文单字模糊查询

安装
==============
安装ZopeChinaPak后，如果使用 *Default Chinese Plone* 的站点策略，会自动完成中文索引设置。

下面介绍手工安装的流程：

1. 在ZMI界面中，进入catalog对象（如Plone下的portal_catalog）

2. 在“Select type to add”下拉菜单中，选择 *ZCTextIndex Lexicon* , 进入ZCTextIndex字典的添加表单，填写：

   - id: 任意，典型的如：CJKLexicon
   - Word Splitter: 这里应该选择CJK打头的Splitter, 一般选择 *CJK Splitter*

3. 填写完成后，点击 *Add* 按钮

4. 进入Catalog的索引标签页面，添加一个新的ZCTextIndex索引，选择使用前面添加的字典(CJKLexicon)

5. 对新增加的索引，需要重建立索引，可选择索引项，点击 *reindex* 按钮