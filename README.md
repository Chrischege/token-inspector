# token-inspector
Decode tokenized URLs 

# 🔍 Tokenized URL Analyzer

## 📌 Project Overview
Tokenized URL Analyzer is a tool designed to **capture, analyze, and decode tokenized URLs** from network traffic. It integrates **Wireshark (TShark) with Python** to automate packet analysis and extract meaningful insights from HTTP requests containing authentication tokens.

## 🚀 Features
- **Live packet capture** using Wireshark/TShark
- **Extract and decode Base64, JWT, and other tokenized URLs**
- **Analyze HTTP traffic for authentication tokens**
- **Detect redirections and expired token patterns**
- **Logging and reporting for security research**

## 🛠️ Tech Stack
- **Python** (Automation, data extraction, decoding)
- **Wireshark & TShark** (Packet capture and network analysis)
- **PyShark** (Python wrapper for TShark)
- **Requests** (For making and analyzing HTTP requests)
- **Scapy** (Optional for deeper packet manipulation)
- **Will change or grow as need arises

## 📂 Installation & Setup
### 1️⃣ Install Wireshark & TShark
- Download Wireshark: [Wireshark Official Site](https://www.wireshark.org/download.html)
- Ensure `tshark` is accessible in your terminal:
  ```bash
  tshark --version
  ```

### 2️⃣ Install Python Dependencies
```bash
pip install pyshark requests scapy
```

### 3️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/tokenized-url-analyzer.git
cd tokenized-url-analyzer
```

## 🔎 Usage
### **Capture Live Network Traffic**
```bash
python capture_packets.py
```

### **Analyze a Saved PCAP File**
```bash
python analyze_pcap.py network_traffic.pcap
```

### **Decode a Token Manually**
```bash
python decode_token.py 'dGVzdF9zdHJpbmc='
```

## 📌 Roadmap
- [ ] Improve token decoding (support for more encoding formats)
- [ ] Implement GUI for better visualization
- [ ] Detect anomalies in tokenized URLs (expired, modified, etc.)

## 🤝 Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature-new`)
3. Commit changes (`git commit -m "Add new feature"`)
4. Push to the branch (`git push origin feature-new`)
5. Open a pull request 🚀

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🛠️ Author
**Your Name**  
📧 your.email@example.com  
🐙 [GitHub Profile](https://github.com/your-username)
