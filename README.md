

# Group 3 - Project 1 Proposal


# The Fintech Hotels


## Proposal Requirements:

**<span style="text-decoration:underline;">The kind of data we'd like to work with and the field you're interested in:</span>**

Neil is active in the hospitality industry and found a great dataset around two hotels (one inside the city and another which is a resort). This dataset has a lot of data on both stays and the guests' characteristics. It also has significant economic data to correlate hotel activity with overall economic health. For this presentation, we assume the location is Miami, and the hotels are named “Miami - Resort Sea Sand” and “Miami -  Citylife Hotel“.

**<span style="text-decoration:underline;">The kinds of questions we'll be asking of that data:</span>**



1. In which season do the hotels generate the most revenue?
2. In which season do the hotels generate the least revenue?
3. What is the ADR (Average Daily Rate) for a given week? 
4. When do guests reserve their stay?
5. What is the average Check-is in a week?
6. Which is the best market segment (Direct, Corporate, Online Travel Agent) for how guests book their stays?
7. How do overall economic factors impact hotel stays and guests?

 

**<span style="text-decoration:underline;">Why do we want to answer these questions? </span>**



* Goal 1 - Compare yearly data to look for revenue growth and forecast future revenue
* Goal 2 - Reduce cancellations (what are the circumstances - gas prices, major events?)
* Goal 3 (presentation time permitting) - Which hotel should we invest in for the future? City vs. Resort
* Goal 4 (presentation time permitting) - Optimize Promotions for the hotels
    * We will use this data to understand better <span style="text-decoration:underline;">when and where</span> we should generate more promotions and when not to generate promotions.
* Goal 5 (Likely to be cut for time) - Target weekly bookings goal over the year
    * How many rooms do you want to book per week or day ahead of time vs. walk-ins? 


## Sources for data:

[Hotel Booking Demand with Economic Indicators (kaggle.com)](https://www.kaggle.com/datasets/mlardi/hotel-booking-demand-with-economic-indicators)

[Major Events in 2014](https://www.discoverwalks.com/blog/world/15-major-historical-events-that-happened-in-2014/)



**<span style="text-decoration:underline;">Work breakdown for the Team:</span>**



1. Data import into Pandas (Jason Brunsell)
    1. Import CSV
    2. Rename columns for readability
    3. Convert dates to DateTime format
    4. Identify outliers in the data
    5. Decide whether to eliminate or subgroup outliers
2. Analyze data for Goal 1 - Compare yearly data to look for revenue growth and forecast future revenue (Neil Baride)
    6. Plot revenue over the timeframe provided
    7. Use ARIMA to forecast future revenue growth with seasonality
    8. Generate helpful graphs to demonstrate future revenue
3. Analyze data for Goal 2 - Reduce cancellations (Michael Colbert)
    9. Identify likely relationships with variables provided
    10. Analyze the cancellations rate as a function of likely inputs
    11. Suggest variables that could impact the cancellation rate and solutions
    12. Generate helpful graphs to demonstrate understanding and talk about improvements
4. Analyze data for Goal 3 - Which hotel should we invest in for the future? City vs. Resort (Jett Acuna)
    13. Use revenue forecasts to identify the better candidate for investment
5. Analyze data for Goal 4 - Optimize Promotions for the hotels (Jason Brunsell)
    14. Identify likely relationships with variables provided
    15. Analyze when the hotels have lower occupancy
    16. Analyze how far ahead to promote to get bookings
    17. Calculate when to do promotions
    18. Generate helpful graphs to demonstrate understanding and talk about improvements
6. Analyze data for Goal 5 - Target weekly bookings goal over the year (Likely to be cut for time)
    19. Identify likely relationships with variables provided
    20. Analyze the occupancy rate over the year
    21. Calculate possible bookings goals over the year
    22. Generate helpful graphs to demonstrate understanding and talk about seasonality
7. Presentation
    23. Motivation & Summary Slide (Michael Colbert)
    24. Questions/Goals & Data (Neil Baride)
    25. Data Cleanup & Exploration (Jason Brunsell)
    26. Data Analysis/Discussion  (Each person on their Analysis Goal #)
    27. Postmortem (Jett Acuna)
    28. Q&A (Team)


# Information from the Project Assignment Documents:


## Technical Requirements:



* Use Pandas to clean and format your dataset(s).
* Create a Jupyter Notebook describing the **data exploration and cleanup** process.
* Create a Jupyter Notebook illustrating the **final data analysis**.
* Use Hvplot or GeoViews to create six to eight data visualizations (ideally, at least two per question asked of the data).
    * Save PNG images of your visualizations to distribute to the class and instructional team and for inclusion in your presentation and your repo's README.md file.
* Use one new Python library that hasn't been covered in class.
* Optionally, use at least one API, if you can find an API with data pertinent to your primary research questions.
* Create a README.md in your repo with a write-up summarizing your major findings. This should include a heading for each question you asked of your data and, under each heading, a short description of what you found and any relevant plots.


## Presentation Requirements:



* Title Slide
    * Include the name of the project and group members.
* Motivation & Summary Slide
    * Define the core message or hypothesis of your project.
    * Describe the questions you asked, and _why_ you asked them.
    * Describe whether you were able to answer these questions to your satisfaction, and briefly summarize your findings.
* Questions & Data
    * Elaborate on the questions you asked, describing what kinds of data you needed to answer them and where you found it.
* Data Cleanup & Exploration
    * Describe the exploration and cleanup process.
    * Discuss insights you had while exploring the data that you didn't anticipate.
    * Discuss any problems that arose after exploring the data, and how you resolved them.
    * Present and discuss interesting figures developed during exploration, ideally with the help of Jupyter Notebook.
* Data Analysis
    * Discuss the steps you took to analyze the data and answer each question you asked in your proposal.
    * Present and discuss interesting figures developed during analysis, ideally with the help of Jupyter Notebook.
* Discussion
    * Discuss your findings. Did you find what you expected to find? If not, why not? What inferences or general conclusions can you draw from your analysis?
* Postmortem
    * Discuss any difficulties that arose, and how you dealt with them.
    * Discuss any additional questions that came up that you didn't have time to answer: What would you research next, if you had two more weeks?
* Questions
    * Open-floor Q&A with the audience
