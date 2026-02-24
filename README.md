# 🛠️ IT Ops Central

**A suite of lightweight, web-based tools designed to streamline IT procurement, onboarding, and offboarding workflows.**

This toolkit was developed to solve common administrative bottlenecks in IT departments. Originally created to automate manual documentation during my professional tenure, these tools replace messy spreadsheets and paper forms with clean, standardized, and professional PDF reports.

---

## 1. 📊 IT Vendor Price Comparison System

A professional utility to evaluate vendor quotations and generate comparison reports for management approval.

### ✨ Key Features

* **Dynamic Entry:** Add unlimited vendor entries for a single item.
* **Smart Calculation:** Real-time auto-calculation of (Price × Quantity).
* **Best-Value Detection:** Automatically highlights the lowest price to assist decision-making.
* **Standardization:** Automatically converts vendor names to uppercase for clean reporting.
* **Instant PDF:** Generates a structured procurement report ready for senior management.

---

## 2. 📤 IT Offboarding Checklist (Resigned Staff)

A standardized system to ensure all hardware is recovered and digital accounts are secured when an employee leaves.

### ✨ Key Features

* **Comprehensive Tracking:** Covers hardware handover, backups, and system deactivation.
* **Asset Management:** Includes dedicated fields for Asset IDs and device condition remarks.
* **Live Preview:** Real-time A4 layout preview before exporting.
* **Professional Records:** Exports a "tick-enabled" PDF with red checkmarks (✓) for audit trails.

---

## 3. 📥 IT Onboarding Checklist (New Staff)

A procedural tool to ensure every new hire receives the correct hardware, accounts, and software configurations from Day 1.

### ✨ Key Features

* **Step-by-Step Setup:** Tracks hardware prep, profile configuration, and printer drivers.
* **Software Bundle Tracking:** Specialized checklist for core apps (O365, VPN, Remote Desktop, etc.).
* **Audit-Ready:** Generates a formatted A4 document with revision codes for internal filing.
* **Efficient UI:** Uses TailwindCSS and DaisyUI for a fast, responsive mobile-friendly experience.

---

## 💻 Technical Stack (Shared)

Across all tools, the focus was on **zero-dependency portability** and **speed**:

* **Frontend:** HTML5, Tailwind CSS, DaisyUI (for On/Offboarding).
* **Logic:** Vanilla JavaScript (ES6+).
* **PDF Generation:** `jsPDF` & `jsPDF-AutoTable`.
* **Icons:** Lucide Icons.
* **Deployment:** Fully client-side; can be run locally or hosted via GitHub Pages/Vercel with no database required.

---

## 🚀 Usage & Deployment

### Local Execution

1. Clone the repository: `git clone https://github.com/yourusername/it-toolkit.git`
2. Open the respective `.html` file in any modern web browser.

### Online Deployment

Since these tools require no backend, simply connect your repository to **Vercel**, **Netlify**, or **GitHub Pages** for instant deployment.

---

## 🎯 Project Origin

These tools were independently developed to improve operational efficiency and documentation accuracy within an enterprise IT environment. They serve as a bridge between technical execution and administrative compliance.
