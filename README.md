# Glassdoor Employeee Review Predictor

Using a Glassdoor employee reviews dataset, I constructed a unsupervised neural net and a random forest regressor to predict the star rating an employee would give their employer based on a series of features including sentiment scores and text analysis based on their review. I assessed both models' performance and found the random forest to work better.

## Findings
The best reviews mentioned a good work life balance, flexible work hours, and a good work environment. The worst reviews included comments about bad management, long work hours, bad work life balance, and low pay. These were commmon phrases based on sentiment score and word clouds were outputted to the graphs folder.

## File Directory
- `./data/` includes all csv files
- `./data/test/` includes test data I used to assess the performance of my model
- `./graphs/` includes all graphs generated through my analysis
- `main.ipynb` is the Jupyter notebook with all my code and results

## How to run
1. Git clone the repo
2. Run `pip install -r requirements.txt`
3. Run the cells in main.ipynb
