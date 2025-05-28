# IPL - Tableau- Visualization
The Indian Premier League (IPL) is one of the world’s most competitive T20 cricket tournaments.
The analysis aims to uncover insights about match outcomes, strategies, and venues.
This dataset sourced from a Kaggle notebook by Razamh.
It focus on visualization-based storytelling using Tableau to support hypotheses.

## Data Cleaning:
### matches.csv
Originally had 756 rows, with several missing values in critical columns..
After cleaning, retained 118 rows with complete data to ensure analytical integrity.

### deliveries.csv
Contained over 179,000 rows.
Major nulls in dismissal-related fields (e.g., player_dismissed, fielder).
Post-cleaning: 6,448 high-quality rows focused on dismissals.

## Tools Used:
Excel for preprocessing.
Tableau for further filtering and visualization.

## Few Results of Conducted Hypothesis:
### Hypothesis 1: IPL Match Outcome Analysis – Chasing vs. Defending

This project explores one of the key hypotheses in IPL cricket:
Do teams chasing a target (batting second) win more often than those defending (batting first)?

#### 📊 Visualization Overview


Bar chart showing percentage of matches won by chasing vs. defending teams.

Chasing Wins: 54.64%
Defending Wins: 45.36%

#### 🔍 Insights & Interpretation

Teams chasing tend to win more, likely due to:
Tactical advantage of knowing the target.
Pitch behavior and dew factor favoring the team batting second in night matches.
The data supports the growing trend of captains choosing to field first after winning the toss.

#### 📁 Files Included

ipl_outcome_analysis.ipynb – Code for data cleaning, analysis, and visualization.

match_outcome_chart.png – Bar chart comparing match outcomes.

#### Result:
![image](https://github.com/user-attachments/assets/20e6ccb6-fdb6-486c-bf40-77bb57f2c7a9)

## How to Run

Clone the repository
git clone https://github.com/yourusername/ipl-chasing-vs-defending.git
cd ipl-chasing-vs-defending
Launch the Jupyter Notebook
jupyter notebook
Open ipl_outcome_analysis.ipynb and run all cells.

### Hypothesis 2: Does Winning the Toss Increase the Chances of Winning the Match?

This visualization investigates the common belief that winning the toss provides a strategic advantage in an IPL match.

#### 📊 Visualization

A bar chart comparing match outcomes based on toss results.

#### 🔍 Key Findings
Toss Winners Who Also Won the Match: 52.26%
Toss Losers Who Won the Match: 47.74%
#### 🧠 Interpretation
Tactical Edge: Winning the toss offers the captain flexibility — to bat or field first based on pitch, weather, or team strengths.
Not a Decisive Factor: With nearly even win rates, it’s evident that game execution, team performance, and on-field decisions outweigh pre-match advantages.
Strategic Depth: The data supports the idea that while the toss provides options, match outcomes are more dependent on how well teams adapt during the game.

#### Result:
![image](https://github.com/user-attachments/assets/a55909de-acb6-45b6-890e-c8094e3f5a09)

### Hypothesis 3:Do Chasing Teams Have an Advantage at Eden Gardens?

This visualization explores whether Eden Gardens—a historic IPL venue—favors teams chasing a target.

#### 📊 Visualization

A pie chart showing win distribution at Eden Gardens based on innings order.

####  📈 Key Results
🟢 Chasing Win Rate: 58.44%
🔴 Defending Win Rate: 41.56%
####  🧠 Interpretation
Environmental Factors: Dew accumulation and pitch behavior under lights make chasing easier during evening matches.
Crowd Pressure: The iconic stadium's charged atmosphere may add pressure to defending teams.
Strategic Insight: Captains winning the toss should opt to bowl first at Eden Gardens.
Broader Implication: Reinforces the importance of venue-specific data for tactical planning in the IPL.

#### Result:
![image](https://github.com/user-attachments/assets/11a58e79-6534-4dca-be35-f63efd8ccf86)

## Conclusion:
The Tableau-driven analysis highlights that while elements like match strategy, toss outcome, and venue characteristics do influence IPL match results, none of them alone guarantee victory. Teams chasing targets hold a marginal advantage (54.64%), and certain grounds like Eden Gardens amplify this trend with a higher chasing win rate (58.44%). However, the toss offers only a slight edge (52.26%), suggesting its influence is limited.

Ultimately, on-field performance remains the most decisive factor. Success in the IPL demands a holistic, data-informed, and flexible strategy—one that adapts to real-time conditions rather than leaning on a single variable. Winning teams combine insights from data with execution under pressure, showcasing that cricket is as much a game of preparation as it is of performance.

