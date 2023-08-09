# British Airways Customer Feedback Analysis

Welcome to the British Airways Customer Feedback Analysis project! In this project, we scrape customer reviews from Skytrax about British Airways, clean and preprocess the data, and perform various analyses to extract valuable insights. Our goal is to provide actionable recommendations for enhancing customer satisfaction and improving operational efficiency at British Airways.

## Repository Contents

- `BA_DataAcquisition.ipynb`: Jupyter Notebook containing the code to scrape review data from Skytrax.
- `BA_DataPreprocessing.ipynb`: Jupyter Notebook containing data preprocessing steps including cleaning, handling missing values, and text preprocessing.
- `BA_DataAnalysis.ipynb`: Jupyter Notebook containing the analysis of the preprocessed data, addressing specific questions and generating insights.
- `BA_dict.pkl`: Pickle file containing processed data as a dictionary.
- `BA_reviews.csv`: CSV file containing cleaned and preprocessed review data.
- `analysis_explaination.pptx`: PowerPoint presentation explaining the analysis results and insights.

## Data Acquisition

We used the provided `BA_DataAcquisition.ipynb` notebook to scrape customer reviews from Skytrax for British Airways. The code retrieves review data, seat type, ratings, and recommendations for analysis.

## Data Preprocessing

The data collected was messy and required cleaning before analysis. In `BA_DataPreprocessing.ipynb`, we addressed missing values, handled outliers, and performed text preprocessing to prepare the data for analysis.

## Data Analysis

We aimed to answer several key questions through analysis:

1. How does the seat type affect the seat comfort rating?
2. Is there any correlation between cabin staff service and food and beverages rating?
3. What is the average inflight entertainment rating for each seat type?
4. What factors influence a higher likelihood of recommendations?
5. How many recommendations are 'Yes' based on seat type?
6. Which seat type offers the best service based on services rating?
7. Which seat type offers the best service based on reviews?
8. How likely is a high service rating given the best review?

Results of these analyses are documented in `BA_DataAnalysis.ipynb`.

## Getting Started

To replicate or further explore the analysis, follow these steps:

1. Clone this repository: `git clone [repository_url]`
2. Install the required Python libraries: `pip install -r requirements.txt`
3. Run the Jupyter notebooks in the provided order.

## Conclusion

Through rigorous data scraping, preprocessing, and analysis, we've gained insights into British Airways' customer feedback. Our findings contribute valuable recommendations that can impact decision-making processes within the airline industry.

Feel free to explore the notebooks, review the code, and leverage the insights to drive improvements in customer satisfaction and business operations.

**Let's collaborate and make flying with British Airways even better! ✈️**

For more information, contact Gaayana Revanna at `gaayanar.ds.ai@gmail.com`.

