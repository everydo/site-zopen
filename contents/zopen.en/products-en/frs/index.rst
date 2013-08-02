---
created: ''
creator: admin
description: An open, scalable file system based content storage for Plone.
title: ZOpen FRS - Plone File Repository System
---
==========================================
ZOpen FRS - Plone File Repository System
==========================================

An open, scalable file system based content storage for Plone.

.. image:: img/zopen-frs.gif
   :class: image-right image-noborder

ZOpen FRS adapts Plone to store content in file system directly. Content metadata is stored as xml files. 

With simple cut/paste operations, you can dump plone content to the file system. ZOpen FRS supports content versioning and content trash box too. 

Why ZOpen FRS?
=========================
Plone stores content in ZODB  by default. It works quite well for most sites. But it has many shortcomings in ECM area:

- ZODB is a black box. We have no way to access contents once any part of the zope/cmf/plone/add-on-products stack works wrong. The content is hard to be used by other CMS systems.

- FileStorage is ZODB's fastest and most mature storage. But it stores all content in a single file. It is hard to split and backup. When packing FileStorage, the system will consume double space to store the packed and original file.

- ZODB is not adequate to store large files. The performance will be quite slow with large files.

- It is hard to integrate with other software, such as enterprise search engine, stream media server and others.

- It is hard to migrate content. Migrating content need to know the many Zope/Plone programming details.

Benefit from ZOpen FRS
==========================
- Open storage format. Contents are stored in file system. All metadata are stored as xml files.

- Scalable. Contents can be distributed in different disks, or event different servers.

- Easy to dump Plone content to the file system. Just copy and past are enough.

- Easy to migrate, no Zope/Plone knowledge needed. Since the storage format is open, it is easy to write a migration script with existing XML technologies such as XSLT.

- Easy to integrate with other system such as enterprise search engine, stream media server and NAS server. 

- Revisions management. You can keep all the historical revisions for your contents.

- Easy to split any part of the site and mount to another site.

- Trash box management. You will never worry about lost some thing by wrong operations.

- Using a virtual file system internally. It can run on both Windows and Linux system. And it supports Chinese and other non-ascii characters well.

Why not other solutions?
===========================
There are some other related opensource solutions in Plone community, such as ExternalStorage, FilesystemStorage and ATManagedFile. After some investigation, we found they only stores file but not metadata in the file system. Also, they can't manage files in the file system directly. Other advanced features like trash box management and revision management are missing too.

See the demo
====================
`Click here <http://download.zopen.cn/zopen-frs-en.htm>`__ to see the demo(Flash).

Buy this product...
=========================
ZOpen FRS is a Plone add-on product. If you have interest with this product, please `contact us </contact-info>`__.

Sorry, we heard commercial addon products may violate Plone's GPL license. **So we stopped the product selling plan.** Instead, these is an opensource version here:

http://plone.org/products/frs
