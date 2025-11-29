## 🛍️ Challenge 1: The "Black Friday" Crash

### 📖 The Story
You pitch a dashboard to the CEO of a massive failing retail chain. He smirks, *"We have millions of transactions. You think your little laptop can handle our scale?"* He refuses to give you database access but says: *"If you can tell me which product category is bleeding money due to returns by tomorrow morning, I'll hire you."*

### 🎯 The Mission
Analyze your mock data to answer:
- [ ] Which **Product Category** generated the highest total Revenue?
- [ ] Which specific **Item** has the highest "Return Rate"?
- [ ] What is the average transaction value for customers in **"New York"**?
- [ ] How many **"High Value" customers** (spent over $500 in one transaction) do we have?

### 💾 Data Generation Prompt
*Copy and paste this into an AI to generate your CSV:*
> "Generate a CSV dataset with 1,000 rows representing retail transactions. The columns should be: `Transaction_ID` (unique), `Customer_Name`, `Location` (City), `Product_Category` (Electronics, Clothing, Home, Beauty), `Item_Name`, `Price` (between 10 and 1000), `Quantity` (1 to 5), and `Returned` (Yes/No - make 'No' 80% likely). Ensure there are meaningful patterns."