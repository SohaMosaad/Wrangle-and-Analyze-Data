# Wrangle-and-Analyze-Data
Udacity project 'data Professional Analyst - Advanced Track'. Using Python and its libraries, gathering data from a variety of sources and in a variety of formats, assessing its quality and tidiness, then cleaning it. This is called data wrangling. The wrangling efforts are documented in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries).

# Project Details
## Data wrangling, which consists of:
- Gathering data (downloadable file in the Resources tab in the left most panel of your classroom and linked in step 1 below).
- Assessing data
- Cleaning data
- Storing, analyzing, and visualizing the wrangled data
- Reporting on 1) Data wrangling efforts and 2) Data analyses and visualizations

# Gathering Data for this Project
## Gather each of the three pieces of data in a Jupyter Notebook titled wrangle_act.ipynb:

- The WeRateDogs Twitter archive. Download this file manually 'twitter_archive_enhanced.csv'

- The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. This file (image_predictions.tsv) is hosted on Udacity's servers and should be downloaded programmatically using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

- Each tweet's retweet count and favorite ("like") count at minimum, and any additional data you find interesting. Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt file. Each tweet's JSON data should be written to its own line. Then read this .txt file line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite count. 

# Assessing Data for this Project
After gathering each of the above pieces of data, assess them visually and programmatically for quality and tidiness issues. Detect and document nine quality issues and five tidiness issues in wrangle_act.ipynb Jupyter Notebook. 

# Cleaning Data for this Project
- Clean each of the issues documented while assessing. Perform this cleaning in wrangle_act.ipynb as well. 
- Storing, Analyzing, and Visualizing Data for this Project
Store the clean DataFrame(s) in a CSV file with the main one named twitter_archive_master.csv. .
- Analyze and visualize the wrangled data in wrangle_act.ipynb Jupyter Notebook.

# Reporting for this Project
- report called wrangle_report.pdf that briefly describes the wrangling efforts.
- report called act_report.pdf that communicates the insights and displays the visualization(s) produced from the wrangled data.
