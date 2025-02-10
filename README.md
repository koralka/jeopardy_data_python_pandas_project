# 🏆 Jeopardy Data Analysis Project #
## :pushpin: Project Description ##
This project explores a dataset of **Jeopardy questions** to identify patterns, trends, and relationships between different aspects of the game. The dataset contains historical Jeopardy questions, their respective categories, monetary values, and answers.

This project is **my first attempt at working with a dataset using pandas**. 
It is part of Codecademy’s Data Science learning pathway, designed to help me practice data cleaning, filtering, and basic analysis.

## :bar_chart: Dataset Information ##
The dataset includes the following columns:
- **Air Date** – The date the question aired  
- **Round** – The game round (Jeopardy!, Double Jeopardy!, Final Jeopardy!)  
- **Category** – The category of the question  
- **Value** – The monetary value assigned to the question  
- **Question** – The question text  
- **Answer** – The correct response

## :dart: Project Goals ##
Since this project is primarily for **practice and skill development**, I focused on the following:  
✔ Filtering the dataset to find questions containing specific words  
✔ Converting monetary values into numerical data  
✔ Investigating how question topics have changed over time  
✔ Identifying the most common categories in each round  


## :hammer_and_wrench: How the Code Works ##
### :one:  Data Cleaning ###
- Renamed columns for consistency  
- Converted the "Value" column to a float for analysis  
- Extracted "Year" from the "Air Date" column  

### :two: Data Filtering & Analysis
- **Filtered questions** based on specific keywords (e.g., "King", "Computer")  
- **Calculated the average monetary value** of filtered questions  
- **Counted unique answers** to questions containing specific words  
- **Investigated category frequency** across Jeopardy rounds  
- **Compared question trends over time** (e.g., questions from the 90s vs. 2000s)


## :chart_with_upwards_trend: Key Findings ##
- The most frequent **Jeopardy!** category is **"BEFORE & AFTER"** in **Double Jeopardy!**  
- **Literature and Science** appear **far more often in Double Jeopardy!** than in Jeopardy!  
-  The word **"Computer" appeared more frequently in the 2000s than in the 1990s**  
- **"Stupid Answers"** is one of the most common categories in Jeopardy!

## :rocket: Future Improvements ##
As this is a **learning-focused project**, I plan to improve it by:
- Expanding the analysis to explore more question patterns  
- Introducing **data visualisations** (e.g., bar charts) to illustrate trends  
- Experimenting with more complex data analysis techniques

## :raised_hands: Acknowledgements ##
- [Codecademy](https://www.codecademy.com/learn) for providing the dataset.
- This project is a **work in progress**, and improvements will be made over time.

:pushpin: **Note:** Feedback and suggestions for improvement are welcome!
