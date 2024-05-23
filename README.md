# Forever Red Vs Blue
## League of Legends: Analysis of Main Objectives and Their Impact on Match Outcomes

__By Lotus Baumgarner__

### *Overview*
League of Legends (LoL), launched in October 2009, has become a premier esport globally, with a player base and fan following that rivals even the NFL. Despite its evolution since the original client, LoL has remained a skill-based, free-to-play game, with monetization strictly through optional character customization, ensuring no pay-to-win elements.

Each match in LoL starts with all players at level one. Players collaborate with teammates to level up, purchase new items, and achieve various in-game objectives to secure victory.

### *Project Objective*
This project aims to analyze the key objectives within League of Legends matches and evaluate their impact on the likelihood of winning. By examining objective-related data, the goal is to provide actionable insights into the strategic elements that most significantly influence match outcomes.

### *Dataset Overview*
The dataset, titled League of Legends Ranked Match Data from NA, was sourced from Kaggle and comprises data from over 10,000 matches featuring players approximately ranked at the Gold level within League of Legends. The original dataset contains 775 columns, capturing a wide array of variables, including individual player items, kills, deaths, champions, and various team statistics and objectives.

For this personal project, the focus was narrowed to the primary objectives of the game rather than individual player statistics. Consequently, all rows pertaining to summoners 1 to 5 on both the Red and Blue teams were removed, reducing the dataset to 24 columns. Further refinements, such as combining similar columns (e.g., b_tower_kills and r_tower_kills), resulted in a final dataset tailored to analyze the key objectives.

### *Key Objectives Analyzed*
- First Blood
- First Tower
- First Inhibitor
- First Baron
- First Dragon
- First Rift Herald
- Total Tower Kills
- Total Inhibitor Kills
- Total Baron Kills
- Total Dragon Kills
- Total Rift Herald Kills

### *Analysis and Findings*

__Data Cleaning and Preparation:__
- Removed individual player statistics.
- Combined similar columns for a consolidated view of team objectives.
- Ensured data consistency and accuracy by checking for extra characters or white spaces in column names.


__Exploratory Data Analysis (EDA):__
- Conducted initial analysis to understand the distribution and correlation of key objectives with match outcomes.
- Visualized data to identify trends and patterns.


__Impact Analysis:__
- Evaluated the impact of achieving each key objective on the likelihood of winning a match.
- Used statistical methods to determine the significance of each objective.


### *Conclusion*
The analysis provides insights into the strategic importance of key objectives in League of Legends. Understanding the impact of these objectives can help players and teams make more informed decisions during matches, potentially increasing their chances of winning.


### *Future Work*
- Expand the analysis to include matches from other regions and different ranks.
- Incorporate machine learning models to predict match outcomes based on key objectives.
- Explore the impact of patch updates on the significance of different objectives.

### *Acknowledgments*
- Kaggle for providing the dataset.
- The League of Legends community for their continuous support and engagement.

### Repository Structure

├── Data  
├── Images  
├── .gitignore  
├── LeagueOfLegends.ipynb  
├── PowerPoint_PDF.pdf  
└── README.md  