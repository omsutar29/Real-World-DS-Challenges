## 🎵 Challenge 2: The Music Mogul's Bet

### 📖 The Story
You meet a Record Label Executive at a coffee shop. You mention you can predict viral hits. He laughs, *"Everyone says that."* He writes a challenge on a napkin: *"I have a list of aspiring artists. Tell me who I should sign based on engagement, not just play count."*

### 🎯 The Mission
Analyze your mock data to answer:
- [ ] Which Artist has the highest **"Engagement Ratio"** (Likes + Shares / Plays)?
- [ ] What is the most common **Genre** among artists with over 1 Million plays?
- [ ] Who is the **"One Hit Wonder"**? (High plays on one song, zero/low on others).
- [ ] Rank the **top 5 songs** released in 2023.

### 💾 Data Generation Prompt
*Copy and paste this into an AI to generate your CSV:*
> "Generate a dataset with 500 rows representing music streaming data. Columns: `Song_ID`, `Artist_Name` (use 20 repeating names), `Song_Title`, `Genre`, `Release_Year` (2020-2024), `Play_Count` (1,000 to 10,000,000), `Like_Count`, `Share_Count`. Make sure `Like_Count` is always lower than `Play_Count`."