# Event Detection and Live Summarization through Sports Tweet Analysis
This a capstone project by Megan Williams required for completion of a Master's degree.

## Project Summary
This project is designed to live-tweet NFL games. We monitor mentions of 'NFL' on Twitter to detect games. Then, we analyze team name mentions and hashtags to extract more information about the game. We use a moving threshold technique based on the volume of game tweets to detect interesting events. Then, we use a RNN to generate a new tweet characterizing the event.

For more details, read the paper capstone.pdf. 

## Running the Project
This project depends on the Tweet collecting software found at https://github.com/Jefferson-Henrique/GetOldTweets-python. Download and install this repository, and be sure to get the python 3 version, found in the "got3" folder. Place this folder in the capstone directory.

Install other dependencies through pip:

``` pip install -r requirements.txt```

Then, open and run the Jupyter notebook capstone.ipynb with a Python 3 kernel. Launch Jupyter with the command:

```jupyter notebook```

 For best results, run on a GPU. 
