# Recon Assistant 🕵️‍♂️

A Python-based reconnaissance tool for ethical hackers and penetration testers.  
It automates information gathering using `nmap` and other tools.

## 🔧 Features
- Nmap scanning (version detection)
- Logs results with timestamps
- User-friendly CLI with `prompt_toolkit` and `rich`

## 📦 Requirements
Install dependencies:

```bash
pip install -r requirements.txt
[Nmap](https://nmap.org/) must be installed and added to system path
```
## 📥 Clone & Run

```bash
git clone https://github.com/yashwanthreddy3x/recon-assistant.git
cd recon-assistant
pip install -r requirements.txt
python recon_assistant.py
```

## **🧰 Tools & Libraries Used**

| Tool/Library     | Purpose                         |
|------------------|----------------------------------|
| `os`             | System operations               |
| `subprocess`     | Running external commands       |
| `datetime`       | Timestamps                      |
| `colorama`       | Colored terminal output         |
| `prompt_toolkit` | Better CLI user experience      |
| `rich`           | Styled and formatted output     |
| `nmap`           | Network scanning tool (external)|


## **📁 File Structure**

recon-assistant/

├── recon_assistant.py    
├── README.md             
├── requirements.txt       
└── .gitignore             

## **🙋‍♂️ Author**
Yashwanth Reddy
Ethical Hacking & Red Teaming Enthusiast
🔗 GitHub Profile

## **📄 License**
This project is licensed under the MIT License. You’re free to use, modify, and share with attribution.

## **💡 Future Ideas**

- WHOIS lookups

- Subdomain enumeration

- DNS record retrieval

- Automation pipeline

**Pull requests and contributions welcome!!**


