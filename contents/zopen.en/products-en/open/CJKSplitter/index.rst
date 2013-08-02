---
created: ''
creator: panjy
description: "CJKSplitter is a ZCTextIndex splitter for CJK (Chinese-Japenese-Korea)\
  \ text\r\n  stored as Unicode.  It uses a simple, but workable, \"hack\" instead\
  \ of trying\r\n  to do real word splitting from dictionaries.  Compared to a dictionary\
  \ based\r\n  word splitter, this results in a bigger index and more matches than\
  \ necessary,\r\n  but it is a cheap price to pay for the reduced complexity."
title: CJKSplitter - Chinese, Japanese, Korean word splitter for ZCTextIndex
---
Feature
===============
- use regular expression to compatible with defualt English white space splitter

- much simpler code, easy to install, easy to use

- support multiple encodings: unicode/utf-8/gb18030/gbk/gb2312/mbcs/big5. provide 3 splitters(more to come):

  * 'CJK splitter' : support unicode/utf-8 encoding. 

  * 'CJK GB splitter' : support unicode/gb18030/gbk/gb2312/mbcs encodings.

  * 'CJK BIG5 splitter' : support unicode/big5/mbcs encodings

- support english globing

- support single Chinese charactor search

