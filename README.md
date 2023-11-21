# Practicum-TripleTen-Data-Analytics-Portfolio 
#### by Jonathan Chan Mun Heng
<br>
Welcome to my Data Analytics Portfolio.
This repository showcases a collection of data analytics projects completed as part of the Practicum/TripleTen data analysis course by Yandex. 

These projects exhibit cumulative proficiency, focusing on various aspects of data analysis.
This includes the Python language and a heavy emphasis on the Pandas library, data preprocessing, statistical analysis, 
exploratory data analysis and visualization (matplotlib, seaborn, plotly, etc.), features engineering, predictive modelling, Tableau and SQL amongst others. 

### <u>Projects Overview</u>
1. **Python Basics and Data Preprocessing**
<br>Title: *"Analyzing music preferences and user behaviours between 2 cities."*
   - Standardizing column names and its values. 
   - Missing value and duplicate treatment.
   - Testing basic hypotheses with user-defined functions.
<br><br>

2. **Data Preprocessing (cont.)**
<br>Title: *"Exploring borrowers' (bank customers) risk of defaulting." - 
Perusing available customer data on credit worthiness to establish main criteria(s) for future loan approvals.*
   - Missing values - Establishing if missing values are random (collection error) or interdependence between other column(s).
   - Illogical values - Processing column values that do not make sense. Example: negative duration of 'days_employed'.
   - Replacing missing values - Filling missing values with averages (mean/median). Example: missing values in the columns 'days_employed" & 'total_income'
     can be estimated by getting an approximate average from non-null values based off of 'education_level' and 'age_group'.
   - Categorizing data - Transforming categorical and numerical data into readable and succint groups. Example: converting 'total_income'.
     which is a continuous numeric column into income groups.
   - Testing average default rates of varying distinct customer profiles.
<br><br>

3. **Exploratory Data Analysis (EDA)**
<br>Title: *"Vehicle price study." -
Assessing the contributing factors that dictate vehicle pricings on a used-vehicle website.*
   - Extracting date-time objects 
   - Features Engineering - Constructing new core features for further analysis and visualization, such as 'age', 'mileage', 'vehicle_condition'.
   - Visualizing feature distribution via histrograms and bar charts; spotting outliers.
   - Treating outliers via boxplots/whisker-plots; determining upper and lower limits via interquartile ranges.
   - Determining viable price factors by visualizing price distribution for each selected feature's unique values, while testing for correlation; 
     This was accomplished with boxplots and correlation matrices.
<br><br>

4. **Statistical Data Analysis**
<br>Title: *"Performance (revenue) comparisons between a communication service provider's two prepaid plans." - 
Establishing the more profitable prepaid plan towards future marketing budget allocation*
   - Working with multiple DataFrames and feature engineering information that is needed.
   - Aggregation with pivot tables; finding monthly usage rates, surcharges, etc.
   - Visualizing user behaviour between both plans, such as sign-up dates, average duration of calls and average volume of data used.
   - Comparing average monthly revenue.
   - Statistical hypothesis testing 1. - Performing a T-Test to establish if the revenue differences observed by both plans indeed differ from one another.
   - Statistical hypothesis testing 2. - Performing a T-Test to etablish if revenue differs when observing a bigger region compared to all other regions. 
<br><br>

5. **Integrated Project 1.**
<br>Title: *"Video game forecasts for an online game store" - 
Determining the most profitable gaming platforms and genres for varying geographical regions, which will allow for more prudent use of future marketing budget.*
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
<br>Title: *"Ride-share analysis (i.e., Uber, Grab)" - 
Analyzing ride patterns, user behaviour/preferences and weather effects in terms of ride-hailing services across the Chicago area.*
   - Preprocessing datetime objects.
   - Extracting (querying) and visualizing top locations and ride-hailing companies across Chicago.
   - General assumptions about why certain ride-hailing companies severely outperform others.
   - Hypothesis testing - Assessing if average duration of rides from the busiest part of Chicago to the largest airport (Loop - O'Hare International Airport)
     changes during Saturdays with bad weather.
<br><br>

7. **Business Analytics** 
<br>Title: *"Marketing Expense Optimization for an events booking platform (i.e., Klook, Eventbee, Showpass)" - 
Studying business metrics such as user activity, retention rates, conversion rates, purchase volume & size, ad-expenditure, CAC and ROI.*
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
<br>Title: *"A/B test study on website recommendation blocks" - 
Studying the feasibility of adding recommendation blocks to an e-commerce website, with the goal of chanelling more 
visitors down the marketing funnel.*
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
<br>Title: *Robot-run Cafe" - 
Studying the feasibility of opening a wholly robot-run cafe in downtown Los Angeles using interactable visualizations and regular expressions.*
    - **N.B.** - The use of Seaborn and Plotly Express libraries together with Plotly Graph Objects were 
     the main focus of this project. Additionally, Regular Expressions (regex) was used for extraction/filtering of useable data.
    - Constructing interactable pie charts for visualizing proportion share of restaurant types (type of food) as well as establishment types (chain vs non-chain).
    - Bargraphs to visualize percentage share of restaurant type for chain restaurants only (deemed profitable).
    - Scatterplots to study the relationship between the average no. of seats and average no. of outlets pertaining to a certain brand.
    - Boxplots pertaining to the number of seats by restaurant type; i.e., which cuisine brings in the most number of customers.
    - Regex used to extract popular street names to study the most popular locations in LA according to street-restaurant density.
    - Consolidation of streets into groups for interpretability based on ranges of their restaurant density.
<br><br>

10. **Event-Based Analytics: The Events Funnel**
<br>Title: *"Food-produce app: Testing the effects of an app's font changes on the user journey (behaviour)." - 
Using an A/A/B test (2 control groups) to study the viability of introducing an entirely new font across the entire application, with the goal of
maintaining and improving the overall health of the events funnel.*
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
<br>Title: *"Youtube trends report." - 
Constructing a dashboard on Tableau that automates visualizations of trends regarding Youtube videos across different regions
and video categories. Subsequently, generating a report on current trends across the available timeframe.
    - Area chart on highest trending video categories in absolute terms across the past 1.5 years.
    - Area chart on highest trending video categories in relative terms across the past 1.5 years.
    - Pie chart regarding the relative proportion/distribution of trending videos across all major regions studied.
    - Absolute count on highest trending video categories by each major regions studied.
<br><br>
    
12. **Machine Learning: Forecasts and Predictions**
<br>Title: *"Food-produce app: Testing the effects of an app's font changes on the user journey (behaviour)." - 
Using an A/A/B test (2 control groups) to study the viability of introducing an entirely new font across the entire application, with the goal of
maintaining and improving the overall health of the events funnel.*
    - Ensuring equality of data proportions (sample size equality) by visualizing the frequency distribution of events across 
      time periods for the purpose of an A/B test.
      * Histograms and lineplot visualizations.
<br><br>
13. fdfdf
<br>Title: *"Food-produce app: Testing the effects of an app's font changes on the user journey (behaviour)." - 
Using an A/A/B test (2 control groups) to study the viability of introducing an entirely new font across the entire application, with the goal of
maintaining and improving the overall health of the events funnel.*
    - Ensuring equality of data proportions (sample size equality) by visualizing the frequency distribution of events across 
      time periods for the purpose of an A/B test.
      * Histograms and lineplot visualizations.

