# Airline Review Analysis

This project analyzes airline reviews to understand customer satisfaction and identify key factors influencing travel experiences. The analysis includes data cleaning, exploratory data analysis, sentiment analysis, and hypothesis testing.

## Project Overview

The project aims to:
- Determine what factors are influencing consumer decisions.
- Analyse how holiday booking times affect consumer behavior.
- Investigate the level of popularity of different airline schedules and routes.
  
It aims to answer the following research questions:
1. What is the relationship between traveller type and customer satisfaction?
2. How does the travel season affect customer satisfaction?
3. Is there a difference in customer satisfaction between different travel classes?
4. Which routes have the highest and lowest customer satisfaction?

## Dataset

The dataset used for this project is "Airline_Review.csv," which contains airline reviews. It includes passenger name, flying month, route, rating, review content, traveller type, and class.

## Methodology

The project follows these steps:

1. Data cleaning:
   - Handling missing values
   - Removing duplicates
   - Cleaning and formatting data columns

2. Exploratory data analysis:
   - Analyzing the distribution of ratings
   - Identifying popular routes
   - Exploring traveller type and class distributions

3. Sentiment analysis:
   - Classifying reviews as negative, positive, or neutral using sentiment intensity analysis

4. Hypothesis testing:
   - Using statistical tests to analyze the relationship between variables and answer research questions

## Results

- Customer satisfaction varies depending on the traveller type, travel season, and travel class.
- Specific routes have notable differences in customer satisfaction levels.
- The sentiment analysis provides insights into the overall customer perception of the airline.

## Screenshots
The percentage of positive, negative, and neutral reviews.
<img width="678" alt="Screenshot 2025-03-23 at 09 07 33" src="https://github.com/user-attachments/assets/cb69c4ce-13f2-4cf2-9495-8753fa00be40" />

<img width="792" alt="Screenshot 2025-03-23 at 09 06 22" src="https://github.com/user-attachments/assets/861d669a-893a-4f3c-8761-aaf656e858e0" />

- **Word Clouds:** Word clouds for positive, negative, and neutral sentiments.
- <img width="791" alt="Screenshot 2025-03-23 at 09 09 07" src="https://github.com/user-attachments/assets/a89c26d3-82e3-48fc-a911-80ae4bb36b1a" />
<img width="791" alt="Screenshot 2025-03-23 at 09 08 58" src="https://github.com/user-attachments/assets/800865e9-0567-4dbc-9b8f-8eb41385723b" />
<img width="791" alt="Screenshot 2025-03-23 at 09 09 07" src="https://github.com/user-attachments/assets/edcb4863-8b56-4df2-87ca-d994f093ae12" />
![Uploading Screenshot 2025-03-23 at 09.08.58.png…]()
<img width="791" alt="Screenshot 2025-03-23 at 09 08 49" src="https://github.com/user-attachments/assets/e6d11b4a-66e0-4d84-91fc-be349664311a" />


- **Correlation Matrix:** Heatmap showing correlations between sentiment and other variables (traveller type, class).
- **Customer Satisfaction by Season and Traveller Type/Class:** Bar charts showing mean ratings for different seasons, traveller types, and travel classes.
- **Sentiment Distribution for Top Routes:** A stacked bar chart showing the sentiment distribution for the top 10 routes.

These screenshots will provide a visual overview of the project's findings and make the README more engaging.

## Requirements

- Python 3
- pandas
- numpy
- seaborn
- matplotlib
- nltk
- wordcloud
- scipy

## Contributors
[Your Name]

## Acknowledgements

- [Dataset source]

## License

[Your chosen license]
