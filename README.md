# US Open Men’s Singles Analysis (2000–2024)

This project is part of my **"Answering Questions with Data"** portfolio series.  

We are reaching the final stages of the 2024 US Open and everything looks predictable — another chapter in the **Alcaraz vs. Sinner saga** seems inevitable.  

But has it always been like this? Was the US Open predictable throughout the 21st century, or has it earned its reputation as the most unpredictable Grand Slam?  

To explore this, I built a Power BI dashboard (backed by SQLite) to answer three questions:

## Key Questions
1. **Champions** – Who has won the most titles since 2000?  
2. **Upsets** – How frequent are shocking defeats?  
3. **Ranking Buckets** – How dominant are Top 10 players compared to lower-ranked competitors?  

## Dataset
- Source: Kaggle ATP men’s matches dataset.  
- Filtered to include only US Open matches from 2000 to 2024.  
- Loaded into **SQLite** for data cleaning and transformation.  

## Tools
- **SQLite**: Built views for champions, upsets, and ranking buckets.  
- **DB Browser for SQLite**: Query validation.  
- **Power BI**: Dashboard creation and storytelling.  

## Dashboard Pages
1. **Champions**  
   - Bar chart of most successful champions.  
   - Historical table of finals.  

2. **Upsets**  
   - KPI card with upset percentage.  
   - Area chart showing upsets per year.  
   - Table with detailed upset matches.  

3. **Ranking Buckets**  
   - 100% stacked column chart showing win share by ranking bucket.  
   - KPI card for Top 10 win share (last decade).  
   - Text insights highlighting dominance and unpredictability.  

## Key Insights
- Federer, Djokovic, and Nadal dominate the era, but multiple one-time champions also appear.  
- **28.8% of matches were upsets**, with peaks in 2019 and 2023.  
- Top 10 players consistently secure over 70% of wins, yet lower-ranked players still shape the narrative.  

## How to Use
- Open the Power BI dashboard (`.pbix`) to interact with the visuals.  
- Explore each page to see how SQL and Power BI were combined to transform raw data into insights.  

## About
This project is part of my transition into Data Analytics, combining SQL, Power BI, and storytelling to answer real-world questions with data.
