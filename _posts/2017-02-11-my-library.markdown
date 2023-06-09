---
layout: post
title:  "我的图书馆"
date:   2017-02-11 10:00:00 +0800
image: /images/software/my-library-small.jpg
categories: [我的图书馆, 软件]
---

　　藏书越来越多，记性越来越差。为了方便管理家里的图书，避免买书的时候买重，我就开发了一个自用的图书管理软件。电脑端使用的是 Delphi 开发，连接远程 MySQL 数据库，主要用于录入图书信息。支持激光扫描枪读取图书条形码，自动从豆瓣上获取图书信息，以减少手工录入的工作量。手机 Web 端大概用了一天半完工，方便随时在手机上查看。采用了 SUI＋PHP＋MySQL 技术。MySQL 数据库和 php 服务器部署在云端的一台 Ubuntu Server 虚拟机上。

　　2019年，服务器中毒导致数据全部丢失。后来，只找到了早期的备份数据，内容不全。这件事再次提醒我，数据备份很重要！

------

<h3>我的图书馆 电脑端</h3>

![我的图书馆]({{site.baseurl}}/images/software/我的图书馆-电脑-1.jpg)

![我的图书馆]({{site.baseurl}}/images/software/我的图书馆-电脑-2.jpg)

------

<h3>我的图书馆 手机端</h3>

<div class="row">
    <div class="col-md-6">
        <a href="{{site.baseurl}}/images/software/我的图书馆-手机-1.jpg" target="_blank">
            <img class="thumbnail thumbnail-border" src="{{site.baseurl}}/images/software/我的图书馆-手机-1.jpg">
        </a>
    </div>
    <div class="col-md-6">
        <a href="{{site.baseurl}}/images/software/我的图书馆-手机-2.jpg" target="_blank">
            <img class="thumbnail thumbnail-border" src="{{site.baseurl}}/images/software/我的图书馆-手机-2.jpg">
        </a>
    </div>
</div>
<div class="row">
    <div class="col-md-6">
        <a href="{{site.baseurl}}/images/software/我的图书馆-手机-3.jpg" target="_blank">
            <img class="thumbnail thumbnail-border" src="{{site.baseurl}}/images/software/我的图书馆-手机-3.jpg">
        </a>
    </div>
    <div class="col-md-6">
        <a href="{{site.baseurl}}/images/software/我的图书馆-手机-4.jpg" target="_blank">
            <img class="thumbnail thumbnail-border" src="{{site.baseurl}}/images/software/我的图书馆-手机-4.jpg">
        </a>
    </div>
</div>

------
