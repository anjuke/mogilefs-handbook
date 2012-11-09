MogileFS Handbook
=================

本手册提供了有关MogielFS的大部分内容

Get Involved
------------

本文档使用[nanoc][1]撰写，是一个静态网站生成器。

所有主要页面在content目录下面，主要遵守以下约定

+ content目录下页面的扩展名都以html结尾
+ 暂时没有层级，全部使用第一级目录

配置开发、编译环境，您需要有ruby环境，最好是1.9.3的

确保有安装rubygems以及bundler

```
gem install bundler
bundle install
```

成功安装完即可进行文档撰写

Quick Start
-----------

**如果发现执行nanoc出错，请使用`bundle exec nanoc`**

（重新）生成output目录

```
nanoc compile
```
查看输出结果

```
nanoc view

# 然后在浏览器打开http://localhost:3000查看
```

建立新页面

```
nanoc create-item
```

发布（注意config.yml里的配置）

```
nanoc deploy
```

[1]: http://nanoc.stoneship.org/

