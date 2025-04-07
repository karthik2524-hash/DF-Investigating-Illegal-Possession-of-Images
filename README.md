# 🕵️‍♂️ DF-Investigating-Illegal-Possession-of-Images

This repository presents a digital forensics case study titled **"Investigating Illegal Possession of Images"**, based on the **DFRWS 2005 RODEO Challenge**. The challenge focuses on uncovering and analyzing hidden or deleted illegal wildlife images from a USB thumb drive. The USB disk image was provided by **NIST**.

---

## 📌 Case Overview

- **Profession**: A post-graduate student in the University of New Orlands   
- **Allegation**: Possession of illegal rhino images  
- **Objective**: Recover deleted/hidden images and investigate file activity on a USB drive

---

## 🧰 Tools Used
- `wireshark` – log analysis 
- `Stegdetect` – Stegnography detection
- `Stegbreak` – brute-force dictionary attack on embedded JPG images
- `Stegseek|jpseek.exe` – DOS program to recover a file hidden with JPHIDE.EXE
- `PhotoRec` – Deleted file recovery (file carving)  
- `ExifTool` – Metadata analysis  
– `ExifTool`Hidden content and embedded file detection
- `dd` – Disk image acquisition
- `Hexeditor` – For reading binary files and displaying the bytes in a hexadecimal format.  
---

## 🔍 Investigation Steps
1. **Rhion_Possession_Case Intro**
   
2. **Downloading the DD file and Recovering Images and any evidence Related**
   
3. **Rhino_Stegnography**
 
4. **Tracing_Logs FTP Traffic**
   
5. **Tracing_Logs HTTP Traffic**
    
6. **Final Conclusion **

## 🖼️ Key Findings

- Illegal rhino images were found in **deleted and disguised file formats**
- EXIF metadata confirmed **timestamps and origin**
- Chat logs and browsing history confirmed **intentional download and possession**

---

## 📁 Case Artifacts

- 📂 Recovered Images  
- 📄 Metadata Reports  
- 🧾 Logs and Timeline Analysis  
- 📑 PDF Case Study Report (attached in this repo)

---

## ✅ Conclusion

The forensic investigation **confirmed illegal image possession** and **attempted concealment** by the suspect. This case demonstrates the power of file carving, metadata analysis, and thorough forensic procedures.

---

## 📎 Reference

- [DFRWS 2005 RODEO Challenge](http://www.dfrws.org/2005/challenge/index.shtml)  
- [NIST - National Institute of Standards and Technology](https://www.nist.gov/)  

---

## 📜 License

This project is for **educational and research purposes only**.

---



