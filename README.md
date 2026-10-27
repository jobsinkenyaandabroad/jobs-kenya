# 🇰🇪 KaziKenya & Abroad – Official Recruitment & CV Portal

A high-converting, mobile-first recruitment marketplace and ATS CV revamp portal built for our **13,000+ Facebook Community**. Hosted 100% free on **GitHub Pages** with zero backend infrastructure requirements.

---

## 📌 Project Overview

This portal serves two primary audiences:
1. **Job Seekers:** Candidates register their profile for 6 months to be visible to verified Kenyan and Gulf/Diaspora recruitment agencies, with an optional upsell for professional ATS CV revamps.
2. **Employers & Agencies:** Recruiters filter pre-screened talent across security, logistics, hospitality, healthcare, and general labor, purchasing unlock passes for direct contacts.

---

## 💰 Monetization & Service Pricing

| Service | Price | Description |
| :--- | :--- | :--- |
| **Candidate Profile Registration** | **KES 199** | 6-month active placement in verified agency directory |
| **Professional ATS CV Revamp** | **KES 300** | Gulf & Diaspora standard CV delivery within 24–48 hours |
| **Registration + CV Bundle** | **KES 499** | Complete package: 6-month listing + full CV revamp |
| **Employer Candidate Access Pass** | **KES 1,000** | Unlock 20 verified candidate phone numbers & full CVs |

---

## 📞 Official Contacts & Payment Routing

To ensure security and organized customer support, the platform strictly separates money collection from help desk communications:

* **Official M-Pesa Payment Line:** `+254 708 743 931` (0708 743 931)
  * *Used exclusively for receiving candidate fees, revamp orders, and agency passes.*
* **Official WhatsApp Help Desk:** `+254 739 658 520` (0739 658 520)
  * *Used for receiving M-Pesa confirmation codes, customer inquiries, and delivering revamped CV documents.*

---

## 🚀 How to Deploy on GitHub Pages (Step-by-Step)

1. **Create Repository:**
   * Create a new repository on [GitHub](https://github.com) named `jobs-kenya` (or your preferred name).
   * Ensure repository visibility is set to **Public** (required for free GitHub Pages).
2. **Add Website Files:**
   * Upload `index.html` (the portal source code).
   * Upload `README.md` (this documentation file).
   * Click **Commit changes**.
3. **Activate Pages:**
   * Go to **Settings > Pages** in your repository.
   * Under **Build and deployment > Source**, select **Deploy from a branch**.
   * Under **Branch**, select `main` (or `master`) and folder `/(root)`.
   * Click **Save**.
4. **Go Live:**
   * Your site will be accessible within 1–2 minutes at:  
     `https://<your-github-username>.github.io/<repository-name>/`

---

## 🔐 Administrative Dashboard Access

The website includes a lightweight, built-in administrative management dashboard embedded directly inside `index.html`.

* **Access Point:** Click the **Admin** link in the top header or bottom website footer.
* **Default Security PIN:** `7439`
* **Admin Features:**
  * View total incoming candidate leads.
  * Real-time revenue tracking based on verified payments.
  * Filter candidates by status (Paid vs. Payment Pending vs. CV Revamps).
  * 1-click candidate WhatsApp engagement.
  * **Export to CSV:** Download all candidate data (names, phone numbers, trade, passport status, M-Pesa receipts) for import into Microsoft Excel or Google Sheets.

> **Security Note:** To change the default admin PIN, open `index.html` and edit the variable:
> ```javascript
> const ADMIN_PASSCODE = "7439"; // Replace with your desired 4-digit PIN
> ```

---

## 🛠️ Technology Stack

* **Frontend:** HTML5, CSS3, JavaScript (Vanilla ES6+)
* **Styling:** [Tailwind CSS CDN](https://tailwindcss.com/)
* **Icons:** [Font Awesome 6](https://fontawesome.com/)
* **Hosting:** [GitHub Pages](https://pages.github.com/) (100% Free, Automated SSL/HTTPS)
* **Lead Storage:** Client-side `localStorage` with CSV export utility
* **Integrations:** Direct WhatsApp Click-to-Chat API & M-Pesa manual/assisted flow

---

## 📄 License & Community Usage

Designed and deployed for the **Jobs in Kenya and Abroad** community. All rights reserved.
