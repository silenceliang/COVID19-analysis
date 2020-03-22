# COVID19_Analysis
Using datasets credited by WHO, we analyze a variety of aspects that probably  were reasons why  this world is covered by such a disaster.<br>
This is one of the two complementary forecasting tasks to predict COVID-19 spread. This task is based on various regions across the world. To start on a single state-level subcomponent, please see the companion forecasting task for California, USA.

## Background
The White House Office of Science and Technology Policy (OSTP) pulled together a coalition research groups and companies (including Kaggle) to prepare the COVID-19 Open Research Dataset (CORD-19) to attempt to address key open scientific questions on COVID-19. Those questions are drawn from National Academies of Sciences, Engineering, and Medicine’s (NASEM) and the World Health Organization (WHO).

## The Challenge
Kaggle is launching two companion COVID-19 forecasting challenges to help answer a subset of the NASEM/WHO questions. While the challenge involves forecasting confirmed cases and fatalities between March 25 and April 22 by region, the primary goal isn't to produce accurate forecasts. It’s to identify factors that appear to impact the transmission rate of COVID-19.

You are encouraged to pull in, curate and share data sources that might be helpful. If you find variables that look like they impact the transmission rate, please share your finding in a notebook.

As the data becomes available, we will update the leaderboard with live results based on data made available from the Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE).

We have received support and guidance from health and policy organizations in launching these challenges. We're hopeful the Kaggle community can make valuable contributions to developing a better understanding of factors that impact the transmission of COVID-19.

## Data Description

In this challenge, you will be predicting the cumulative number of confirmed COVID19 cases in various locations across the world, as well as the number of resulting fatalities, for future dates.

We understand this is a serious situation, and in no way want to trivialize the human impact this crisis is causing by predicting fatalities. Our goal is to provide better methods for estimates that can assist medical and governmental institutions to prepare and adjust as pandemics unfold.

### Files
- train.csv - the training data up to Mar 18, 2020.
- test.csv - the dates to predict; there is a week of overlap with the training data for the initial Public leaderboard. Once submissions are paused, the Public leaderboard will update based on last 28 days of predicted data.
- submission.csv - a sample submission in the correct format; again, predictions should be cumulative
### Data Source
This evaluation data for this competition comes from John Hopkins CSSE, which is uninvolved in the competition.
See their README for a description of how the data was collected.
They are currently updating the data daily.

## Companies and Organizations
There is also a call to action for companies and other organizations: If you have datasets that might be useful, please upload them to Kaggle’s dataset platform and reference them in this forum thread. That will make them accessible to those participating in this challenge and a resource to the wider scientific community.

## Acknowledgements
JHU CSSE for making the data available to the public. The White House OSTP for pulling together the key open questions. The image comes from the Center for Disease Control.

## Reference
kaggle: https://www.kaggle.com/c/covid19-global-forecasting-week-1/overview
