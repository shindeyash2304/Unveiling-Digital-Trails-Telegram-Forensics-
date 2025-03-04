# Unveiling-Digital-Trails-Telegram-Forensics
**Research & Development Project | Feb 2024 - May 2024**  

## 📌 Overview  
This research project focuses on **Telegram forensics**, identifying gaps in **Linux & macOS data extraction** for forensic investigations. While previous research has successfully extracted Telegram data from **Windows desktop applications**, limited methods exist for other platforms. Our goal is to **develop strategies for extracting Telegram data across multiple operating systems** and enhance digital forensic capabilities.

## 🔬 Research Problem  
Existing studies highlight methods to extract **chat logs, deleted messages, and metadata** from Telegram on **Windows**. However, no concrete techniques were available for **Linux/macOS** environments. This project addresses that gap by:  
- Investigating Telegram's **storage mechanisms** across different OS.  
- Identifying **forensic artifacts** that can be used as **digital evidence**.  
- Implementing and testing **cross-platform extraction strategies**.  

## 🛠 Tools Used  
- **Telepathy** – Extracts Telegram data from memory dumps.  
- **Windows Memory Extractor** – Analyzes volatile memory for forensic artifacts.  
- **Telegram Scraper** – Scrapes chat data, including metadata from Telegram.  
- **ExifTool** – Extracts metadata from exported Telegram JSON files.  

## ⚙️ Methodology  
1. **Literature Review** – Analyzed research papers on Telegram forensics and identified gaps.  
2. **Data Extraction Strategies** – Developed methods to retrieve **deleted messages, chat logs, and media** from Linux/macOS.  
3. **Tool Evaluation & Implementation** – Tested existing forensic tools and modified them for **cross-platform compatibility**.  
4. **Forensic Evidence Collection** – Exported and analyzed Telegram JSON metadata for digital investigation.  

## 📂 Repository Structure  
