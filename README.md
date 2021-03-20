# Twitter-Data-Analysis

### 1. Description 

Twitter's stream live data can be retrieved through Twitter's API once you have an Twitter developer account. Hence, we can utilize it to do some interesting data analysis or make some useful applications to serve our own purpose. This is a mini experimental project which makes an application for showing freqency of tweet's hashtags with stream live data. Furthermore, some additonal analysis can be implemented with stream live data. 


### 2. Tools

 * Python 3.6.1
 * Jupyter Notebook

### 3. Files
Requirement.txt - List of necessary Python libraries
tweets.txt - Stream data in json format from Twitter
codepurpose_Chen Wei.ipynb - Jupyter Notebook file of the project

### 4. General Project Steps

1. Create stream lisenter.
2. Store stream data into a txt file in local path.
3. Calling data from local file.
4. Doing necessary data transformation.
5. Plot out required data analysis figure.


### 5. Run notebook on local machine

1. Download and store all txt files and ipynb file to your own working path in local.
3. Install all necessary libraries following Requirement.txt
4. Create Twitter's developer account and obtain the consumer & acess key  [Access Link](https://developer.twitter.com/en/apply-for-access)
5. Add your own consumer and access key into scripts
   * consumer_key = 'xxxxxxxxx'
   * consumer_secret = 'xxxxxxxxx' 
   * access_token = 'xxxxxxxxx'
   * access_secret = 'xxxxxxxxx'
6. Run ipynb file locally.
