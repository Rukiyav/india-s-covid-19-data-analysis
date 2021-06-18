India's covid-19 Data Analytics
==============================

A file structure template, development environment and rule set for python data analytics projects on the data analytics team

**About Project**
------------
This is about analysing India's covid 19 data using python

**Project Tech stack Used:**
------------
#Data Set Obtained from: kaggle
#Project Description:
##No. Of. Engineers: 1
###Python Package Manager and Deployment: anaconda
#Tool: jupyter notebook
#Libraries:Numpy,pandas,seaborn,matplotlib

What Is This?
-------------

This is a Python Jupyter Notebook file that collects, analyzes the Covid-19 data for India and give a skeptical view about the condition that India is dealing with in today's Second wave. Current Data manifests the details of Second wave in India and gives the details of Recovery Rate against the Total cases and also the Deaths against Total Cases.

**Note**: This data is obtained from Kaggle data set.

How It Works
---------------

1. Clone the repository
2. Register a new Uber application and make your Redirect URI `http://localhost:7000/submit` - ensure that both the `profile` and `history` OAuth scopes are checked.
3. Fill in the relevant information in the `config.json` file in the root folder and add your client id and secret as the environment variables `UBER_CLIENT_ID` and `UBER_CLIENT_SECRET`.
4. Run `export UBER_CLIENT_ID="`*{your client id}*`"&&export UBER_CLIENT_SECRET="`*{your client secret}*`"`
5. Run `pip install -r requirements.txt` to install dependencies
6. Run `python app.py`
7. Navigate to http://localhost:7000 in your browser

Data is processed using pandas and numpy , data visulation is done by using seaborn
Data is read by using pandas
