# Project Log – Invoice Extractor Tool

## Project: Invoice Extractor Tool
A drag-and-drop web-based app to extract data from `.txt` invoice files and export to Excel.

---

### [Date: 2025-04-17]

**Commit:** Initial version of invoice extractor  
**Description:**  
Created a web-based drag-and-drop tool using HTML and JavaScript. It extracts Invoice Number, Item, Performance Date, Scan Amount, and Total Invoice Amount from text-based invoice files. Outputs the data to a downloadable Excel file.

---

### [Date: 2025-04-17]

**Commit:** Performance date logic fix  
**Description:**  
Improved performance date extraction by identifying the smallest (earliest) date in the invoice. This ensures accurate capture even when the layout varies.

---

### [Date: 2025-04-17]

**Commit:** Invoice number validation  
**Description:**  
Refined logic to extract the invoice number that begins specifically with "HI" for accuracy.

---

### [Date: 2025-04-18]

**Commit:** Updated README and uploaded to GitHub  
**Description:**  
Created and uploaded a detailed `README.md` file with project overview, usage steps, and licensing. The repo now has clear documentation for users and contributors.

---

### [Date: 2025-04-18]

**Commit:** Fallback item value to "TATES" when NAB item is missing  
**Description:**  
Updated the item extraction logic to check for a line starting with "NAB ". If not found, the item value is now defaulted to `"TATES"` instead of being left blank. This change ensures consistent Excel output even when the expected item format is missing from the invoice text.

---
