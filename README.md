# 🛡️ The SiX | Premium Ontario Tax Hub & Budget Oracle

> **Ontario Shop Tax Oracle // High-Performance PWA & Smart Fiscal Matrix**

Welcome to the official GitHub repository and documentation page for **The SiX**. This state-of-the-art tax and budget calculation web application is tailored specifically for Ontario, Canada, featuring an intelligent tax oracle engine, real-time budgeting, ledger storage with 2-hour leeway cache management, and an immersive dark-mode glassmorphism aesthetic.

🌐 **Live Web Application:** [https://breaultalex44-cmd.github.io/TheSiX/](https://breaultalex44-cmd.github.io/TheSiX/)

---

## 📋 Table of Contents

1. [Overview & Features](https://www.google.com/search?q=%23-key-features--capabilities)
2. [Technical Stack](https://www.google.com/search?q=%23%EF%B8%8F-technical-stack)
3. [Quick Start / Local Deployment](https://www.google.com/search?q=%23-quick-start--local-deployment)
4. [System Manual & Wiki](https://www.google.com/search?q=%23-system-manual--wiki)

---

## 🎯 Key Features & Capabilities

### 🔍 1. The Oracle (Context-Aware Tax Engine)

* **Place-Differentiated Intelligence:** Accurately distinguishes tax rules based on context (e.g., buying a single muffin at a bakery or coffee shop at 13% HST versus buying 6 or more at a supermarket classified as zero-rated basic groceries).
* **Broad Scope Rules:** Instantly evaluates restaurant meals, prepared foods, snack foods, alcohol, electronics, children's goods, books, and medical supplies against CRA and Ontario Point-of-Sale (POS) rebate standards.

### 💰 2. The Vault & Smart Budget Ledger

* **Dynamic Budget Tracking:** Set custom budget cycles with a real-time progress bar that dynamically shifts color to critical red if spending exceeds allocated limits.
* **Itemized Budget Impact:** Every logged entry calculates its exact percentage impact on your overall budget.
* **Accumulated Tax Metrics:** Automatically monitors total tax accrued across your shopping session.

### 🛡️ 3. 2-Hour Leeway Persistence & Cache Management

* **Sliding Session Windows:** Utilizes an automated 2-hour leeway cache window (`CACHE_WINDOW_MS`) via browser `localStorage` to securely store your ledger items and budget parameters while maintaining sliding session integrity.

---

## 🛠️ Technical Stack

| Component | Architecture |
| --- | --- |
| **Frontend** | Vanilla HTML5, ES6+ JavaScript, Responsive CSS3 Grid |
| **Styling & UI** | Cinzel, Inter, Orbitron Fonts, FontAwesome 6, Custom Glassmorphism |
| **State & Storage** | Browser `localStorage` API with timestamped cache control |
| **PWA Readiness** | Embedded Data-URI Web Manifest, Apple Touch Icons, and Startup Loading Screen Matrix |

---

## 🚀 Quick Start / Local Deployment

1. Clone or download the repository to your local machine.
2. Open `index.html` in any modern web browser or host it via GitHub Pages.
3. No build tools, package managers, or server setups required!

```bash
git clone https://github.com/breaultalex44-cmd/TheSiX.git
cd TheSiX
# Open index.html directly in your browser

```

---

## 📖 System Manual & Wiki

### System Architecture

The application runs entirely client-side, ensuring rapid computation and maximum data privacy. Upon launch, an immersive startup loading screen initializes the system matrix before smoothly fading out.

### The Tax Oracle Regex Engine

The oracle uses advanced regex pattern-matching to cross-reference user queries against a comprehensive array of Ontario and Canadian tax guidelines:

* **Bakery Rules:** Automatically evaluates quantities and vendor locations (bakery/cafe vs. grocery store).
* **Restaurant / Fast Food Rebates:** Factors in Ontario point-of-sale rules, such as prepared food items priced at or below $4.00 qualifying for a reduced 5% GST rate instead of the full 13% HST.
* **Zero-Rated Exemptions:** Accurately identifies basic groceries, prescription medications, children's apparel, and books.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
