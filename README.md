# AI-Powered Security Analysis Tool

> Automated vulnerability exploitation and remediation using Google Gemini AI for the AIxCC Challenge

## 🚀 Quick Start

```bash
# Clone and run
python3 u335008079_hw1.py
```

## 📋 What it does

- **🔍 Exploit Generation**: Creates files that trigger security vulnerabilities
- **🛠️ Patch Creation**: Generates fixes for identified vulnerabilities  
- **✅ Validation**: Tests both exploits and remediation effectiveness
- **💰 Cost Tracking**: Monitors API usage and costs

## 🏗️ Architecture

```
SecurityAnalysisEngine
├── AI Integration (Gemini 1.5 Pro)
├── Workspace Management
├── Two-Phase Analysis
│   ├── Exploit Generation
│   └── Patch Creation
└── Comprehensive Testing
```

## 📁 Output Files

- `x.bin` - Exploit file (PNG format)
- `x.diff` - Patch file (unified diff)
- Test logs and AI responses

## ⚙️ Requirements

- Python 3.6+
- Google Gemini API key
- Unix-like environment
- Standard build tools

## 🔧 Configuration

```python
# Set your API key
api_key = "YOUR_GEMINI_API_KEY"
```

## ✨ Features

- ✅ Intelligent retry logic with error context
- ✅ Real-time cost monitoring
- ✅ Comprehensive logging
- ✅ Functional test validation
- ✅ Sandboxed code execution

## 🧪 Testing

The tool automatically:
1. Generates exploit files
2. Tests crash conditions
3. Creates remediation patches
4. Validates patch effectiveness
5. Runs functional tests

## 📈 Sample Output

```
🎉 ALL TESTS PASSED! Security analysis completed successfully.
⏱️  Total execution time: 245.67 seconds
💰 Total API cost: $0.0234
📞 Total API requests: 3
```

## ⚠️ Security Notice

This tool is designed for educational and research purposes in controlled environments. Follow responsible disclosure practices.

## 📄 License

Educational/Research use only - AIxCC Challenge submission

---

*Demonstrates AI-powered cybersecurity automation with intelligent exploit generation and remediation capabilities.*
