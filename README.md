# Practicum-TripleTen-Data-Analytics-Portfolio 
#### by Jonathan Chan Mun Heng
<br>
Welcome to my Data Analytics Portfolio.
This repository showcases a collection of data analytics projects completed as part of the Practicum/TripleTen data analysis course by Yandex. 

These projects exhibit cumulative proficiency, focusing on various aspects of data analysis.
This includes the Python language and a heavy emphasis on the Pandas library, data preprocessing, statistical analysis, 
exploratory data analysis and visualization (matplotlib, seaborn, plotly, etc.), features engineering, predictive modelling 
(machine learning), Tableau and SQL amongst others. 

### <u>Projects Overview</u>
1. **Python Basics and Data Preprocessing**
<br> **Title:** *"Analyzing Music Preferences And User Behaviours Between 2 Cities."*
   - Standardizing column names and its values. 
   - Missing value and duplicate treatment.
   - Testing basic hypotheses with user-defined functions.
<br><br>

2. **Data Preprocessing (cont.)**
<br> **Title:** "*Exploring Bank Borrowers' Risk Of Defaulting*." - 
Perusing available customer data on credit worthiness to establish main criteria(s) for future loan approvals.
   - Missing values - Establishing if missing values are random (collection error) or interdependence between other column(s).
   - Illogical values - Processing column values that do not make sense. Example: negative duration of 'days_employed'.
   - Replacing missing values - Filling missing values with averages (mean/median). Example: missing values in the columns 'days_employed" & 'total_income'
     can be estimated by getting an approximate average from non-null values based off of 'education_level' and 'age_group'.
   - Categorizing data - Transforming categorical and numerical data into readable and succint groups. Example: converting 'total_income'.
     which is a continuous numeric column into income groups.
   - Testing average default rates of varying distinct customer profiles.
<br><br>

3. **Exploratory Data Analysis (EDA)**
<br> **Title:** *"Used Vehicle Price Study." -  
Assessing the contributing factors that dictate vehicle pricings on a used-vehicle website.*
   - Extracting date-time objects 
   - Features Engineering - Constructing new core features for further analysis and visualization, such as 'age', 'mileage', 'vehicle_condition'.
   - Visualizing feature distribution via histrograms and bar charts; spotting outliers.
   - Treating outliers via boxplots/whisker-plots; determining upper and lower limits via interquartile ranges.
   - Determining viable price factors by visualizing price distribution for each selected feature's unique values, while testing for correlation; 
     This was accomplished with boxplots and correlation matrices.
<br><br>

4. **Statistical Data Analysis**
<br> **Title:** *"Performance Comparisons Between A Communication Service Provider's Prepaid Plans.*" -
Establishing the more profitable prepaid plan towards future marketing budget allocation.
   - Working with multiple DataFrames and feature engineering information that is needed.
   - Aggregation with pivot tables; finding monthly usage rates, surcharges, etc.
   - Visualizing user behaviour between both plans, such as sign-up dates, average duration of calls and average volume of data used.
   - Comparing average monthly revenue.
   - Statistical hypothesis testing 1. - Performing a T-Test to establish if the revenue differences observed by both plans indeed differ from one another.
   - Statistical hypothesis testing 2. - Performing a T-Test to etablish if revenue differs when observing a bigger region compared to all other regions. 
<br><br>

5. **INTEGRATED PROJECT 1 - A Culmination Of Data Preprocessing, EDA and Statistical Data Analysis** 
<br> **Title:** *"Video Game Forecasts For An Online Game Store"* - 
Determining the most profitable gaming platforms and genres for varying geographical regions, which will allow for more prudent use of future marketing budget.
   - Determining the period of study for historical analysis.
   - Visualizing overall total sales by platform (PlayStation, Xbox, etc.), for each of the last 4 years.
   - Assessing the correlation between user scores and critic scores with overall total sales recorded; Scatterplot together with Pearson's Correlation Coefficient.
   - Comparing best-selling game franchises that are outliers in nature - visualizing how they were distributed amongst the many gaming platforms (cross-platform types).
   - Comparing the total game sales across each genre using boxplots - visualizing which genre(s) not only had the best average numbers, but also the most outliers (best-selling games).
   - Visualizing the normalized share of top 5 games by platform and genre for each main region of study (NA, EU, JP) 
   - Assessing the correlation between *Entertainment Software Rating Board* (ESRB) ratings and region sales.
   - Hypothesis testing 1 - Establishing if user scores are different between the Xbox One (one of the most popular game consoles) and PC (widely used gaming platform for the masses).
   - Hypothesis testing 2 - Establishing if user scores are different between two of the most popular gaming genres, Action and Sports.
