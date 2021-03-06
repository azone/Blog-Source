---
layout: post
title: "如何高效的使用XCode"
date: 2013-01-23 20:52
comments: true
tags: xcode
categories: Xcode
---

上周看了WWDC 2012的Session 402 - Working Efficiently with Xcode，顺便记了一些笔记。看了之后才注意到很多Xcode的快捷键和特性都没用过或者说没想到过用~，平时用的太死板，只是用了`+R`之类的快捷键。现在把上周整理的笔记贴上来吧~
<!-- more -->
- `⌘+0` 显示/隐藏导航栏
- `⌥+⌘+0` 显示/隐藏工具栏
- `⇧+⌘+O` 快速打开
- `⌘+单击` 在主编辑器中显示定义
- `⌥+⌘+单击` 在助手编辑器中显示定义
- `⌥+⌘+⏎` 显示助手编辑器
- `⌘+⏎` 隐藏助手编辑器
- 先按 `⌘+E` 再按 `⌘+G` 搜索当前所选文本，继续按`⌘+G`搜索下一个
- `⌃+⌥+⌘+2`	打开代码片段库
- `⌘+J` 多个窗口之间切换
- `⌥+→/←` 先前/向后移动一个单词
- `⌃+b/f/n/p` 向前/向后移动一个字符，向上/向下移动一行
- `⌃+⌘+E` 当前编辑器全局编辑当前光标所在的变量名或方法名
- `⌃+⇧+⌘+/` 快速帮助
- `⌘+双击` 在新窗口中显示定义
- `⌃+⌥+⌘+J`	在助手编辑器中显示定义
- 双击 `{` 选择代码块
- 搜索替换时按住 `⌥` 会将搜索栏的 "Replace All" 变成 "In Selection"
- Xcode有 **TODO** 和 **FIXME** 功能，只需要在注释中写上`TODO: xxx`或者`FIXME: xxx`即可

他们在视频中介绍了一个Automator服务，通过这个服务来达到对引入的头文件进行排序和过滤重复的功能，方法很简单，具体设置见图：

[![sort | uniq](http://farm9.staticflickr.com/8186/8408600186_3c8f005426_z.jpg)](http://www.flickr.com/photos/92204252@N08/8408600186/)

另外在这个视频中他们还介绍了Behavior、Tab和新窗口等的使用技巧来提高效率，很值得一看。