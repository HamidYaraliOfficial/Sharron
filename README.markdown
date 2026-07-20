# 🚀 Sharron

Sharron is an experimental, local-first, peer-to-peer (P2P) file synchronization engine built entirely from scratch in Python. It enables secure device discovery, encrypted communication, and automatic directory synchronization across a local network without relying on any centralized server.

> ⚠️ Disclaimer: This project is an ongoing experimental MVP intended for educational and research purposes only.

---

# 🇺🇸 English

## ✨ Features
- Fully decentralized P2P architecture
- Encrypted UDP-based peer discovery
- Secure TCP handshake with challenge-response authentication
- Real-time filesystem monitoring using watchdog
- Automatic file synchronization across nodes
- Self-healing transfer recovery system

## 🛠 Installation

### 1. Install Python dependencies
```bash
pip install watchdog cryptography asyncio
```

### 2. Run the node
```bash
python main.py
```

## ⚙ Requirements
- Python 3.9+
- Local network (LAN/WiFi)
- Administrative permission (recommended for file watching)

---

# 🇮🇷 فارسی

## ✨ ویژگی‌ها
- معماری کاملاً غیرمتمرکز P2P
- کشف همتاها با استفاده از UDP رمزنگاری‌شده
- احراز هویت امن با چالش-پاسخ (Handshake)
- مانیتورینگ لحظه‌ای فایل‌ها
- همگام‌سازی خودکار بین نودها
- سیستم بازیابی هوشمند انتقال فایل

## 🛠 نصب

### 1. نصب وابستگی‌ها
```bash
pip install watchdog cryptography asyncio
```

### 2. اجرای برنامه
```bash
python main.py
```

## ⚙ نیازمندی‌ها
- Python نسخه 3.9 یا بالاتر
- شبکه محلی (LAN / WiFi)
- دسترسی مدیریتی برای مانیتورینگ فایل‌ها

---

# 🇨🇳 中文

## ✨ 功能
- 完全去中心化 P2P 架构
- 基于加密 UDP 的节点发现
- 安全 TCP 挑战-响应认证机制
- 实时文件系统监控
- 节点间自动同步文件
- 断点恢复与自愈传输系统

## 🛠 安装

### 1. 安装依赖
```bash
pip install watchdog cryptography asyncio
```

### 2. 运行节点
```bash
python main.py
```

## ⚙ 要求
- Python 3.9 或以上版本
- 局域网环境 (LAN/WiFi)
- 文件监控权限（推荐管理员权限）

---

# 📌 Notes
- Do NOT use this system for production-critical data.
- Designed for experimentation, learning, and local network research.
