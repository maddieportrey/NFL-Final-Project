# NFL Success and College Conference

How do the college conference and division from which NFL players were drafted correlate with their success in the NFL? 

- Does a tougher schedule because of a higher caliber conference prepare players better for the competition of the NFL?
- Success can be defined as higher yardage or more touchdowns than average for each position.

## Sources:
- https://www.kaggle.com/datasets/zynicide/nfl-football-player-stats/code -- 25k player's stats for over 1,000,000 games played
- https://www.kaggle.com/datasets/jacklichtenstein/espn-nfl-draft-prospect-data?select=README.md -- Used to get player's college and conference

## Files:
- NFL_Data_Clean.ipynb -- combined datasets to start with a semi-interpretable one for the EDA, etc.
- NFL_EDA.ipynb -- includes EDA, model training, and model performance/evaluation
- total.csv -- cleaned data set from NFL_Data_Clean.ipynb

## Results:
- Logistic Regression: F1 - 0.213018
- Random Forest: F1 - 0.218648
- SVM: F1 - 0.219909
- AdaBoost: F1 - 0.158966

## Conclusions:
- There doesn't seem to be a huge correlation between NFL success and college conferences, but there's a lot more that could still be done with this question. In the future, I would like to explore what “success” could mean in a data set. It would be helpful to create a ranking system with accuracy, team wins, etc., but it would be difficult to create a grading system that every type of player could be on. Alternatively, there could be multiple models – one for each position, so that new variables don’t mess up other types of players. For models, exploring more ensemble techniques that combine the strengths of multiple models could be helpful. Stacking or blending models could potentially improve predictive performance because of the diverse perspectives offered by different algorithms.
