## 🍕 Challenge 4: The "30-Minutes or Free" Crisis

### 📖 The Story
You are consulting for a food delivery startup that is bleeding cash because of their "30 minutes or it's free" promise. The Operations Director screams, *"Our drivers are fast, it's the traffic!"* He gives you one day to prove him wrong or right. If you can pinpoint exactly **where** and **why** delays happen, the contract is yours.

### 🎯 The Mission
Analyze your mock delivery data to answer:
- [ ] What is the average **Delivery Time** for "Bike" vs. "Scooter"?
- [ ] Which **City Zone** has the highest delay rate (deliveries > 30 mins)?
- [ ] Is there a correlation between **Driver Rating** and **Delivery Time**? (Do better drivers drive faster?)
- [ ] Calculate the total money lost on refunds (assume every late delivery costs the company $15).

### 💾 Data Generation Prompt
*Copy and paste this into an AI to generate your CSV:*
> "Generate a food delivery dataset with 1,000 rows. Columns: `Order_ID`, `Driver_ID`, `Vehicle_Type` (Bike, Scooter, Car), `City_Zone` (Downtown, Suburbs, University, Industrial), `Delivery_Time_Minutes` (10 to 60), `Weather` (Sunny, Rainy, Foggy), `Driver_Rating` (1.0 to 5.0), and `Order_Value`. Make 'Rainy' weather correlate with higher delivery times."