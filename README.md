# Forever Red Vs Blue
## League of Legends: Analysis of Main Objectives and Their Impact on Match Outcomes

__By Lotus Baumgarner__

Since its inception in October 2009, League of Legends has emerged as one of the foremost esports globally, boasting a player base and fan following that rivals, and perhaps surpasses, even the NFL. Despite significant evolution since its original client, League of Legends has consistently maintained its reputation as a skill-based, free-to-play game. Monetization is strictly through optional character customization, ensuring no pay-to-win elements.

Each match in League of Legends begins with all players starting at level one. Players must collaborate with their teammates to level up, purchase new items, and achieve various in-game objectives to secure victory.

This project focuses on analyzing the key objectives within League of Legends matches and evaluating their impact on the likelihood of winning. By examining objective-related data, we aim to provide actionable insights into the strategic elements that most significantly influence match outcomes.


## Data Set Overview and EDAs

The data set, titled __League of Legends Ranked Match Data from NA__, was sourced from Kaggle and comprises data from over 10,000 matches featuring players approximately ranked at the Gold level within League of Legends. The original dataset contains 775 columns, capturing a wide array of variables including individual player items, kills, deaths, champions, and various team statistics and objectives.

__Original Data Set Link:__ https://www.kaggle.com/datasets/jamesbting/league-of-legends-ranked-match-data-from-na

For this personal project, the focus was narrowed to the primary objectives of the game rather than individual player statistics. So I ended up removing about 375 columns for both the Red Team and the Blue Team reducing the dataset to 24 columns. Further refinements, such as combining similar columns (e.g., b_tower_kills and r_tower_kills), resulted in a final dataset comprising 17 columns.

Notably, the dataset contained no missing values, and the target variable, Winner, was relatively balanced. As a result, all 10,013 rows were retained, yielding a final dataset of 10,013 rows across 17 columns.

This refined dataset will be utilized to analyze the impact of key objectives on match outcomes, providing insights into the strategic elements that most significantly influence victory in League of Legends.


## Columns After Cleaning and Formatting:
__Tower_Kills_Blue:__ Number of towers killed by the blue team  
__Inhib_Kills_Blue:__ Number of inhibitors taken by the blue team  
__Baron_Kills_Blue:__ Number of Barons killed by the blue team  
__Dragon_Kills_Blue:__ Number of dragons killed by the blue team  
__Rift_Kills_Blue:__ Number of Rift Heralds killed by the blue team  
__Tower_Kills_Red:__ Number of towers killed by the red team  
__Inhib_Kills_Red:__ Number of inhibitors taken by the red team  
__Baron_Kills_Red:__ Number of Barons killed by the red team  
__Dragon_Kills_Red:__ Number of dragons killed by the red team  
__Rift_Kills_Red:__ Number of Rift Heralds killed by the red team  
__First_Blood:__ Team that achieved the first kill  
__First_Tower:__ Team that destroyed the first tower  
__First_Inhibitor:__ Team that destroyed the first inhibitor  
__First_Baron:__ Team that killed the first Baron  
__First_Dragon:__ Team that killed the first dragon  
__First_Rift_Herald:__ Team that killed the first Rift Herald  
__Winner:__ The team that won the game  


