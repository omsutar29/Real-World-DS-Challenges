## 📉 Challenge 5: The Silicon Valley Layoff

### 📖 The Story
A ruthless Private Equity firm has acquired your tech company. The new board wants to cut costs by 20%. They hand you a chaotic spreadsheet of employee data and say, *"We want to keep the high performers and correct our salary bands. Give us a list of who is overpaid and underperforming by noon."*

### 🎯 The Mission
Analyze the employee data to answer:
- [ ] Identify the **Department** with the highest average Salary.
- [ ] Find employees with a **Performance Score** below 3 but a **Salary** above the department average (The "Overpaid" group).
- [ ] What is the average tenure (Years at Company) for employees with a Performance Score of 8 or higher?
- [ ] Visualize (or calculate) the salary distribution between "Remote" vs. "On-site" employees.

### 💾 Data Generation Prompt
*Copy and paste this into an AI to generate your CSV:*
> "Generate an HR dataset with 500 rows. Columns: `Employee_ID`, `Department` (Engineering, Sales, HR, Marketing), `Role_Level` (Junior, Senior, Lead, VP), `Salary` ($40k to $250k), `Years_At_Company` (1 to 15), `Performance_Score` (1 to 10), `Work_Mode` (Remote, On-site, Hybrid), and `Last_Promotion_Year`. Ensure 'VP' roles have significantly higher salaries."