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
<br>Title: *"Performance (revenue) comparisons between a commuication service provider's two prepaid plans." - 
    Establishing the more profitable prepaid plan towards future marketing budget allocation*
   - Working with multiple DataFrames and feature engineering information that is needed.
   - Aggregation with pivot tables; finding monthly usage rates, surcharges, etc.
   - Visualizing user behaviour between both plans, such as sign-up dates, average duration of calls and average volume of data used.
   - Comparing average monthly revenue.
   - Statistical hypothesis testing 1. - Performing a T-Test to establish if the revenue differences observed by both plans indeed differ from one another.
   - Statistical hypothesis testing 2. - Performing a T-Test to etablish if revenue differs when observing a bigger region compared to all other regions.