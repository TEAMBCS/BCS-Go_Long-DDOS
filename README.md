# BCS-Go_Long-DDOS


**BCS-DOS** is a high-performance DDoS (Distributed Denial of Service) flood tool written in **Go (Golang)**.  
Developed for **educational and research** purposes, BCS-DOS demonstrates how network stress testing works at the packet level using Go's concurrency model.

> 🚨 **WARNING:** This tool is for **educational use only**. Do not use it on servers or networks without **explicit authorization**.

---

## 📦 Features

- Multi-threaded / Goroutine-based packet flooding
- POST / GET flood capabilities (customize as needed)
- Simple CLI interface for fast execution
- Fast and lightweight thanks to Go's performance

---

## ⚙️ Requirements

Make sure you have **Go (1.18 or newer)** installed.  
You can download it from: https://golang.org/dl/

---

## 📥 Installation

```bash
git clone https://github.com/JOY-XII/BCS-DOS.git
cd BCS-DOS
chmod +x bcsdos
./bcsdos
```

---

## 🚀 Usage

```bash
./bcsdos <url> <threads> <get/post> <seconds> <header.txt/nil>
```

### Example:

```bash
./bcsdos https://xyz.com 15000 post 60 nil
```

---

## 📚 Flags

| Flag      | Description                  |
|-----------|------------------------------|
| `-target` | Target IP or URL             |
| `-port`   | Port number to attack        |
| `-method` | Type of flood (`get`, `post`) |
| `-threads`| Number of concurrent threads |

---

## 📁 Modules Used

- `net`
- `net/http`
- `time`
- `flag`
- `sync`
- `runtime`

> All modules are part of Go's standard library — no external dependencies required.

---

## ⚠️ Disclaimer

> This tool is **only for educational and authorized testing** purposes.  
> Unauthorized use of BCS-DOS against servers or networks without permission is **illegal** and unethical.  
> The developers are **not responsible** for any misuse or damage caused by this tool.

---

## 👨‍💻 Developer

Made with 💻 by **Bangladesh Cyber Squad**

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
