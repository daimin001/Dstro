# HyperSmart - Hyperliquid到Bybit等交易所跟单系统

<div align="center">

![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)
![Docker](https://img.shields.io/badge/docker-ready-brightgreen.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

**专业的 Hyperliquid 到 Bybit 等交易所跟单系统**

订阅 Hyperliquid 聪明钱地址交易信号，实时自动复制交易到 Bybit、Bitget、OKX、Binance、gate

[快速开始](#快速安装) | [功能特性](#功能特性) | [系统要求](#系统要求) | [文档](#使用文档)

</div>

---

## 🚀 快速安装

一键安装命令（推荐）：

```bash
curl -L https://raw.githubusercontent.com/daimin001/HyperSmart/main/install.sh | sudo bash
```

## ✨ 功能特性

- ✅ **实时跟单** - Hyperliquid 到 Bybit 实时同步交易
- ✅ **多账户管理** - 支持最多 6 个账户同时运行
- ✅ **Web 管理界面** - 现代化的 Web UI，轻松管理
- ✅ **持仓复制** - 一键复制 Hyperliquid 持仓到 Bybit
- ✅ **白名单控制** - 支持交易对白名单过滤
- ✅ **账户限制** - 智能账户数量限制（最多6个）
- ✅ **安全认证** - 完整的认证系统（bcrypt + TOTP）
- ✅ **数据持久化** - SQLite 数据库，数据安全可靠
- ✅ **Docker 部署** - 一键部署，开箱即用
- ✅ **自动更新** - 内置版本检查和自动更新机制
- ✅ **后续多交易所支持** - Bybit、Bitget、OKX、Binance

## 📋 系统要求

### 最低配置
- **操作系统**: Ubuntu 20.04+ / Debian 10+ / CentOS 7+
- **CPU**: 1核
- **内存**: 2GB RAM
- **磁盘**: 10GB 可用空间
- **Docker**: 20.10+ (安装脚本会自动安装)

## 📦 安装后

安装完成后，系统会自动启动并运行在：

```
http://你的服务器IP:8080
```


## 🎯 使用文档

### 首次登录

1. 访问 `http://你的服务器IP:8080`
2. 首次访问会引导你注册管理员账号
3. 设置 TOTP 双因素认证（推荐使用 Google Authenticator）
4. 登录后即可开始配置账户

### 添加交易账户

1. 登录管理界面
2. 点击"添加账户"
3. 填写配置信息：
   - 账户名称
   - Hyperliquid 地址
   - Bybit API Key 和 Secret
   - 选择模式（实盘/模拟盘）
4. 保存并启动


---

<div align="center">

**⭐ 如果这个项目对你有帮助，请给个 Star ⭐**

Made with ❤️ by HyperSmart Team

</div>
