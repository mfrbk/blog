---
title: 实现自动化部署
date: 2026-05-06 14:32:00
tags:
  - DevOps
  - GitHub Actions
categories:
  - 技术
---

## 概述

本文介绍如何使用 GitHub Actions 实现博客的自动化部署。

## 配置步骤

### 1. 创建 Workflow

在项目根目录创建 `.github/workflows/deploy.yml` 文件。

### 2. 配置 Secrets

在 GitHub 仓库设置中添加 `DEPLOY_KEY`。

### 3. 自动部署

每次推送到 `main` 分支时，GitHub Actions 会自动构建并部署到 GitHub Pages。
