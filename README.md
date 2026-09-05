# HR Analytics Dashboard - Full Insight

An interactive, multi-page Power BI dashboard designed to provide workforce analytics, track key HR metrics, manage employee action lists (promotions, retrenchments, and severance), and evaluate job satisfaction and compensation across departments.

---

## Executive Summary

| Category | Value |
| --- | --- |
| **Total Headcount** | 1,470 |
| **Gender Breakdown** | Male: 882 (60%) | Female: 588 (40%) |
| **Active Workforce (On Service)** | 1,353 (92%) |
| **Promotions Due** | 72 (4.9%) |
| **Retrenchments (Lay-offs)** | 117 (8.0%) |
| **Total Attritions** | 237 (16.1%) |
| **Total Monthly Income** | $9,559K |
| **Average Monthly Income** | $6,503 |

---

## Dashboard Structure

The report is divided into three functional viewable pages accessible via the custom sidebar navigation menu:

### 1. Home Page (`Home.png`)

Provides a high-level overview of demographics, tenure distribution, and organizational structure.

* **Top KPIs:** Total Employees, Gender Split, Active Status, Promotions, Retrenchment, and Attrition Rates.
* **Service Tenure Distribution:** Visualizes employee counts by service years (e.g., 5 years: 196, 1 year: 171, 3 years: 128).
* **Job Level Breakdown:** Tracks headcount distribution across Levels 1 through 5 (Level 1: 543, Level 2: 534, Level 3: 218, Level 4: 106, Level 5: 69).
* **Educational Background:** Displays workforce numbers across fields like Life Sciences (606), Medical (464), Marketing (159), Technical Degree (132), and others.
* **Commute Distance Status:** Categorizes employees by proximity—Near (63.95%), Far (20.48%), and Very Far (15.58%).

### 2. Action Page (`Action.png`)

Provides operational lists to support HR personnel decisions and administrative execution.

* **Promotion Due List:** Detailed list of specific employees eligible for promotion status.
* **Retrenchment List:** Specific list of employees identified for lay-offs.
* **Severance List:** Actionable list detailing employees eligible for severance payouts.

### 3. Details Page (`Details.png`)

Offers deep-dive granular analytics combining financial data, satisfaction metrics, and department breakdowns.

* **Department Performance:** Side-by-side comparison of promotions vs. retrenchments across Research & Development, Sales, and Human Resources.
* **Job Satisfaction Levels:** Segments staff responses across Very High (459), High (442), Very Low (289), and Low (280).
* **Overtime Breakdown:** Tracks proportion of workforce working overtime (Yes: 28.3% / 416 employees vs. No: 71.7% / 1,054 employees).
* **Compensation Metrics:** Visualizes Total Monthly Income ($9,559K) and Average Monthly Income ($6,503).
* **Role Summary Matrix:** Full breakdown by Job Role (e.g., Healthcare Representative, Research Scientist, Sales Executive) summarizing total employees, promotions, retrenchments, severance counts, and attritions.

---

## Project Setup & Usage

1. **Prerequisites:** Install the latest version of [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. **Opening the Dashboard:**
* Clone this repository:
```bash
git clone https://github.com/HamadaX98/HR-Dashboard-Analysis.git

```


* Open the `.pbix` file in Power BI Desktop.


3. **Interactivity:** Use the **Navigation** buttons (`Home`, `Action`, `Details`) on the left bar to jump between pages. Filter visuals dynamically by clicking individual bar charts, pie slices, or table entries.
