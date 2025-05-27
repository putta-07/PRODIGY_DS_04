# Twitter Sentiment Analysis

This project analyzes the sentiment of tweets towards popular topics on Twitter. It uses a dataset of tweets labeled with sentiment (positive, negative, or neutral) and identifies the top mentioned topics. The project then visualizes the sentiment distribution for each topic to understand public opinion.

## Dataset

The project uses the following datasets:

* **twitter_training.csv:** This file contains the training data for the sentiment analysis model.
* **twitter_validation.csv:** This file contains the validation data for the sentiment analysis model.

The datasets contain the following columns:

* **id:** Unique identifier for each tweet
* **entity:** The topic or brand mentioned in the tweet
* **sentiment:** The sentiment of the tweet (positive, negative, or neutral)
* **text:** The text of the tweet

## Methodology

The project follows these steps:

1. Load the datasets using pandas.
2. Identify the top 10 most mentioned topics using value_counts().
3. Filter the data to include only tweets related to the top topics.
4. Use seaborn to create a countplot that shows the sentiment distribution for each top topic.
5. Analyze the plot to understand the prevalent sentiments towards each topic.

## Results

The analysis reveals the prevalent sentiments expressed towards popular topics on Twitter. Topics like Apple, Google, and Microsoft show a mix of positive, negative, and neutral sentiments, suggesting diverse user opinions. Some topics might exhibit predominantly positive or negative sentiments, indicating a clear public perception. By examining the distribution, we can understand the general sentiment surrounding specific brands and topics.

## Further Analysis

Further analysis could involve:

* A deeper dive into the specific tweets to understand the reasons behind the sentiments.
* Comparing sentiment distributions across different time periods.
* Investigating the impact of external events or news on sentiment trends.

## Conclusion

This analysis provides a valuable overview of sentiment towards the top mentioned topics on Twitter, enabling you to understand public opinion and potentially inform decision-making.

## Usage

To run the analysis, follow these steps:

1. Upload the datasets (`twitter_training.csv` and `twitter_validation.csv`) to your Google Colab environment.
2. Copy and paste the code from the notebook into a Colab notebook.
3. Run the code to generate the sentiment distribution plot.

## Dependencies

This project requires the following libraries:

* pandas
* matplotlib
* seaborn

You can install them using pip:
