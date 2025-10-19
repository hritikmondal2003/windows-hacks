# ⚡ Windows Hacks & Power Commands

A clean collection of practical Windows tricks and commands you can use right from **Terminal (Admin)**.
These are safe, quick, and perfect for troubleshooting or learning hidden system tools.

---

## 🔋 Generate a Battery Report

```bash
powercfg /batteryreport
```

➡️ After running, copy the file path (like `C:\Users\<YourName>\battery-report.html`)
Paste it into your browser to view battery health, usage history, and capacity.

---

## 🧾 View Complete System Info

```bash
systeminfo
```

Shows your OS version, BIOS, memory, and updates — helpful for diagnostics.

---

## 🌐 Network Fix Commands

**View IP details:**

```bash
ipconfig /all
```

**Reset network (fixes connection drops):**

```bash
ipconfig /release
ipconfig /renew
```

---

## 🛠 Fix System Files

**Scan and repair corrupted files:**

```bash
sfc /scannow
```

**If that fails, restore the Windows image:**

```bash
DISM /Online /Cleanup-Image /RestoreHealth
```

---

## 💾 Check Disk Health

```bash
chkdsk C: /f /r
```

Scans and fixes file system or bad sector issues (may require a reboot).

---

## 🧩 Enable “God Mode”

Create a new folder on your desktop and name it:

```
GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}
```

It turns into a control panel hub showing every Windows setting in one place.

---

## 📋 Clipboard History

Press **Win + V** → Enable clipboard history.
You can now paste from your clipboard history anytime.

---

## ⚙️ Manage Startup Programs

Press **Ctrl + Shift + Esc** → Open **Task Manager** → Go to **Startup Apps** tab.
Disable unnecessary apps to improve boot time.

---

## 🧰 Mount ISO Files

Right-click → **Mount**, or use:

```bash
Mount-DiskImage -ImagePath "C:\path\to\file.iso"
```

---

## 🐧 Install WSL (Windows Subsystem for Linux)

```bash
wsl --install
```

Reboot when asked. After installation, you can open Ubuntu or any distro from the Start menu.

---

## 🧠 Bonus Tips

* Always open **Terminal (Admin)** for system commands.
* Use `Win + Shift + S` for quick screenshots.
* Save important reports (like battery or system info) in a dedicated folder.

---

### 🧭 Author

**Windows Hacks by [YourName]**
A curated list of small but powerful Windows commands.

> 💬 Feel free to fork this repo and add your own favorite shortcuts!
