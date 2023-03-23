---
layout: post
title:  "VCF Encoding"
date:   2009-06-19 10:00:00 +0800
image: /images/software/vcf-encoding-small.jpg
categories: [VCF, VCF Encoding]
---

　　飞翔 VCF 文件编码转换器，又名VCF Encoding。该软件设计的初衷是为了解决飞翔通讯录导入 VCF 文件出现的乱码问题。但是自2008年发布以来，软件获得了广大需要解决 VCF 名片乱码问题的用户的喜爱，之后根据用户反馈有多次升级。但是2010年之后，由于作者本人的原因，该软件长久没有更新。

　　2013年新年过后，作者重写了 VCF Encoding 的源代码，使其全面支持 VCard 2.1、3.0 标准，解决了  Unicode、UTF-8、UTF-7、ANSI、Big-endian Unicode 编码问题，支持对嵌入图片和声音资源的解析，支持对 VCF 名片的拆分和合并。目前对大多数的乱码问题都已经有效解决。

------

<h3>VCF 文件编码转换  1.2</h3>

　　该软件可以将编码格式有 Unicode、UTF-8、ANSI 的 VCF 文件转换成标准的 ANSI 编码格式，以便于飞翔通讯录等通讯录软件的识别。飞翔通讯录从1.0.2版本就已经提供对VCard文件（.vcf）的支持。但是手机导出的VCF文件，可能使用的编码格式比较特殊，所以飞翔通讯录可能不能够正确识别其中的信息。

![VCF 文件编码转换  1.2]({{site.baseurl}}/images/software/VCFEncoding_V1_2-1.png) 

------

<h3>飞翔 VCF 文件编码转换器  2.0</h3>

　　VCF 格式通讯录格式现在用途广泛，一般手机导出通讯录的格式即为 VCF。但是在不同设备或软件之间导入VCF文件基本都有乱码。飞翔 VCF 文件编码转换器(VCF Encoding)可以很好的解决该问题，使用 VCFEncoding 将 VCF 文件重新输出一下即可。VCFEncoding 可以识别 VCF 文件的编码（支持 Unicode、UTF-8、UTF-7、ANSI、Big-endian Unicode），并对其进行重新编码，以便于飞翔通讯录、祥云联系人等通讯录软件的识别。

![飞翔 VCF 文件编码转换器  2.0]({{site.baseurl}}/images/software/VCFEncoding_V2_0-1.png) 

------

<h3>网上对 VCF Encoding 的评价</h3>

![网上对 VCF Encoding 的评价]({{site.baseurl}}/images/software/VCFEncoding_网上评价.png) 

------