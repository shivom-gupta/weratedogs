# WeRateDogs Twitter Data Analysis

### Overview

This project focuses on wrangling, analyzing, and visualizing the tweet archive of the popular Twitter account, [@dog_rates](https://twitter.com/dog_rates), also known as WeRateDogs. This account, with over 4 million followers, humorously rates dogs and has garnered international attention. The goal of this project is to clean and process the data, extract interesting insights, and create visualizations that showcase trends and patterns in the dog ratings and social media interactions.

### Project Workflow

1. **Data Gathering:**
   - **WeRateDogs Twitter Archive:** Directly downloaded and loaded into a DataFrame.
   - **Tweet Image Predictions:** Downloaded programmatically and imported as a DataFrame.
   - **Additional Data via Twitter API:** Collected using Tweepy, including retweet and like counts for the tweets.

2. **Data Assessment:**
   - **Visual Assessment:** Data was visually inspected in the Jupyter Notebook.
   - **Programmatic Assessment:** Used Pandas functions to assess data quality, identify missing values, duplicates, and data type issues.

3. **Data Cleaning:**
   - Addressed identified issues including missing data, incorrect data types, and inconsistencies.
   - Merged the different datasets to create a master dataset that is clean and ready for analysis.

4. **Data Storage:**
   - The cleaned and merged dataset was stored as `twitter_archive_master.csv` for future analysis.

5. **Data Analysis and Visualization:**
   - Analyzed the cleaned data to uncover interesting insights:
     - **Popular Breeds:** Golden Retriever, Labrador Retriever, and Pembroke are the most frequently rated breeds.
     - **Highest Rated Stage:** Puppo receives the highest average ratings.
     - **Social Media Popularity:** Breeds like French Bulldog, Samoyed, and Cocker Spaniel are top in favorites and retweets.
   - Created visualizations to illustrate these trends and findings.

6. **Reporting:**
   - The project includes two comprehensive reports:
     - **Wrangle Report:** Details the data wrangling process, from gathering to cleaning.
     - **Act Report:** Summarizes the analysis, insights, and visualizations.

### How to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/shivom-gupta/weratedogs.git
   cd weratedogs
   ```

2. **Set Up the Environment:**
   - Ensure Python and Jupyter Notebook are installed.
   - Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**
   - Launch Jupyter Notebook and open `wrangle_act.ipynb` to explore the data wrangling and analysis process.

### Key Files

- **`wrangle_act.ipynb`**: The Jupyter Notebook containing the entire data wrangling process.
- **`twitter_archive_master.csv`**: The cleaned and merged dataset.
- **`wrangle_report.pdf`**: A detailed report on the data wrangling process.
- **`act_report.pdf`**: A report summarizing the analysis and key findings.

### Key Insights

- **Top Breeds**: Golden Retriever, French Bulldog, and Samoyed are among the most interacted with breeds on social media.
- **Dog Ratings**: Puppo stage dogs receive the highest ratings on average.
- **Popular Dog Names**: Oliver, Cooper, and Charlie are the most common dog names in the dataset.
- **Engagement Trends**: Number of retweets and likes are highly correlated.

### Conclusion

This project offers a comprehensive analysis of the WeRateDogs Twitter account, providing insights into dog ratings, breed popularity, and social media engagement. It serves as a robust example of data wrangling, exploratory data analysis, and visualization.
