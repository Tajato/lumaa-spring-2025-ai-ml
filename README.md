# AI/Machine Learning Intern Challenge: Simple Content-Based Recommendation

Developer: Tahj Gordon
---

## Overview

This project showcases a simple movie recommendation system using **TF-IDF** and **cosine similarity.** Below you will be instructed on how to run the Jupyter Notebook and test the recommendation system on your own.

### Dataset

The original dataset was retrieved from Kaggle. You can open it up from the directory or visit this link to view it on Kaggle - https://www.kaggle.com/datasets/rajugc/imdb-movies-dataset-based-on-genre?resource=download .. Be aware that the dataset zip file contains multiple files and I opted to use the action.csv file.


---

## Setting up my project

1. **Download/Clone my repository**  
   Clone or download my repository. It will contain all the files you need. 

2. **Create a virtual environment & activate environment (if you don't already have Jupyter Notebooks or Anaconda Navigator)**
  The follow commands might vary depending on which machine or type of command prompt you are using. However, in Git Bash, type:
 - py -m venv venv 
 - source venv/Scripts/activate
   

3. **Install requirements**  
   Run the following command: pip install -r requirements.txt

4. **Run jupyter notebook**  
   Type the following command to run and open my notebook in your browser: jupyter notebook recommender.ipynb

## The Solution

# Example Input:
- Enter a short movie description:
 "I love comedy"

# Example Output:
 Top 5 movie recommendations based on your description are:
 - 106    Pirates of the Caribbean: The Curse of the Bla...
- 322                                           Underworld 
- 662                           The Twilight Saga: Eclipse
- 67                                      The Mummy (1999)
- 321                                       Predestination

# Salary expectations: 25-30/hr