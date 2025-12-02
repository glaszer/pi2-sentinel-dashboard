# 🛡️ Pi² Sentinel | Universal Settlement Monitor

![License](https://img.shields.io/badge/license-MIT-blue) ![Version](https://img.shields.io/badge/version-v29.0-cyan) ![Network](https://img.shields.io/badge/network-Pi2_Devnet-green) ![Tech](https://img.shields.io/badge/tech-HTML5%20%7C%20JS%20%7C%20Web3-purple)

> **The advanced diagnostic instrument for the Pi Squared Universal Settlement Layer.**  
> Visualize **FastSet™** consensus performance, verify **Proof-of-Proof** integrity, and generate professional audit reports.

## Dashboard Preview

<img width="1242" height="878" alt="screenshot png" src="https://github.com/user-attachments/assets/b3879256-0b97-4d82-a23c-5d94f0d679e8" />

## ⚡ What is Sentinel?

Sentinel is a client-side diagnostic tool built for the **Pi Squared community**. It connects to the Devnet to benchmark the efficiency of the **Universal Settlement Layer (USL)**.

Unlike standard explorers, Sentinel provides a "Hacker-style" deep dive into network performance:
*   **Latency & Jitter Analysis:** Measures the real-world stability of the connection.
*   **Pipeline Visualization:** Tracks the transaction lifecycle (Init -> Proxy -> USL Verification -> Finality).
*   **Smart Auditing:** Generates a comprehensive text report comparing Pi2 performance against legacy chains like Ethereum.

---

## 🚀 Key Features (v29.0)

### 🧠 The "Analyst" Engine
- **Automated Reporting:** At the end of a benchmark, the system generates a unique **Audit Dossier**.
- **Grade System:** Automatically grades the network connection (S/A/B/C) based on responsiveness and stability.
- **Fail-Safe Mode:** If public CORS gateways fail (HTTP 429/500), the system seamlessly switches to mathematical simulation mode to ensure the UI never freezes.

### 🌐 Architecture Visualizer
- **Real-Time Pipeline:** Watch your transaction propagate from your local signer, through the gateway tunnel, to the FastSet Consensus layer.
- **Micro-Metrics:** Tracks block production down to the millisecond.

### 🛡️ Security First
- **Client-Side Only:** No backend server. Your keys **never** leave your browser.
- **Memory Execution:** Private keys are processed in RAM and cleared on session termination.
- **Burner Friendly:** Explicit warnings to use Testnet Burner Wallets only.

---

## 🛠️ Installation & Usage

You don't need Node.js or complicated builds. Sentinel is a standalone "Single File App".

### Option A: GitHub Pages (Recommended)
Simply navigate to the deployed link (replace with your repo link):
> **[👉 Launch Live Dashboard](https://glaszer.github.io/pi2-sentinel-dashboard/)**

### Option B: Local Execution
1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/pi2-sentinel.git
   cd pi2-sentinel

## Run:

Simply open index.html in your browser.
(Note: For best performance, use VS Code "Live Server" extension to avoid local file CORS restrictions).

📖 How to Run a Benchmark

Get Credentials: Create a Burner Wallet (Testnet Only). Do not use your main funds.

Initialize: Enter your set1... address and Private Key. Click Init Session.

Engage: Click START.

The system will broadcast 20 test transactions.

Watch the Knowledge Feed on the right for educational info about K-Framework and USL.

Review Report: Once finished, the "Audit Report" will slide out.

Export: Click DOWNLOAD DATA to save the logs as a CSV file for proof-of-work.

🏗️ Tech Stack & Architecture

Core: Vanilla JavaScript (ES6+) for maximum compatibility.

UI Framework: TailwindCSS (CDN) for the futuristic HUD aesthetic.

Networking: Smart Proxy Rotation logic to bypass CORS limitations on the Devnet API.

Math: Chart.js for real-time latency visualization.

Understanding the Metrics

Latency: The Round-Trip Time (RTT) including the HTTP Proxy overhead. Direct node connection on Mainnet will be significantly faster (est. <200ms).

Jitter: The variance in latency. High jitter indicates congestion at the public gateway, not the Pi2 chain itself.

⚠️ Disclaimer

This is a community-built tool for educational and testing purposes only.

It is not an official product of Pi Squared Inc.

Never enter private keys for wallets holding real value.

Use on Testnet/Devnet environments only.

Built by Microcutsd for the Pi2 Community.
Verifying the Mathematical Truth, one block at a time.
