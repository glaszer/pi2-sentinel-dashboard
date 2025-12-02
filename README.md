# 🛡️ Pi² Sentinel | Universal Settlement Verifier

![Version](https://img.shields.io/badge/version-v29.0-00f3ff?style=for-the-badge)
![Status](https://img.shields.io/badge/status-STABLE-10b981?style=for-the-badge)
![Network](https://img.shields.io/badge/network-Pi2_Devnet-a855f7?style=for-the-badge)

**A professional-grade diagnostic dashboard designed to audit and benchmark the Pi Squared (Pi2) network's FastSet™ consensus layer in real-time.**

Sentinel acts as a client-side observatory, visualizing the "Proof-of-Proof" lifecycle—from transaction initiation to sub-second finality. It features a fail-safe architecture, deep metrics analysis (Latency, Jitter), and automated reporting.

<img width="1242" height="878" alt="screenshot png" src="https://github.com/user-attachments/assets/64167695-3112-4459-8705-6f29a84dc54f" />

---

## 🚀 How to Run

### Option A: GitHub Pages (Recommended)
No installation required. Simply navigate to the deployed link to start the diagnostic tool:

[👉 **LAUNCH LIVE DASHBOARD**](https://glaszer.github.io/pi2-sentinel-dashboard/)


### Option B: Local Execution
1. Clone this repository.
2. Open `index.html` in any modern web browser (Chrome/Brave/Edge).
3. Ensure you have an active internet connection for Proxy bridging.

---

## ⚡ Key Features

### 🖥️ High-Fidelity UX (Cyberdeck Interface)
*   **Immersive HUD:** A futuristic, responsive interface featuring glassmorphism, animated pipelines, and scanline effects inspired by high-end monitoring tools.
*   **Real-time Visualization:** Dynamic charts rendering execution metrics powered by `Chart.js`.
*   **Multilingual Support:** Instant toggle between English and Russian (EN/RU).

### 🔍 Advanced Network Auditing ("The Analyst" Engine)
*   **Metrics Triangulation:** Measures **Mean Latency** (RTT), **Network Jitter** (stability variance), and **Throughput success rates**.
*   **Intelligent Routing:** Automatically rotates between CORS Proxies (`corsproxy.io`) to bypass browser restrictions.
*   **Fail-Safe Protocol:** If public gateways are throttled, the system seamlessly switches to a mathematically accurate simulation mode to demonstrate UI flows without crashing.

### 📄 Comprehensive Reporting
*   **Auto-Generated Dossiers:** At the end of a session, the system compiles a detailed **Audit Report** analyzing performance grades (S, A, B, C).
*   **Context-Aware Analysis:** The report explains metrics in the context of Pi2's architecture (comparing results against Ethereum and Solana benchmarks).
*   **CSV Export:** One-click data export for community research.

---

## 🧠 Architectural Insights (Why this tool exists)

Pi Squared is not just another blockchain; it is a **Universal Settlement Layer (USL)**. Sentinel helps visualize how Pi2 achieves scalability:

1.  **FastSet Consensus:** By separating transaction ordering from execution, Pi2 achieves theoretical sub-second finality. Sentinel measures this propagation delay.
2.  **Proof-of-Proof:** Instead of re-executing heavy smart contracts, Pi2 verifies a recursive ZK-proof of correctness.
3.  **K-Framework Integrity:** The tool acts as a visual frontend for the formal verification guarantees provided by the underlying K-Framework semantics.

---

## 🔒 Security & Privacy

> [!IMPORTANT]
> **Use strictly for Devnet diagnostics.**

*   **Client-Side Execution:** All logic runs locally. Your private keys **never** leave your device except to sign the specific transaction sent to the RPC endpoint.
*   **Burner Wallet Mandate:** Do not use mainnet keys holding real value. Create a temporary account for testing purposes.
*   **Open Source:** The code is transparent. You can inspect `index.html` to verify there are no hidden backdoors or analytics trackers.

---

## 🏗️ Technical Stack

*   **Core:** Vanilla JavaScript (ES6+) for maximum performance and zero dependencies.
*   **Styling:** TailwindCSS (via CDN) for the utility-first, dark-mode design.
*   **Visuals:** Chart.js for data plotting.
*   **Fonts:** JetBrains Mono & Rajdhani (Google Fonts) for that specialized engineer aesthetic.

---

## 👨‍💻 Contributing

Built for the **Pi Squared Community**.
Feedback and pull requests are welcome to improve the routing logic or add new metrics!

**Created by MicrocutsD**
*Universal Settlement Layer Advocate*
