US Open Men’s Singles Analysis (2000–2024)

This project is part of my portfolio series “Answering Questions with Data.”

As the 2024 US Open heads into its final rounds, everything seems to point to what fans expected: another chapter in the ongoing Alcaraz vs. Sinner rivalry. That gives the impression of predictability—but has it always been like this? Has the US Open really been the most unpredictable Grand Slam of the 21st century, or is that reputation overstated?

To find out, I built a Power BI dashboard (powered by SQLite) designed to answer three key questions: Who have been the most successful champions? How often do big upsets actually occur? And how dominant have Top 10 players been compared to lower-ranked competitors?

Dataset and tools

The data comes from the Kaggle ATP men’s matches dataset. I filtered it to include only US Open matches from 2000 to 2024, then loaded it into SQLite for cleaning and transformation.

I used SQLite to create views for champions, upsets, and ranking buckets, and DB Browser for SQLite to validate queries. The final step was building the dashboard in Power BI, which allowed me to bring the story together visually.

The dashboard

The report is divided into three sections. The first, Champions, highlights the most successful players with a bar chart and provides a historical table of all finals. The second, Upsets, presents a KPI showing the overall upset percentage, an area chart tracking yearly fluctuations, and a detailed match table. Finally, Ranking Buckets shows the share of wins across ranking groups with a stacked column chart, includes a KPI focused on Top 10 dominance over the past decade, and adds text-based insights to put the numbers into context.

Key findings

The analysis confirms part of the common narrative: Federer, Djokovic, and Nadal dominated the era, but several one-time champions also left their mark. When it comes to unpredictability, the results are striking—28.8% of matches ended in upsets, with noticeable peaks in 2019 and 2023. And while Top 10 players captured over 70% of wins, lower-ranked competitors still played a decisive role in shaping the tournament’s storyline, reinforcing the US Open’s reputation as a stage where surprises are always possible.

How to explore it

The .pbix file can be opened in Power BI to interact with the dashboard. Each page provides a different lens on the data and shows how SQL and Power BI were combined to transform raw match records into meaningful insights.

About this project

This analysis is part of my transition into Data Analytics, combining SQL, Power BI, and storytelling to explore real-world questions and communicate insights effectively.
