# 学习目标管理台 (Learning Goal Dashboard)

考研/学习目标管理的在线看板：创建目标、每日打卡、周报复盘、进度可视化。

## 在线访问

- 学习目标管理台：<https://workbuddy.link/p/ApyuWCJSTsXSaVt7W4heLx>

## 功能特性

- **今日**：今日目标、每日建议投入、打卡节奏、连续打卡、休息日、补卡记录
- **看板**：目标进度、近 14 天投入时长、近 35 天打卡热力图
- **周报**：周复盘、合计投入统计
- **我的**：目标管理（含默认时长设置）、学习进度同步

## 数据存储

数据保存在腾讯文档资料库的在线数据表（Goals / Logs / Weekly），修改即写云端，支持手动同步。本地直接打开 HTML 时自动降级为 localStorage 本地预览模式。

## 本地使用

直接用浏览器打开 `clone_work/learning-goal-final.html` 即可，无需构建。

## 技术说明

- 纯前端单页应用（HTML + JavaScript，无构建依赖）
- 接入 WorkBuddy 资料库 SDK 读写在线数据表
- 乐观更新 + 手动同步的数据写入策略
