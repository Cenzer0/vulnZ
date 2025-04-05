# 🐉 vulnZ - Cyber Recon & Exploit Scanner

**vulnZ** adalah alat ringan namun sangat bertenaga yang dirancang untuk kebutuhan **ethical hacking**, **penetration testing**, dan **cybersecurity research**. Dibangun untuk berjalan di terminal, vulnZ menggabungkan berbagai fitur canggih untuk pengintaian, pemindaian, dan analisis exploit.

---

## 🚀 **Fitur Utama**

- 🔍 **TCP Port Scanner** (1-100)
- 🎯 **OS Fingerprinting** via TTL
- 📜 **Banner Grabbing** + CVE Lookup
- 🌐 **Subdomain Discovery**
- 📁 **Index of Scanner** (Auto Save)
- 🐉 **Dragon Mode** (Inspirasi Cyber Quotes)
- 💬 **Interactive Shell Mode**
- 🌎 **Domain to IP Resolver**
- 📂 **Directory Finder** (DirBuster-like)

---

## 🧪 **Contoh Penggunaan**

```bash
# Pemindaian dasar
./vulnZ -t example.com

# Dengan OS fingerprint & CVE lookup
./vulnZ -t example.com --os --cve

# Subdomain dan Index Of scan
./vulnZ -t example.com --subs --indexof

# Menampilkan quote dari Dragon Mode
./vulnZ --dragon

# Masuk ke shell interaktif
./vulnZ --shell
```

### ⚙️ **Interactive Shell Commands**

```bash
vulnZ > help

Commands:
  scan -t <target>     → Scan target ports
  os -t <target>       → Fingerprint OS
  cve -b <banner>      → Lookup CVE from banner
  subs -d <domain>     → Subdomain discovery
  indexof -u <url>     → Check for Index Of
  ip -d <domain>       → Resolve domain to IP
  dir -u <url>         → Directory Finder
  quote                → Random hacking quote
  exit                 → Quit shell
```

---

## 💾 **Output & Loot**

- Hasil dari **"Index of"** akan disimpan otomatis ke direktori: `loot/indexof/`
- Fitur tambahan seperti **SQLite** dan **HTML Export** akan hadir di update mendatang.

---

## 🔧 **Instalasi**

### **Persyaratan**:
- Python 3.8+
- Module: `scapy`, `requests`, `dnspython`

### **Setup Cepat**:
```bash
pip install -r requirements.txt
chmod +x vulnZ
./vulnZ -h
```

---

## 👨‍💻 **Author**

- **Nama**: Cenzoo  
- **GitHub**: [Cenzer0](https://github.com/Cenzer0)  
- **Project**: [vulnZ Repository](https://github.com/Cenzer0/vulnZ)

---

## ⚠️ **Disclaimer**

> **This tool is intended for educational and authorized testing purposes only. Unauthorized usage against targets you don't own is illegal.**

---

## 🖤 **Dragon Mode Quotes**

- "The quieter the port... the louder the breach."
- "I scan, therefore I am."
- "Behind every service version... there's a forgotten patch."

---

## ✨ **Contribution**

Kami menyambut kontribusi Anda! Jangan ragu untuk **fork**, melaporkan **issues**, atau mengusulkan ide fitur baru. Mari bersama-sama membuat vulnZ lebih hebat!

