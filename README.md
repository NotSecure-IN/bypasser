# Bypasser 🔓

**Advanced 403/401 Bypass & WAF Evasion Testing Tool**

![Go Version](https://img.shields.io/badge/Go-1.21+-00ADD8?logo=go)
![License](https://img.shields.io/badge/License-Commercial-red)
![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20macOS%20%7C%20Windows-blue%20%7C%20Android)

## 📖 Overview

Bypasser is a professional security testing tool designed for identifying and exploiting 403 Forbidden and 401 Unauthorized bypass vulnerabilities. Unlike simple fuzzers, Bypasser systematically tests **800+ technique combinations** across multiple attack vectors to uncover authorization weaknesses that manual testing often misses.

**Built for:** Penetration testers, bug bounty hunters, security researchers, and red teams.

## ✨ Features

### 🎯 Comprehensive Testing Suite
- **Multi-Vector Attacks**: Simultaneous testing of path, header, protocol, and method manipulation
- **800+ Technique Combinations**: From basic bypasses to advanced encoded attacks
- **Intelligent Organization**: Prioritizes high-success techniques with logical execution order

### 🔧 Technical Capabilities
- **Path Manipulation**: 150+ encoded traversal techniques (`..%2f`, `%2e%2e`, `..;`, etc.)
- **Header Injection**: 400+ WAF-evasion headers with smart combinations
- **Protocol Testing**: HTTP/0.9 through HTTP/3 compatibility checks
- **Method Fuzzing**: 100+ HTTP method variations
- **Extension Injection**: File extension manipulation attacks
- **Content-Length Variations**: Bypass size validation controls

### ⚡ Performance Features
- **Concurrent Execution**: Multi-threaded scanning with configurable workers
- **Rate Limiting**: Adaptive throttling to avoid WAF detection
- **Batch Processing**: Efficient handling of thousands of URLs
- **Proxy Support**: Integration with Burp Suite and other proxies
- **Detailed Reporting**: Curl commands for every successful bypass

## 🚀 Quick Start

### Installation

#### Method 1: Download Binary
```bash
# Download latest release
wget https://product.notsecure.in/downloads/bypasser-latest
chmod +x bypasser-latest
sudo mv bypasser-latest /usr/local/bin/bypasser
```
