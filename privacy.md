# Privacy Policy for FormulaFix AI

**Effective Date:** October 14, 2026

FormulaFix AI ("the Application", "we", "our") is an add-on designed for Google Sheets™. We are committed to maintaining the confidentiality and integrity of your data. This Privacy Policy details our practices regarding data access, usage, and protection.

---

## 1. Zero Data Retention & Sales
FormulaFix AI does **not** sell, rent, monetize, or log your personal data or spreadsheet contents. We do not maintain user tracking databases, persistent storage, or analytics profiles.

---

## 2. Information Accessed & Scopes
FormulaFix AI requests only the minimal necessary OAuth permissions required for core functionality:

* **Scope (`https://www.googleapis.com/auth/spreadsheets.currentonly` or `spreadsheets`):**
  * **Access:** Reads the active cell value or formula selected by the user to analyze errors or generate requested calculations.
  * **Action:** Writes the corrected formula back to the spreadsheet upon user confirmation.
* **Scope (`https://www.googleapis.com/auth/script.container.ui`):**
  * Displays the user interface sidebar inside the active spreadsheet container.

---

## 3. Data Processing & Third-Party Processors
* When you request a formula repair or generation, the relevant formula or text prompt is transmitted via an encrypted HTTPS connection to the official Google Gemini API (`generativelanguage.googleapis.com`) to generate the formula response.
* Spreadsheet contents are never used to train third-party foundation models.
* No intermediate proxy servers, private databases, or external logging systems are used.

---

## 4. Google API Services User Data Policy
FormulaFix AI's use and transfer of information received from Google APIs adhere strictly to the **Google API Services User Data Policy**, including the **Limited Use** requirements.

---

## 5. Security
All communication between your browser, the Google Sheets™ environment, and the underlying AI service is strictly encrypted in transit using industry-standard TLS (HTTPS).

---

## 6. User Rights & Data Deletion
Because FormulaFix AI does not retain user data on external servers, there is no persistent personal data stored to view, modify, or delete. You can revoke access at any time via your [Google Account Permissions](https://myaccount.google.com/permissions).

---

## 7. Contact & Support
For inquiries, bug reports, or feedback regarding this Privacy Policy, please open an issue or comment on the official project support page.

---
Google Sheets™ and Google Workspace™ are trademarks of Google LLC.
