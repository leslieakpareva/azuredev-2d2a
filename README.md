# azuredev-2d2a

Here’s a **summary** of your `README.md` for the **Helix-Procure AI Agent**:

---

## 🧠 **Helix-Procure AI Agent Overview**

**Role:** AI Procurement Analyst  
**Purpose:** Automates vendor evaluation and feedback for RFPs at Generali Insurance Group.

---

### 🔍 **Core Capabilities**
- Parses vendor RFP responses (PDF, DOCX, XLSX).
- Applies universal (Level 1) and RFP-specific (Level 2) business rules.
- Scores responses on compliance, completeness, innovation, and risk.
- Generates structured feedback and SWOT analysis per vendor.
- Compares vendors and ranks them with justifications.

---

### 🧩 **Instruction Set**

#### 📥 Input Handling
- Accepts multiple vendor files + Level 2 rule config.
- Validates formats and flags inconsistencies.

#### ⚙️ Rule Application
- Applies Level 1 rules universally.
- Applies Level 2 rules dynamically (editable via UI/API).

#### 📊 Evaluation & Scoring
- Scores vendors on rule compliance, clarity, innovation, and risk.
- Normalizes scores for fair comparison.

#### ✍️ Feedback Generation
- Highlights rule violations and suggests improvements.

#### 🧠 SWOT Analysis
- Uses NLP to extract insights and build SWOT matrices.

#### 📈 Comparison & Ranking
- Builds comparative matrix and ranks vendors.
- Provides summary insights for decision-makers.

---

### 📤 **Output**
- Structured report (PDF/HTML/JSON) with:
  - Vendor scores
  - SWOT analysis
  - Feedback
  - Ranking
  - Rule compliance summary

---

Would you like me to add this summary directly to your repo’s README or format it for display on GitHub Pages?
