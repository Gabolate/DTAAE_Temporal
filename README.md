# 🛡️ DTAAE_Temporal
Disk Trash Avoid Avenue Exp (DTAAE) is a malware made especially for the *Viewer Made Malware* series

---
# 🔥 Main Details
**DTAAE** is a malware developed in C# designed to destroy data while bypassing antivirus defenses.

This is a lightweight, fast, and direct piece of malware with no flashy effects or gimmicks — just pure destructive capability.

> **Tested Platforms:**
> * Windows 7
> *  Windows 10
> *  Compatibility with XP or Windows 11 is unverified, might not work.

## 🧪 Antivirus Tests
**DTAAE** was tested against **14 antivirus** programs, all of which failed to stop it. (Note: Results may vary in the future.)

| **Antivirus Name** | **Virus Won** | **Virus Lost** |  
|---------------------|---------------|----------------|  
| Avast              | ✅            | ❌             |  
| MalwareBytes       | ✅            | ❌             |  
| AVG                | ✅            | ❌             |  
| Nod32              | ✅            | ❌             |  
| Kaspersky          | ✅            | ❌             |  
| Bitdefender        | ✅            | ❌             |  
| Avira              | ✅            | ❌             |  
| TotalAV            | ✅            | ❌             |  
| Panda              | ✅            | ❌             |  
| Emsisoft           | ✅            | ❌             |  
| Windows Defender   | ✅            | ❌             |  
| TrendMicro         | ✅            | ❌             |  
| Norton             | ✅            | ❌             |  
| McAfee             | ✅            | ❌             |  

---

## ⚔️ Attack Explanation  
DTAAE’s attack unfolds in **3 rapid stages**, making it extremely difficult to counter or quarantine once detected:  

### 🌀 Stage 1:  
The malware marks itself a **Critical Process**, making sure that its termination triggers a BSOD (Blue Screen of Death). This mechanism also crashes the system after the destruction is complete.  

### 🚫 Stage 2:  
DTAAE denies access to the **C:** drive for all processes (excluding itself). Since DTAAE doesn’t directly access files and **C:** is merely a partition, this step ensures antivirus tools are crippled.  

### 💥 Stage 3:  
The malware clears the first **5 MB** of the disk, effectively destroying the **MBR (Master Boot Record)** or **GPT (GUID Partition Table)**. In some cases, parts of a partition may also be deleted.
> *Note: This destruction is difficult to recover from, unlike tools like MEMZ that utilize Windows installer ISOs for recovery.*
> *However, there is a concern of GPT Backup Headers which are located at the end of the disk which store the GPT headers as a backup.*

All three stages are executed within seconds, leaving minimal time for counteraction.

---

## 📥 How to Get  

### ⚠️ **WARNING: DTAAE is highly dangerous. For this reason, it will only be distributed to verified creators in the *Viewer Made Malware* series.**
### 📜 Instructions for Verified Creators:  

1. **Download** the ZIP file from this repository.  
2. Extract the ZIP using the key provided via email or Discord by the developer.  
3. A second ZIP file will appear; its password can be found in the comments section of the file under `paasuwoodo`.  
   > *Tip: Use WinRAR to view file comments.*  
4. Extract the final ZIP on a **virtual machine (VM) without internet access** to prevent unintended distribution.  
   - Generally, try to **avoid all public sandboxes** like Any.Run, Intezer Analyzer, or VirusTotal.  
5. Make sure your VM has **.NET Framework 3.5** installed.  
   - *Check this via ‘Turn Windows Features On or Off’ on your VM.*  
6. Before running DTAAE, **create a file named `GabeIsCute.X3` on the C:** drive of your VM.  
   - This prevents accidental execution of the malware.  
7. You're ready! Have fun experimenting responsibly! 😈  

---

## 🚨 Reporting Unauthorized Distribution  
If you find DTAAE being distributed without my permission, please report it immediately via the [Issues](https://github.com/Gabolate/DTAAE_Temporal/issues) page.  

---

Made by **Gabolate (Gabe)** ∑:3 | 2024 - 2026.
