# Red Card and Goal Analysis > [Go to project]([https://github.com/tophercollins/eifo-data-extraction](https://github.com/tophercollins/red_card_goal_analysis/])

This project involved analyzing the relationship between red cards and goal-scoring in football matches using Python in Jupyter Notebooks. The analysis explored trends and patterns in match outcomes, leveraging statistical modeling and data visualization to uncover insights into the impact of red cards on goal-scoring dynamics.

---

## Problem Definition  
The objective was to determine whether red cards influence goal-scoring in football matches, focusing on both the overall effect and the timing of red cards. The analysis aimed to provide statistically valid insights into game dynamics and trends.

---

## Data  
The datasets used contained detailed information from 19,294 football matches and 54,451 in-game events over five seasons from 10 European national leagues. Key features included match identifiers, goals scored, red card events, and event timing.

**Key Metrics**:
- Total matches: 19,294  
- Total goals: 50,356  
- Total red cards: 4,131  
- Mean goals per game: 2.61  

---

## Evaluation  
The analysis aimed to assess the relationship between red cards and goal-scoring using statistical models. Specific hypotheses tested included whether red cards lead to more goals overall, and whether the timing of a red card affects total goals scored.

---

## Features  
Derived features included:
- Total goals scored per game
- Timing of the first red card
- Red card occurrence indicators
- Goal-scoring rates pre- and post-red cards

---

## Process  

1. **Exploratory Data Analysis (EDA)**  
   - Conducted a detailed exploration of match and event datasets.
   - Identified trends such as higher goal rates in the second half and linear increases in red cards over time.

2. **Feature Engineering**  
   - Extracted relevant features, such as the timing of the first red card and minute-by-minute goal rates.

3. **Statistical Modeling**  
   - Applied Poisson Means Tests and Linear Regression to test hypotheses.
   - Compared goal averages between games with and without red cards and analyzed the impact of red card timing.

4. **Visualization**  
   - Used Matplotlib and Seaborn to visualize correlations, goal-scoring trends, and event timing distributions.

5. **Hypothesis Testing Results**  
   - Red cards do not significantly increase overall goal counts (p-value: 0.43).
   - Earlier red cards may lead to slightly more goals (p-value: 0.067).
   - Goal-scoring rates increase post-red cards (0.037 goals/min vs. 0.028 goals/min before red cards).

---

## Conclusion  
This analysis demonstrated a nuanced relationship between red cards and goal-scoring, with evidence suggesting that red cards influence short-term scoring dynamics. While no statistically significant overall impact was found, timing plays a critical role. These findings offer actionable insights for football strategy and in-play betting scenarios.