<br><br>

6. **Statistical Data Analysis (cont.)**
<br> **Title:** *"Ride-Share Analysis (i.e., Uber, Grab)" - 
Analyzing ride patterns, user behaviour/preferences and weather effects in terms of ride-hailing services across the Chicago area.*
   - Preprocessing datetime objects.
   - Extracting (querying) and visualizing top locations and ride-hailing companies across Chicago.
   - General assumptions about why certain ride-hailing companies severely outperform others.
   - Hypothesis testing - Assessing if average duration of rides from the busiest part of Chicago to the largest airport (Loop - O'Hare International Airport)
     changes during Saturdays with bad weather.
<br><br>

7. **Business Analytics** 
<br> **Title:** *"Marketing Expense Optimization For An Events Booking Platform (i.e., Klook, Eventbee, Showpass)"* - 
Studying business metrics such as user activity, retention rates, conversion rates, purchase volume & size, ad-expenditure, CAC and ROI.
   - User Metrics 
      * User activity - Calculating active users by month, week and day (MAU, WAU, DAU)
      * User sessions - Calculating the average daily visits to the website and consequently, the average duration of a typical session.
      * User retention rates - Performing cohort analysis based on the month a user visited the website for the first time.
   - Sales Metrics
      * Conversion time delta - Visualizing the average delta between first visit and conversion (first purchase)
      * Order volume - Visualizing order volume by conversion groups (less than/more than 10 days) and by first-visit-month cohorts. Alternatively, studied order volume by each unique ad-source.
      * Average purchase size - Visualizing purchase size by first-order-month cohorts across its lifetime. Alternatively, studied average purchase size by the device used and each unique ad-source.
      * Lifetime value (LTV) - Calculating gross profit and number of unique buyers for each first-order-month cohort; heatmap visualization of LTV across the lifetime of each cohort.
   - Marketing Metrics
      * Ad expenditure - Observing total expenditure by unique ad-source. Also visualizing a lineplot of cost/revenue over time (1-year period).
      * Customer acquisition cost (CAC) - Calculating total marketing costs and total unique buyers for each distinct ad-source.
      * Return on marketing investment (ROMI) - Using LTV and CAC to find out ROMI for each ad-source.
   - Conclusions
      * Optimization suggestions on which device(s) and ad-source(s) to focus marketing budget on, while highlighting futile avenues to cut cost in.
<br><br>

8. **Making Business Decisions (A/B Testing)** 
<br> **Title:** *"A/B Test Study On Website Recommendation Blocks"* - 
Studying the viability of adding recommendation blocks to an e-commerce website, with the goal of chanelling more 
visitors down the marketing funnel.
   - Hypothesis prioritization using the ICE/RICE Framework
      * Ranking importance of hypotheses based on *Reach - Impact - Confidence - Effort* parameters.  
   - A/B test analysis
      * Aggregating cumulative data for both test groups, grouped by each date of the A/B test duration.
      * Visualizing(line plot) cumulative revenue and average order size between test groups across the test duration; 
        subsequently plotting a relative-difference graph on cumulative average order size for the test group against the control group.
      * Visualizing(line plot) cumulative conversion rate between test groups across the test duration; 
        subsequently plotting a relative-difference graph on cumulative conversion rate for the test group against the control group.
      * Spotting outliers for *number-of-orders-per-visitor* and *order-size-per-transaction* using scatterplots and percentile values. 
        This may explain any spikes in our cumulative graphs.
      * Hypothesis testing on raw data - Mann-Whitney U Test (MWU) was used (because of the presence of outliers) to test for 
        statistical significance of difference in both conversion rates and average order size between groups.
      * Hypothesis testing on filtered data - Outliers were removed using percentile benchmarks; MWU was re-run while 
        comparing P-values and Relative Difference values of both raw and filtered data.
      * Stabillity testing to prevent the *Peeking Problem*.
<br><br>

9. **Data Storytelling: A Deeper Look Into Graphs And Visualization**
<br> **Title:** *Robot-Run Cafe"* - 
Studying the feasibility of opening a wholly robot-run cafe in downtown Los Angeles using interactable 
visualizations and regular expressions.
    - The use of Seaborn and Plotly Express libraries together with Plotly Graph Objects were 
     the main focus of this project. Additionally, Regular Expressions (regex) was used for extraction/filtering of useable data.
    - Constructing interactable pie charts for visualizing proportion share of restaurant types (type of food) as well as establishment types (chain vs non-chain).
    - Bargraphs to visualize percentage share of restaurant type for chain restaurants only (deemed profitable).
    - Scatterplots to study the relationship between the average no. of seats and average no. of outlets pertaining to a certain brand.
    - Boxplots pertaining to the number of seats by restaurant type; i.e., which cuisine brings in the most number of customers.
    - Regex used to extract popular street names to study the most popular locations in LA according to street-restaurant density.
    - Consolidation of streets into groups for interpretability based on ranges of their restaurant density.
<br><br>

10. **INTEGRATED PROJECT 2 - Event Based Analytics And The Events Funnel**
<br> **Title:** *"Food-Produce App: Testing Effects Of An App's Font Changes On The User Journey."* - 
Using an A/A/B test (2 control groups) to study the viability of introducing an entirely new font across the entire application, with the goal of
maintaining and improving the overall health of the events funnel.
    - Ensuring equality of data proportions (sample size equality) by visualizing the frequency distribution of events across 
      time periods for the purpose of an A/B test.
      * Histograms and lineplot visualizations.
      * Filtering only for time periods that contains substantial data density.
      * Ensuring an equal (approximate) representation of unique users across each A/A/B test group.
    - Events funnel study.
      * Itemizing possible event funnel sequences by calculating event frequency, unique users and user proportions
        at each event stage.
      * Visualizing the funnel using Plotly Express funnel plots.
      * Calculating the conversion rates (total and stage-to-stage) of each funnel event.
      * Highlighting the stages of the funnel that have traction and those that are losing customers.
    - A/A/B study.
      * Ensuring user distribution/share equality amongst experiment groups.
      * Constructing a function to perform a *two-proportion Z-test*.
      * Testing for statistically significant differences in conversion-rates and user-proportions-by-event
        between both control groups (A/A) using *two-proportion Z-tests*. This is to ensure data collection was 
        performed correctly and that both sets of users pertain to the same population sample.
      * Re-running our *two-proportion Z-test* on conversion rates and user proportions for the test group (A/B).
    - Conclusions.
      * Establishing if the font-change had a detrimental or positive effect on the user journey (user behaviour).
      * Recommendations on funnel stages that can be improved on (low conversion rates).
<br><br>

11. **Automation, Dashboards and Tableau**
<br> **Title:** *"Youtube Trends Report."* - 
Constructing a dashboard on Tableau that automates visualizations of trends regarding Youtube videos across different regions
and video categories. Subsequently, generating a report on current trends across the available timeframe.
    - Area chart on highest trending video categories in absolute terms across the past 1.5 years.
    - Area chart on highest trending video categories in relative terms across the past 1.5 years.
    - Pie chart regarding the relative proportion/distribution of trending videos across all major regions studied.
    - Sortable table on absolute count of highest trending video categories by each major regions studied.
<br><br>
    
12. **Machine Learning: Forecasts and Predictions**
<br> **Title:** *"Customer Retention Study For A Fitness Gym."* - 
Breaking down customer profiles and behavioural trends using historical data with the aim towards predicting churn rates and ultimately, 
constructing a feasible customer retention strategy for the future. Both supervised and unsupervised learning models are used.
    - Exploratory data analysis.
      * Visualizing feature distribution between churn vs non-churn customers - this aids in determining if certain 
      features are good/bad churn indicators.
      * Observing feature correlation using Spearman's Correlation Matrix with the goal to avoid any feature-collinearity.
    - Predictive Modelling (supervised learning) - Using historical data to train classification models for the
      prediction of future churn rates.
      * <u>Logistic Regression</u> (LR) 
        * Training and comparing a baseline LR model together with an LR model optimized for L2 Ridge regularization; this
          is to avoid overfitting and multicollinearity. Classification metrics such as *accuracy, 
          precision, recall, F1 and roc_auc* are used for model comparisons.
        * Constructing a Confusion Matrix to assess the quality of our model in terms of minimizing *false positives* and 
          *false negatives*.
        * Visualizing the model's feature coefficients - This tells us the best churn indicators by measuring the *impact*
          of each feature in contrast to one another.
      * <u>Random Forest</u> (RF)  
        * Training and comparing a baseline RF model together with an RSCV-optimized RF model to avoid overfitting 
          and multicollinearity. Similarly, classification metrics are used to assess the quality of an optimized model.
        * Visualizing the RF model's order of feature importance.
        * Classification metrics between the Logistic Regression and Random Forest models are used to determine
      the best model for the task. Additionally, LR impact coefficients and RF feature importance values are 
      compared to determine the overall best churn indicators.
    - User Clustering (unsupervised learning) - Segmenting users based on available features for the purpose of targeted 
      marketing and retention strategies.
      * <u>Hierarchical Clustering</u> - to estimate optimal number of clusters.
        * Standardizing all feature values to the same scale.
        * Constructing a dendogram based on a linkage matrix of features - This gives an approximate guideline for a K-Means model.
      * <u>K-Means Algorithm</u> - as a prediction model.
        * Calculate K-Means inertia and silhouette scores for a range of *n*-clusters.
        * Visualizing the various inertia and silhouette scores as data points on a dual-axis line plot.
        * Determine the optimal clusters (*n*) for K-Means computation based on the inertia plot's elbow point
          and the highest possible silhouette score.
        * Training the K-Means model based on the optimal number of clusters.
        * The clusters are sorted in order of their churn rates; all features are then plotted individually to visualize
          user cluster distribution.
    - Conclusions
      * Target clusters are established as the groups of customers to target in marketing and retention initiatives.
      * Recommendations are provided based around personalization, digital engagement/brand reinforcement 
        and promotional incentives.
<br><br>

13. **CAPSTONE PROJECT - Part 1** (This project is intended to simulate a real-world project environment with a business client.)
<br> **Title:** *"Customer Segmentation For An E-commerce Website."* - An E-commerce platform dealing in household goods
has a need to personalize unique offerings to distinct customer 
profiles of their customer base. The client does not have personal and demographic data at their disposal, hence
website transactional data is used for segmenting purposes.
    - Project Decomposition
      * Project perliminaries with client - this involves establishing the problem statement, success indicators,
        time period of study, gap analysis, key end users and key decisions resulting to the study, amongst others.
      * Generating a list of preliminary hypotheses to be tested across the timeframe of the study.
      * Specifying and requesting required data for analysis.
      * Presenting project stage deliverables to the client and their respective completion timeframes.

    - Data Preprocessing
      * Missing value and duplicates treatment
      * Investigating extreme values - Example, unit prices valued at $0.00 (discounts?) and 
        amounts purchased with negative values (returns?). 

    - Exploratory Data Analysis (EDA)
      * Filtering out timeframes (months) with disproportionaly low sample size.
      * Spotting outliers by studying frequency distribution of basket size and purchase value metrics.
      * Visualizing seasonal purchase trends by studying business metrics across months.
      * Studying business metrics across the days of the week.
      * Testing the correlation between transaction time-delta and repeat purchase frequency -
        Jointplot and Spearman's Correlation Coefficient.
      * Testing the correlation of first-month purchase frequency being a good indicator of
        future purchase frequency - Contingency Tables and Chi Test.
      * Studying the correlation/impact of purchase frequency, purchase value and basket size on Lifetime Value.
      * Feature engineering Price Sensitivity based on percentile values.
        * > Overall for the purpose of clustering/segmentation, this section has produced engineered features of
            *Seasonal Shoppers, Transaction Time Delta, Average Purchase Value, Average Purchase Frequency,
            Average Basket Size, Lifetime Value (LTV) and Price Sensitivity*.

    - Recency, Frequency, Monetary (RFM) Segmentation
      * Constructing an aggregated RFM table based on invoice dates, revenue and unique customer Id's.
      * Segmenting customers based on feature quantiles and assigning unique identifiers from a range of 1-4.
      * Extracting specific combinations of RFM scores that could be potential highlight points for the client.
        For example, a score of '444' are the best and most profitable customers, while a score of '111' are lost
        customers who were cheap spending-wise.
        * > The RFM model is inherently able to produce many more segment types, such is the nature of the attributes
            subjected to the model; this allows the client to attain a more granular view on their customer base. As such, 
            a Tableau dashboard is provided for this purpose that displays visualizations of *Segment Proportion of Total Customers (%), 
            RFM Metric Averages, Revenue Over Time and Business Metrics by Unique Customer ID's*. Otherwise, the K-Means 
            model summarized below may be used for a higher-level perspective.
    - K-Means Clustering (segmentation by machine learning)
      * Correlation Matrix using Spearman's Coefficient for feature set selection and avoidance of multicollinearity.
      * Hierarchical clustering for estimation of *k*-clusters. 
      * Optimizing *k*-clusters by calculating simultaneuous inertia and silhouette scores for a range of possible cluster values.
      * Visualizing inertia and silhouette scores across a lineplot to find the optimal elbow point that coincides 
        with highest achievable silhouette score.
      * Training our K-Means algorithm and sorting our clusters (segments) according to Lifetime Value (LTV).
      * Visualizing each feature's segment/cluster distribution using various strip plots and bar charts, 
        and concluding what this means for targeted/personalized marketing.
<br><br>

14. **CAPSTONE PROJECT - Part 2** (This project aims to simulate a real-world situation of assessing the quality of an on-going A/B test)
<br> **Title:** *"Improved Recommentation System For An Online Store."* - This study aims to test the viability of adding an 
improved recommendation system and subsequently an altogether new payment funnel to an online store using events funnel analysis. 
    - Data Preprocessing and Cleaning Noisy/Bad Data
      * Removing unique users who were inadvertantly part of 2 concurrent A/B tests as this create misrepresentation of the population.
      * Filtering for unique users and events that pertain to the correct A/B test.
      * Filtering for unique users from only specific regions of study. 
      * Ensuring users and events are within the test period.
      * Filtering out events that falls beyond the maximum observation window (14 day test period).
      * Checking for an equal distribution of users between both experiment groups.
    - EDA and Events Funnel Analysis
      * Calculating total conversion and next stage conversion rates.
      * Constructing an events funnel for each of our experiment groups.
      * Visualizing and comparing average events per day between groups.
      * Investigating if there are any ongoing promotions that may cause misrepresentation for our test.
    - A/B Test Results
      * Conducting 2-proportion Z-tests to ascertain if there is a statistically significant difference in proportion of events 
        and conversion proportions between control and test groups. This will confirm if the A/B test participants were split correctly.
      * Testing for stability in cumulative conversion rates between both experiment groups; an unstable horizontal lineplot
        with frequent spikes and fluctuations tell us an A/B test was run for too short a time-period (ended prematurely).
    - Conclusions
      * Recommendations on ensuring neutrality (non-promotional user behaviour), sufficient sample size, equality of 
        test-split and adequate time duration for the A/B test.
<br><br>

15. **CAPSTONE PROJECT - Part 3** 
<br> **Title:** *"SQL Study For A Book Reviews App."* - Using SQL Alchemy. 
    - Connecting to the database; using the necessary connection string with relevant database config attributes
      with sqlalchemy's create_engine method.
    - Selecting and printing all required tables, being "Books", "Authors", "Ratings", "Reviews" and "Publishers".
    - Creating a function to execute a query into a Dataframe.
    - Querying books starting from a particular date.
    - Calculating and joining total reviews and average ratings, grouped for each unique book Id and ordered descendingly.
    - Filtering books above a certain number of pages to eliminate brochures and similar publications; proceedingly,
      finding the publisher with the highest number of book releases.
    - Querying average rating by author, for books with at least a certain number of ratings.
    - Aggregate review counts for only users who rated books on a high-frequency basis; this 
      allows one to observe the behaviour of an avid book reader and reviewer.
<br><br>
 
