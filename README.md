# SoftwareInnovation

## 简介

这是一个web应用，整合了校内外的竞赛、项目和校企信息等。

## 需求背景

考虑到目前创新创业类的竞赛有很多，另外有些校企和学生项目也需要发布一些信息，我们可以将这些信息集中在一起，提供给交大的学生，方便他们关注并参与。我们找到来自创业中心的老师，跟他沟通了我们的想法，他也给我们提供了一些建议。因此我们决定开发一个专属于交大创业中心的活动平台。

## 需求描述

- 发布竞赛/项目/校企活动
- 查看竞赛/项目/校企活动
- 审核竞赛/项目/校企活动
- 删除竞赛/项目/校企活动
- 评论竞赛/项目/校企活动
- 竞赛组队

## 项目结构

本项目采用微服务架构，分为服务注册中心，Server端服务和Web端，分别位于两个独立的仓库进行开发。

服务注册中心使用Spring Cloud开发，项目地址为：https://github.com/sjtusoftwareinnovation/sip-registration

Server端使用java开发，项目地址为: https://github.com/sjtusoftwareinnovation/SIP_Server

Web端使用nodejs开发，项目地址为: https://github.com/sjtusoftwareinnovation/SIP_Web
