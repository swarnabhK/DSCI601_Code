# Instructions on running the Twitter_StanceAnalysis.ipynb notebook:

1) Upload the notebook file in Google Colab.
2) Install required libraries: tldextract, transformers, re, ast, time, string etc using pip install.
This step might take a while depending on whether the packages are already installed in the system.
3) Import the data: The datasets which are to be imported are present in the Data folder. Please import 
the dataset as required, as mentioned in the code cells of the notebook. 
4) Run every cell in the notebook in order to replicate the results of Data Preprocessing, Data Exploration and Stance Analysis. 
Comments on what each cell does are present in the notebook.
5) For stance analysis section in the notebook, it takes time to return the results of classification depending on the size of the dataset.
For the dataframe containing 700 tweets(df_stance dataframe), it took us 44.38 minutes.

# Dataset information
## Data folder includes the following files
1) AllYoutubeComments.csv:
Dataset containing all the comments scraped from Youtube.

2) chessTweets_O02-O08:
Dataset containing all the tweets collected between October 02- October 08.

3) chessTweets_O09-O15.csv:
Dataset containing all the tweets collected between October 09- October 15.

4) chessTweets_O16-O22.csv:
Dataset containing all the tweets collected between October 16- October 22.

5) chessTweets_S04-S10.csv:
Dataset containing all the tweets collected between September 04- September 10.

6) chessTweets_S11-S17.csv:
Dataset containing all the tweets collected between September 11- September 17.

7) chessTweets_S18-S24.csv:
Dataset containing all the tweets collected between September 18- September 24.

8) chessTweets_S25-O01.csv:
Dataset containing all the tweets collected between September 25- October 01.

## src folder contains the notebook file

1) StanceAnalysisTwitter_final.html:
Html file containing the comments and code from the above notebook.

2) Twitter_StanceAnalysis.ipynb: 
Notebook containing preliminary stance analysis of tweets.

