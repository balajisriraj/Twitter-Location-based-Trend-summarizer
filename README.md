# Twitter-Summary-mini-Project

This project is to identify top trends in twitter and generates the summary of those trending hashtags in about 50 to 160 words using Text-to-Text transformer model.

#### Requirments: 
- Python packages mentioned in Requirments.txt
  To install packages use 
  ```
      !pip install <package name>
```
- Pre-trainined transformer model to be downloaded
- Twitter credentials like API Key, Access Tokens,etc
  Steps for getting Twitetr credentials:
    - Create a twitter account incase if you do not have already
    - Go to https://apps.twitter.com/
    - Click 'Create an app', this will help to create a developer account
    - Once you fill all the mandatory details you will be provided with required keys, please save those keys locally in a notepad for later use 
    

## Flow of the Project run:

### Step 1:
Identify the top trends in twitter for the current day with respect to the user defined location.
### Step 2:
Select the top n number of trends in the user defined language based on the volume of tweets available at the point of extraction.
### Step 3:
Extract the tweet data for those selected trends
### Step 4:
Do bit of data cleaning & processing to cater well for the model
### Step 5:
Put all the individual tweets together as a string chunk
### Step 6:
By leveraging pre- trained model’s ability, generate text summary of the tweets in about 50 to 160 words along with Word cloud graph for better understanding of the context.

