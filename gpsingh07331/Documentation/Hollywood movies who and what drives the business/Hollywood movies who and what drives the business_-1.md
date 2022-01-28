## `**Hollywood movies who and what drives the business**`

**Table of Contents:**

- Introductory section
    
- Methodology section
    
- Future targets
    
- References
    
- Team
    
- Acknowledgments
    

***Introductory section***

Since the foraying of Netflix, Amazon and other Tech giants into movie content creation and the ease of watching the movie from the comfort of home, traditional studios bottom line is getting impacted. Studios and distributors have heard about data science and AI and are wondering if technology can help them in to understand the dynamics of movie numbers. They have hired a new Data Science CEO, Harold.

Harold, who is representing the Movie Studio and Distributors has approached CDA (Central Data Agency) to help them out to do analysis on what factors are more likely to contribute to the success of a movie. Success of movie is defined as having earnings higher then the budget.

CDA has assigned the job to MDB (Movie Data busters) team within the organization who are movie enthusiasts and are experts in the art and science of Data. MDB team using Lean concepts have divided the work in multiple milestones. They are calling it HUD, Hollywood usable deliverables. MDB team shall be using various libraries of Python do to the EDA work and come up with initial recommendations.

MDB team is aware that the initial data set may not be good enough to provide the final answer but will direct in the right direction. MDB team will have to eventually scrap more data and do transformations and using machine learning techniques to overcome the obstacles and be the \*\*HERO \*\* for Harold.

HUD -1 answers the following key questions.

1.  Compare total box office compared to average price relationship. -Tyler
    
2.  Which genre grosses the higher for each studio? Show statistics for each studio and genre. -Gregg
    
3.  Top 5 Actors and Directors with highest grossing movies - Rochelle
    
4.  Poster vs grossing revenue relationship. -Tyler
    
5.  Generate ROI for the movies? -GP
    
6.  Facebook like compared to earnings? -GP
    
7.  MPAA Ratings vs Earnings comparison? -Rochelle
    
8.  Correlation between IMDB score and Earnings? -GP
    

***Methodology section***

*Data Source*
[Hollywood Theatrical Market Synopsis 1995 to 2021 | Kaggle](https://www.kaggle.com/johnharshith/hollywood-theatrical-market-synopsis-1995-to-2021)

*Context*

This Dataset contains the data of market analysis built on The Numbers unique categorization system, which uses 6 different criteria to identify a movie. All movies released since 1995 are categorized according to the following attributes: Creative type (factual, contemporary fiction, fantasy etc.), Source (book, play, original screenplay etc.), Genre (drama, horror, documentary etc.), MPAA rating, Production method (live action, digital animation etc.) and Distributor. In order to provide a fair comparison between movies released in different years, all rankings are based on ticket sales, which are calculated using average ticket prices announced by the MPAA in their annual state of the industry report.

[IMDB 5000 Movie Dataset | Kaggle](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)

*Context*

The dataset is from Kaggle website. It contains 28 variables for 5043 movies, spanning across 100 years in 66 countries. There are 2399 unique director names, and thousands of actors/actresses. “imdb_score” is the response variable while the other 27 variables are possible predictors.

*EDA*

In this project, we sought to understand patterns affecting movie profitability, see how popular genres change over years, identify important actors and directors, and observe changes in movie ratings and vote averages over time.

We shall be using Python Pandas to do the exploratory data analysis and pyviz framework for visualization. We shall also be using EDA tools like Pandas profiling, Sweetviz and D-Tale to help us in quick summary statistics before and after data cleaning. These tools will help us in visualizing basic relationships between features of the data set.

Sweetviz especially allows  us to define a target variable and visualize the correlation of other features to the target variable.

Plotly express and matplotlib is being used to present advances visualizations like scatter matrix and box plot.

***Future Work***

In next phase we would be adding more data sets such as -

- How much of the budget is for advertising and does it impact the earnings?
- Has OTT impacted box office?
- Can we use trend analysis on social media to assess the success of the movie?

***References***

*D-Tale**: [man-group/dtale: Visualizer for pandas data structures (github.com)](https://github.com/man-group/dtale)\*\*\*

SweetViz: [sweetviz · PyPI](https://pypi.org/project/sweetviz/)

Pandas Profiling: [pandas-profiling/pandas-profiling: Create HTML profiling reports from pandas DataFrame objects (github.com)](https://github.com/pandas-profiling/pandas-profiling)

[Big Data and Hollywood: A Love Story - IBM - The Atlantic Sponsor Content](https://www.theatlantic.com/sponsored/ibm-transformation-of-business/big-data-and-hollywood-a-love-story/277/): It could be just CDA might become a reality :-)

3.  ***Team***
    Gurpratap Singh
    Tyler
    Rochelle
    Gregg

5.***Acknowledgements***

Kaggle for providing us the data sets.

Our Coach and guide Dave and Nate who are always there providing guidance and expert advice.