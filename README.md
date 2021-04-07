# Communicate-Data-Findings
## by Hager Mohamed


## Dataset

> In This project I investigate FordGoBike dataset. It is a regional public bike sharing system in the San Francisco Bay Area, California. FordGoBike is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States.The dataset used for this exploratory analysis

 ##### Data wrangling process:
1. remove unused features (coloumns)
2. remove nan values
3. extract start day,month and hour from start time and end time
4. extract start day from start time
5. calculate member age

## Summary of Findings

> There are two types of clients using the system: Subscribers and Customers. Subscribers are primarily daily commuters, having short trips to and from work, who rent a bike on weekdays at 8-9am and 5-6pm. Customers are usually tourists or occassional riders who use the system mainly on weekends to explore the Bay Area. Age is also a factor within user type. Subscribers who fall in the age group between 26-35 years old are the most common age group to use the bike sharing system. The 26-32 years old also lead the spike which occurs across all age groups in October. Subscribers who fall in the 32-45 year old age group are the next most common age group to use the bike sharing system, and follow a similar trend at the 26-32 year olds.

### Files
- readme.md - This Markdown file contains sections that you should fill out as you select your dataset, complete your exploration, and plan your explanatory analysis. 

- exploration_template.ipynb - This Jupyter Notebook contains section templates to help you organize your exploration, starting from loading in the data, working through univariate visualizations, and ending with bivariate and multivariate exploration. 

- slide_deck_template.ipynb - This Jupyter Notebook contains starter cells to help you organize your slide deck deliverable. These cells provide an example of how the slide deck should be organized, including pre-set slideshow settings.

To view the slide deck, you will need to use the expression (all one line):
jupyter nbconvert Example_Project_Diamonds_Part2.ipynb --to slides --post serve --template output_toggle

- output_toggle.tpl - This template file can be used with nbconvert to export your slide deck. This adds extra functionality to the slide deck by hiding the code to start, only making it visible if the reader clicks on the output (which should mostly be visualizations in the case of this project).

## Key Insights for Presentation

> For the presentation, I focus on just the user types, gender,trip_duration and age. I start by showing the percentage of bike rides for all user types subcriber and customer, it's show the subcriber users are 91% and that mean the customer users are 9%.
Then I plot the number of bike rides (trips) for each day based on gender, it's plot the number of trips for evryday to show trips number for each gender on all days.
