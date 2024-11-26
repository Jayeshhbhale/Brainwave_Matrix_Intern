# Data Analysis Projects

This repository contains two tasks focused on data analysis:

1. **Task 1: Vrinda Sales Analysis**: Analyzing the sales data of Vrinda Store using Power BI and Python.
2. **Task 2: Social Media Sentiment Analysis**: Analyzing Twitter data to determine public sentiment toward specific topics or events.

---

## Repository Structure

### Task 1: Vrinda Sales Analysis (Vrinda_Sales_Analysis/)
- **Store Data.xlsx**: The raw dataset used for sales analysis in the Vrinda Store project.
- **Power BI Folder**:
  - **Sales_Analysis_Power_BI.pbix**: Power BI file for the sales data analysis.
  - **Sales_Dashboard_Screenshot.png**: Screenshot of the Power BI dashboard with key metrics.
- **Python Files Folder**:
  - **Sales_Trend_Python_Script.py**: Python script used for analyzing sales trends and generating visualizations.
  - **Python_Screenshots/**: Screenshots of the Python code and key visualizations.

### Task 2: Social Media Sentiment Analysis (Social_Media_Sentiment_Analysis/)
- **Output Data Folder**:
  - **twitter_training.csv**: The training dataset containing Twitter data for sentiment analysis.
  - **training_data_with_sentiment.csv**: The training dataset with added sentiment scores.
- **Raw Data Folder**:
  - **twitter_validation.csv**: The validation dataset for testing the sentiment model.
  - **valid_data_with_sentiment.csv**: The validation dataset with added sentiment scores.
- **Screenshots Folder**:
  - **Code_Screenshots/**: Screenshots of the code used in the sentiment analysis project.
- **Python Script Folder**:
  - **sentiment_analysis.py**: Python script for preprocessing data, performing sentiment analysis, and generating visualizations.
  - **requirements.txt**: A list of the required Python libraries for running the sentiment analysis project.

---

## Task 1: Vrinda Sales Analysis

This project involves analyzing sales data from Vrinda Store using Power BI and Python.

### Tasks
1. **Power BI Analysis**: 
   - Developed an interactive dashboard in Power BI with key sales metrics including total sales by channel, category, size, age, and state-level mapping.
   - **Power BI Files**: The `.pbix` file used to create the analysis and a screenshot of the dashboard.
   
2. **Python Analysis**:
   - Performed detailed analysis of sales data, including trend analysis, customer segmentation, and visualization of state-wise sales distribution.
   - Visualized month-over-month growth.
   - **Python Scripts**: The Python code used for the analysis and screenshots of the generated visualizations.

### Example Visualizations
- **Sales Trends**: A line graph showing sales trends over time.
- **Top Customers**: A bar chart highlighting the top customers based on total sales.

---

## Task 2: Social Media Sentiment Analysis

This project involves analyzing Twitter data to extract sentiment using Natural Language Processing (NLP) techniques and visualizing sentiment trends.

### Tasks
1. **Preprocessing**: Cleaned the data by removing URLs, mentions, and stopwords. Performed tokenization and lemmatization on the tweets.
2. **Sentiment Analysis**: 
   - Used the VADER Sentiment Analysis tool to classify tweets into positive, negative, or neutral categories based on sentiment scores.
3. **Visualization**: 
   - Created word clouds from positive tweets and visualized the sentiment score distributions for both the training and validation datasets.

### Example Visualizations
- **Word Cloud for Positive Tweets**: A word cloud visualizing the most frequent terms in positive tweets.
- **Sentiment Score Distribution**: A histogram showing sentiment scores for the training and validation datasets.
- **Comparison of Sentiment Scores**: A comparison of sentiment scores between the training and validation datasets.

---

## Usage

### Task 1: Vrinda Sales Analysis
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/vrinda-sales-analysis.git
   ```
2. Open the Power BI file (`Sales_Analysis_Power_BI.pbix`) to explore the interactive dashboard.
3. For Python-based analysis, open the corresponding script files in the **Python Files** folder and run them for further insights.

### Task 2: Social Media Sentiment Analysis
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/social-media-sentiment-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd social-media-sentiment-analysis
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the sentiment analysis script:
   ```bash
   python python_files/sentiment_analysis.py
   ```


## License

This project is licensed under the MIT License.
