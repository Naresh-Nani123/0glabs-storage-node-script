# 🚀 0G Auto Node Setup Script

Fully automated bash script to **install**, **configure**, **snapshot restore**, and **auto-refresh** the official [0G Storage Node](https://github.com/0glabs/0g-storage-node).

---

## ⚡ Features

- 🔄 Auto backup & restore of `config.toml`
- 🔐 Secure private key input
- 🧊 Snapshot download & restore
- 🛠️ Systemd service creation
- ⏳ Auto-refresh via systemd timer (custom interval)

---

## 📦 One-Line Setup (Recommended)

```bash
bash <(curl -s https://raw.githubusercontent.com/prodipmandal10/oglabs-one-clik/main/oglabs.sh)
```

---

## ✅ Requirements

- Ubuntu 20.04 / 22.04
- sudo access
- Basic terminal knowledge

---

## 🧠 What the Script Does

| Step | Task                                |
|------|-------------------------------------|
| 1️⃣   | Ask refresh interval                |
| 2️⃣   | Backup old `config.toml` if exists |
| 3️⃣   | Install dependencies (Rust, Go)    |
| 4️⃣   | Clone and build 0G node            |
| 5️⃣   | Setup or restore configuration     |
| 6️⃣   | Create systemd service             |
| 7️⃣   | Download & restore snapshot        |
| 8️⃣   | Setup systemd auto-refresh timer   |

---

## 🛡 Security Notice

Your private key is **never transmitted**.  
It's used only locally to configure the node.

---

## 🙋 Made By

Made with ❤️ by Crypto Alerts
Follow us on Twitter for more: https://x.com/CryptoAlertsNH
