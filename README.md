# Project Proposal

# Option 1: Music Trends Analysis
Description:
Analyze the evolution of music trends by collecting data from Spotify and Billboard. The project will explore how factors like artist popularity, genre shifts, and streaming numbers change over time.

Goal(s):

Primary Goal: Predict future music popularity trends (e.g., streaming counts or chart positions for artists/tracks).

Secondary Goal: Identify emerging genres or artists based on historical data trends.

Data Collection:

What Data: Artist names, track titles, genres, streaming counts, chart positions, release dates, etc.

How to Collect:
Use the Spotify API (via libraries like spotipy) to fetch current and historical streaming data.
Scrape Billboard charts using Python libraries such as requests and BeautifulSoup to extract chart positions and other metadata.

Modeling the Data:

Approaches:
Time Series Forecasting: Apply ARIMA or Facebook Prophet to predict future streaming numbers or chart positions.
Regression Models: Use linear or non-linear regression to relate features (e.g., social media mentions, historical performance) with future popularity.

Data Visualization:

Techniques:

Line Plots: To display trends in streaming counts and chart positions over time.

Scatter Plots: To compare relationships between different features (e.g., genre vs. streaming numbers).

Interactive Dashboards: Use tools like Plotly or Dash for dynamic exploration of trends.

Test Plan:

Approach:
Temporally split the data (e.g., train on data until a certain month and test on data from the subsequent month).
Reserve the last 20% of the time-series data as a holdout test set.
Evaluate performance using error metrics such as RMSE (Root Mean Squared Error) and MAE (Mean Absolute Error).

# Option 2: Student Wellbeing Poll

Description:
Evaluate mental health and wellbeing among college students by analyzing survey responses related to academic workload, sleep patterns, social activities, and stress levels.

Goal(s):

Primary Goal: Identify key factors that predict mental health outcomes.

Secondary Goal: Develop a predictive model to flag students who might be at risk based on their responses.

Data Collection:

What Data: Survey responses covering mental health indicators, academic stress, sleep duration, social activities, and demographic information.

How to Collect:
Distribute an online survey using platforms such as Google Forms or Qualtrics targeted at college students.
Ensure anonymity and ethical handling of sensitive data.

Modeling the Data:

Approaches:

Classification Models: Apply logistic regression or decision trees to classify students based on risk levels.

Regression Models: Predict continuous mental health scores.

Clustering: Identify subgroups within the student population with similar wellbeing profiles.

Data Visualization:

Techniques:

Bar Charts/Box Plots: To display the distribution of mental health scores and other survey responses.

Scatter Plots: To explore relationships between academic workload, sleep, and stress.

Interactive Dashboards: For detailed exploratory analysis using tools like Tableau or Plotly.

Test Plan:

Approach:
Randomly split the survey data into an 80/20 training/testing set.
Use cross-validation (e.g., k-fold) to ensure model robustness and to prevent overfitting.
