---
layout: post
title: '做一个DialogueSystem'
date: 2022-04-11
author: Sphinx
color: rgb(135,206,235)
cover: 'https://i.loli.net/2021/01/20/gFvVkBMldKSHfCP.jpg'
tags: gameplay
---

从GDC回来揽了个活儿，要做一个中国古代背景的，类Disco Elysium的游戏。
这样开发一个支撑 branching对话，以及 D&D判定 玩法的 Dialogue System 就成了程序的重要工作。

有branching的DialogueSystem要怎么做是一个重要决策，是应该在Unity里做一个带Graph的编辑器，还是用已经有的branching软件导入，还是两个都要。

我做了一个简单的线性的System。
发现Disco Elysium不是自己从头做的DialogueSystem，而是用了一个叫做 Dialogue System For Unity 的东西。
这种决策又应该怎么做呢。
如果我们要用这个现成的系统，那其他的呢。