## 💸 Challenge 3: The Fintech "Shark Tank"

### 📖 The Story
You are in front of a panel of investors. You claim you can automate loan approvals. The lead shark says, *"I don't trust algorithms. They don't understand human risk."* She challenges you: *"Here are the parameters. Tell me which profession is the safest bet for lending money."*

### 🎯 The Mission
Analyze your mock data to answer:
- [ ] What is the average **Credit Score** of people who "Defaulted" vs. those who didn't?
- [ ] Which **Profession** has the lowest Default rate?
- [ ] Is there a correlation between **"Annual Income"** and **"Loan Amount"**?
- [ ] Bin the Credit Scores into categories (Poor, Average, Good, Excellent). How many people are in each?

### 💾 Data Generation Prompt
*Copy and paste this into an AI to generate your CSV:*
> "Create a loan application dataset with 1,000 rows. Columns: `Applicant_ID`, `Age`, `Profession` (Engineer, Doctor, Artist, Teacher, Lawyer), `Annual_Income` ($30k to $200k), `Credit_Score` (300 to 850), `Loan_Amount` ($5k to $50k), and `Loan_Status` (Paid, Default). Correlate higher Credit Scores with 'Paid' status."