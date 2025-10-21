# UserTools - 用户管理系统

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-Proprietary-red.svg)

**一个功能强大的用户管理和卡密系统**

</div>

---

## 📖 项目简介

　　UserTools 是一个现代化的 Emby 用户管理系统，提供完整的用户生命周期管理 · 卡密系统 · 推广计划等功能 · 采用前后端分离架构

---

## ✨ 核心功能

### 🔐 用户管理
- ✅ 用户信息管理
- ✅ 批量操作支持
- ✅ JWT 令牌认证
- ✅ 用户注册与登录
- ✅ 权限管理（管理员/普通用户）

### 🎫 卡密系统
- ✅ 批量生成卡密
- ✅ 使用记录追踪
- ✅ 卡密兑换与续费
- ✅ 一键清理已用卡密

### 📊 数据统计
- ✅ 实时用户统计
- ✅ 卡密使用分析
- ✅ 收益数据展示
- ✅ 可视化仪表盘
- ✅ 系统状态监控

### 🎁 推广计划
- ✅ 收益统计
- ✅ 邀请码生成
- ✅ 邀请奖励系统
- ✅ 积分兑换卡密
- ✅ 推广记录查询

### 👨‍💼 管理员功能
- ✅ 设备管理
- ✅ 系统配置管理
- ✅ 实时会话监控
- ✅ 操作日志记录
- ✅ 用户封禁/解封
- ✅ 用户管理与监控

---

## 🎨 界面展示

<div align="center">

#### 首次部署 - 创建管理员
![创建管理员](images/screenshots/admin-setup.png)

#### 登录页面
![登录页面](images/screenshots/login.png)

#### 仪表盘
![仪表盘](images/screenshots/dashboard.png)

#### 管理员面板
![管理员面板](images/screenshots/admin-panel.png)

#### 推广中心
![推广中心](images/screenshots/invite-center.png)

#### 系统设置
![系统设置](images/screenshots/settings.png)

</div>

---

## 🚀 技术特点

- 🔄 **优雅关闭** - 支持平滑重启和升级
- 📝 **完整日志** - 操作记录，便于追踪
- ⚡ **高性能架构** - 快速响应，支持高并发
- 📦 **轻量部署** - Docker容器化，一键部署
- 🗄️ **数据持久化** - SQLite数据库，稳定可靠
- 🔒 **安全可靠** - 密码加密、JWT认证、SQL注入防护

---

## 💻 部署方式

### Docker 部署（推荐）

系统支持 Docker 容器化部署，简单快捷：

```bash
docker run -d \
  --name usertools \
  -p 505:505 \
  -v ./data:/data \
  -v ./configs:/configs \
  -v ./logs:/logs \
  usertools:latest
```

### 系统要求

- **端口**: 505
- **存储**: 最低 100MB
- **内存**: 最低 512MB，推荐 1GB+
- **操作系统**: Linux / Windows / macOS

---

## 💬 联系方式

- 👤 **GitHub**: [@Xieburouzzz](https://github.com/Xieburouzzz)
- 📧 **邮箱**: luxdongzzz@gmail.com

---

## 🌟 特别说明

- 不包含任何源代码文件
- 本仓库仅用于项目展示和文档说明
- 如需了解更多信息，请通过上述联系方式咨询

---

<div align="center">

**Built with ❤️ by Xieburouzzz**

⭐ 如果您对本项目感兴趣，欢迎 Star 本仓库！

</div>

