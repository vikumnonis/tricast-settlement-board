# 🏇 Tricast Settlement Board

An interactive, browser-based settlement matrix and training board designed for Turf Accountants, betting office staff, and racing analysts to calculate, visualize, and verify Tricast (Trifecta) combinations.

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Try_It_Now-2ea44f?style=for-the-badge)](https://vikumnonis.github.io/tricast-settlement-board/)
[![License](https://img.shields.io/badge/License-Custom_Non--Commercial-blue?style=for-the-badge)](#-license)
[![Platform](https://img.shields.io/badge/Platform-Web_Browser-orange?style=for-the-badge)](#)

---

## 🔗 Try It Live

> **[Open the Tricast Settlement Board](https://vikumnonis.github.io/tricast-settlement-board/)**  
> *No download, installation, or setup required — works directly in any modern web browser.*

---

## 📋 Overview

Settling complex Tricast (Trifecta) combinations manually during peak race times requires precision and speed. The **Tricast Settlement Board** provides a visual interface to break down multi-runner selections, compute permutation counts, and verify returns across straight, combination, and non-runner scenarios. 

Built primarily as an **educational and staff training tool**, it helps users master the underlying mechanics of horse racing bet settlement without risking live ledger errors.

---

## ✨ Key Features

- **Interactive Combination Matrix:** Instantly generate all valid 1st-2nd-3rd permutations from selected runner numbers.
- **Non-Runner Handling:** Observe how non-runners affect total combination counts and roll over according to standard rulebook procedures.
- **Live Settlement Verification:** Enter returns, stakes, and dividend values to instantly audit total payout breakdowns.
- **Training-Focused UI:** Clean visual board designed for rapid practice, operational onboarding, and counter-staff references.
- **Zero Dependencies:** Pure lightweight client-side application — fully functional offline once loaded.

---

## 🛠️ Usage & Workflow

1. **Launch the App:** Open the [live link](https://vikumnonis.github.io/tricast-settlement-board/) in Chrome, Firefox, Safari, or Edge.
2. **Select Runners:** Choose your 1st, 2nd, and 3rd place selections (or combination sets).
3. **Set Stake & Dividends:** Enter the unit stake and declared official Tricast dividend rate.
4. **View Breakdown:** Review the calculated total lines, winning permutations, total return, and net profit/loss.

---

## 💻 Local Development / Self-Hosting

Since the application runs entirely in the browser, you can host or run it locally with no server runtime needed:

```bash
# Clone the repository
git clone [https://github.com/vikumnonis/tricast-settlement-board.git](https://github.com/vikumnonis/tricast-settlement-board.git)

# Navigate into the project directory
cd tricast-settlement-board

# Open index.html directly in your default browser
# (On macOS)
open index.html

# (On Linux)
xdg-open index.html

# (On Windows)
start index.html
