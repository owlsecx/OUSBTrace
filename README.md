# 🦉 OUSBTrace

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OForensics-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0-cyan?style=flat-square"/>
</p>

> **OUSBTrace** — USB Forensic Trace Analyzer ║

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OUSBTrace is a USB device forensics and monitoring tool that enumerates connected USB devices and tracks connection and disconnection events over time. It reads device identifiers, vendor/product data and timestamps to build an audit trail. It runs as a desktop application for authorized endpoint-forensics work.

---

## ✨ Features


- Enumeration of connected USB devices with vendor/product identifiers
- Real-time tracking of connect and disconnect events
- Timestamped audit trail of device history
- Device metadata inspection (serial, class, mount points where available)
- Export of the device log for forensic reporting
- Desktop UI in the OWLSec theme with an offline --self-test

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OUSBTrace
./OUSBTrace --self-test
./OUSBTrace --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
