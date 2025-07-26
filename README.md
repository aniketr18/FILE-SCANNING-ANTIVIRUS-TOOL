# FILE-SCANNING-ANTIVIRUS-TOOL

This is a GUI-based antivirus scanning application built with **Python** and **PyQt5** that allows users to scan files for malware using **SHA256 hashing**, **VirusTotal**, and **MetaDefender APIs**. It detects known threats through signature-based detection and external API integration, offering an effective and user-friendly experience.

---

## 📌 Key Features

- 🔍 **File Scanning via SHA256**: Compares file hashes with known virus signature packs.
- 🧪 **VirusTotal & MetaDefender Integration**: API-based malware analysis for deeper verification.
- 💻 **Cross-Platform GUI**: Built with PyQt5 for smooth and responsive user interaction.
- ☁️ **Cloud-Assisted Detection**: Supports scanning files under 32MB (VirusTotal) and 120MB (MetaDefender).
- ⚙️ **User Settings Panel**: Save and manage API keys and switch between Dark/Light mode.
- 🗃️ **Local Signature Packs**: Multiple hard signature files for offline/fast scanning.

---

## 🧠 How It Works

1. **File Selection**: User selects a file to scan using the GUI.
2. **SHA256 Calculation**: File hash is computed and compared against hard signature packs.
3. **Cloud API Scan** *(Optional)*: If enabled and API key is provided, the file is scanned through VirusTotal and MetaDefender.
4. **Result Display**: Shows detection stats, scan result (Virus/Clean), and allows file deletion.
5. **Settings**: API keys and theme preferences are saved in `settings/settings.ini`.
