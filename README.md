# 01-data-science-for-business

# Welcome to Data Science for Business Part 1!
 
 Your Journey To Learning R For Business Starts Now! (2:33)
 
 ## Course Certificate - Instructions
 
 Private Slack Channel: How To Join
 
 Video Subtitles (Captions)
Prerequisites
 
 Prerequisites
Getting Help
 
 Getting Help (IMPORTANT!!!)
## Module 1: Jump Start
 
 ## Module 1 Overview (1:33)
## 1.1 Goal: Better Serving Customers With Data
 
 The Business Case (0:54)
## 1.2 What Tools Are In Our Toolbox?
 
 🔽 The ULTIMATE R Cheatsheet (File Download) (2:14)
 
 How To Use The ULTIMATE R Cheatsheet (2:39)
## 1.3 Data Science Project Setup
 
 Installing R & RStudio IDE, Part 1: Installing R (3:06)
 
 Installing R & RStudio IDE, Part 2: The RStudio IDE (3:03)
 
 RStudio IDE: Setup & Customization (5:40)
 
 🔽 Setting Up The Project (File Download) (2:38)
 
 Project Directory Structure & Contents (5:25)
 
 🔽 Installing R Packages (File Download) (11:47)
 
 Package Installation Checkpoint
## 1.4 Optional: Transactional Database Primer
 
 Who Should Watch This?
 
 Transactional Data: What Is It? What Will We Do With It In This Course? (1:41)
 
 🔽 Orders: The Building Blocks Of Transactional Data (File Download) (3:53)
 
 Database 101: The Entity Relationship Diagram (ERD) (2:14)
 
 Understanding Database Relationships (6:18)
## 1.5 Sales Analysis - Diving In!
 
 Read This! - Jumpstart Intent
 
 Overview (1:27)
 
 🔽 Setup (File Download) (4:40)
### 1.5.1 Sales Analysis, Part 1 - Importing, Examining, & Joining Data
 
 Importing Excel Files (6:18)
 
 Examining Data: Console, Data Window, glimpse() (4:27)
 
 Data Model (1:12)
 
 Joining Data, Part 1: Combining 2 Tibbles With left_join() (6:04)
 
 Joining Data, Part 2: Combining Multiple Tibbles With The Pipe (5:07)
 
 🔽 Code Checkpoint: Joining Data (File Download)
### 1.5.2 Sales Analysis, Part 2 - Wrangling Data With dplyr
 
 Wrangling Data Overview (3:00)
 
 Splitting Description Into Category 1, Category 2, & Frame Material: separate() (4:35)
 
 Splitting Location Into City & State: separate() (1:55)
 
 Adding Total Price Column: mutate() (2:41)
 
 Removing Unnecessary Columns: select() (3:59)
 
 Getting The Order ID Column Back: bind_cols() (2:34)
 
 Reordering Columns: select() (4:53)
 
 Renaming Columns: rename() & set_names() (5:28)
 
 Storing The Wrangled Data (1:10)
 
 🔽 Code Checkpoint: Wrangling Data (File Download)
### 1.5.3 Sales Analysis, Part 3 - Visualizing Data With ggplot2
 
 Sales Analysis Visualizations Overview (1:19)
 
 Sales By Year: Data Manipulation (7:23)
 
 Sales By Year: ggplot geometries (10:28)
 
 Sales By Year: ggplot2 formatting (5:45)
 
 Sales By Year & Category 2: Data Manipulation (7:11)
 
 Sales By Year & Category 2: ggplot geometries + facet_wrap (6:45)
 
 Sales By Year & Category 2: ggplot2 Formatting (5:38)
 
 🔽 Code Checkpoint: Visualizing Data (File Download)
### 1.5.4 Visualization Process & Saving Key Data
 
 🔽 Data Visualization Process (File Download) (1:38)
 
 Writing Files: Excel, CSV, RDS (7:32)
 
 🔽 Code Checkpoint: Writing Files (File Download)
# Module 2: Import & Data Wrangling Foundations (Level 1)
 
 ## Module 2 Overview (1:41)
Important Concepts Before Diving In
 
 🔽 Data Type & Structure Basics (File Download) (7:01)
 
 🔽 Tidy Data Primer (File Download) (8:20)
## 2.1 Importing Data: readr, readxl, odbc, & RSQLite
 
 Importing Data Overview (0:41)
 
 Data Import Cheatsheet (2:44)
 
 🔽 Setup (File Download) (2:04)
 
 CSV Files (7:35)
 
 CSV Files: Fixing Parsing Errors With Column Specifications (3:41)
 
 RDS Files (3:11)
 
 Excel Files (3:50)
 
 Database Connection Resources (2:39)
 
 Connecting To Databases: SQLite (8:13)
 
 🔽 Code Checkpoint: Importing Data (File Download)
## 2.2 Wrangling Data (Cleaning, Preparing, & Manipulating Data): dplyr & tidyr
 
 Data Wrangling Overview (1:41)
 
 🔽 Setup (File Download) (1:19)
 
 Data Wrangling Outline (2:19)
 
 Examining The Data (1:35)
### 2.2.1 Using The ULTIMATE R Cheatsheet For Data Wrangling
 
 Using The R Cheatsheet For Data Wrangling (5:10)
### 2.2.2 Working With Columns (Features)
 
 Selecting Columns: select() & select helpers (8:02)
 
 Pull Vectorized Contents: pull() (2:56)
 
 Select Data By Data Type: select_if() (3:31)
 
 Sorting Columns: arrange() (2:59)
 
 🔽 Code Checkpoint: select (File Download)
### 2.2.3 Working With Rows (Observations)
 
 Filtering Rows: filter() (5:58)
 
 Filtering Categorical Data: %in%, ==, and != (6:32)
 
 Filtering By Row Number: slice() (3:45)
 
 Filtering Unique Observations: distinct() (3:39)
 
 🔽 Code Checkpoint: filter (File Download)
### 2.2.4 Performing Feature-Based Calculations
 
 Adding Calculated Columns: mutate() (8:36)
 
 Binning Numeric Data: mutate() + ntile() (2:29)
 
 If-Then Statements Inside Mutate: mutate() + case_when() (9:40)
 
 🔽 Code Checkpoint: mutate (File Download)
### 2.2.5 Performing Summary Calculations, Analyzing Groups, & Renaming Columns for Presentation
 
 Aggregating Data: group_by() + summarize() (5:18)
 
 Summary Functions (5:48)
 
 Detecting & Handling Missing Values: summarize_all() & filter() (8:20)
 
 Renaming Columns for Presentation: Part1, rename() (4:59)
 
 Renaming Columns For Presentation, Part 2: set_names() (2:40)
 
 🔽 Code Checkpoint: summarize (File Download)
### 2.2.6 Reshaping Data (Pivoting)
 
 From Long To Wide Format: spread() (4:59)
 
 From Wide To Long: gather() (6:56)
 
 🔽 Code Checkpoint: Pivoting (File Download)
### 2.2.7 Combining Data (Joining & Binding)
 
 Joining Data: left_join() (4:59)
 
 Binding Data: bind_cols() & bind_rows() (6:05)
 
 🔽 Code Checkpoint: Combining Data (FIle Download)
### 2.2.8 Splitting & Combining Column Text
 
 Manipulating Text In Columns: separate() & unite() (7:26)
 
 🔽 Code Checkpoint: Splitting & Combining Text (File Download)
## 2.3 Module 2 Challenge
 
 🔽 Module 2 Challenge (File Download) (8:00)
 
 🔽 Module 2 Challenge - Solution (File Download) (10:42)
 
 Challenges: Organizing The Directory (2:49)
# Module 3: Data Wrangling Foundations (Level 2)
 
 Data Wrangling Level 2 Overview (2:02)
## 3.1 Time Series Fundamentals: lubridate
 
 Cheat Sheet: lubridate (3:37)
 
 🔽 Setup (File Download) (2:28)
 
 Date Basics (4:39)
 
 Character & Date Classes (5:05)
 
 Converters: lubridate basics part 1 (3:37)
 
 Extractors: lubridate basics, part 2 (4:30)
 
 Helpers: lubridate basics, part 3 (1:07)
 
 Periods & Durations: lubridate basics, part 4 (3:04)
 
 Intervals: lubridate basics, part 5 (5:35)
## 3.2 Time Series Analysis: Most Common Business Operations
 
 Time Series Aggregation: group_by() + summarize() (9:29)
 
 Time Series Aggregation: floor_date() (4:27)
 
 Measuring Change: lag(), part 1 - Annual Change (7:05)
 
 Measuring Change: lag(), part 2 - Monthly Change (2:48)
 
 Measuring Change: first(), part 1 - From First Year (3:22)
 
 Measuring Change: first(), part 2 - From First Month (5:24)
 
 Cumulative Calculations: cumsum() (3:21)
 
 Cumulative Calculations: Cumulative Percentage (5:31)
 
 Rolling Calculations: zoo::rollmean() (7:54)
 
 Filtering Date Ranges (4:24)
 
 🔽 Code Checkpoint: lubridate (File Download)
## 3.3 Text Fundamentals: stringr
 
 Cheat Sheet: stringr (3:38)
 
 🔽 Text Analysis Setup (File Download) (3:08)
 
 Text Detection: str_detect() (5:10)
 
 Changing Case: str_to_upper(), str_to_lower(), & str_to_title() (1:47)
 
 Concatenation, Part 1: str_c() (2:40)
 
 Concatenation, Part 2: str_glue() (6:11)
 
 Separating Text: tidyr::separate() & str_split() (6:42)
 
 Trimming Text: str_trim() (1:38)
 
 Replacing Text: str_replace() & str_replace_all() (6:23)
 
 Formatting Numbers: scales library (6:22)
 
 Formatting Column Names Programmitcally, Part 1: set_names() (4:46)
 
 Formatting Column Names Programmatically, Part 2: rename_at() (7:12)
## 3.4 Text Analysis: Feature Engineering Case Study
 
 Feature Engineering Part 1: Overview (2:30)
 
 Feature Engineering Part 2: Data Cleaning (Fixing Typo No. 1) (4:34)
 
 Feature Engineering Part 3: Separating Model Text (6:55)
 
 Feature Engineering Part 4: Making A Model Base, Pt1 (6:44)
 
 Feature Engineering Part 5: Making A Model Base Pt2 (4:15)
 
 Feature Engineering Part 6: Fixing Typo No. 2 (1:25)
 
 Feature Engineering Part 7: Making A Model Tier Column (2:40)
 
 Feature Engineering Part 8: Remove Unnecessary Columns (1:31)
 
 Feature Engineering Part 9: Fix Missed Model Concatenation (1:45)
 
 Feature Engineering Part 10: Mining Model Tier For Flags, Pt1 (5:52)
 
 Feature Engineering Part 11: Fixing Typo No. 3 (1:21)
 
 Feature Engineering Part 12: Mining Model Tier For Flags, Pt2 (1:31)
 
 🔽 Code Checkpoint: stringr (File Download)
Categorical Data Fundamentals: forcats
 
 Documentation: forcats (1:44)
 
 🔽 Categorical Data Setup (File Download) (2:29)
 
 Why Factors? (3:07)
 
 Motivating Example, Part 1: Visualizing Sales By Secondary Product Category (8:20)
 
 Motivating Example, Part 2: Finishing Up The Sales By Secondary Product Category Visualization (4:43)
 
 Factors & forcats Basics (6:01)
 
 as_factor() vs as.factor() (2:43)
 
 Reordering Factors: fct_reorder() & fct_rev() (4:53)
 
 Time-Based Factor Reordering: fct_reorder2() (8:54)
 
 Making An "Other" Category: fct_lump() & fct_relevel() (6:18)
 
 🔽 Code Checkpoint: forcats (File Download)
# Module 3 Challenges
 
 🔽 Module 3 Challenge (File Download) (7:18)
 
 🔽 Module 3 Challenge - Solution (File Download) (23:01)
# Module 4: Data Visualization with ggplot2
 
 Data Visualization - Overview (2:59)
 
 ggplot2 Cheat Sheet: Page 1, Geometries (5:34)
 
 ggplot2 Cheat Sheet: Page 2, Formatting (3:49)
## 4.1 Anatomy Of A ggplot
 
 🔽 Anatomy (File Download)
 
 Generating A ggplot2, Part 1: Data & Geoms (9:37)
 
 Generating A ggplot2, Part 2: Formatting (5:41)
 
 Anatomy of a ggplot2 Object: What is g? (3:30)
## 4.2 ggplot2 Geometries
 
 🔽 Geometries Setup (File Download) (2:33)
 
 Scatter Plot, Part 1: Data Manipulation (4:49)
 
 Scatter Plot, Part 2: geom_point() & geom_smooth() (10:21)
 
 Line Plot, Part 1: Data Manipulation (4:27)
 
 Line Plot, Part 2: geom_line() & geom_smooth() (6:35)
 
 Bar/Column Plot, Part 1: Data Manipulation (3:11)
 
 Bar/Column Plot, Part 2: geom_col() (5:41)
 
 Histogram Plot: geom_histogram() (6:18)
 
 Histogram - Faceted (6:10)
 
 Density Plot: geom_density() (3:04)
 
 Box Plot: geom_boxplot() (7:11)
 
 Violin Plot: geom_violin() & geom_jitter() (5:19)
 
 Text & Labels, Part 1: Data Manipulation (3:36)
 
 Text & Labels: geom_text() (7:39)
 
 Text & Labels: geom_label() (6:51)
 
 🔽 Code Checkpoint (File Download)
## 4.3 ggplot2 Formatting
 
 Cheat Sheet - ggplot - Page 2 (1:01)
 
 🔽 Formatting Setup (File Download) (5:16)
 
 Colors & Color Conversions (5:55)
 
 Color Palettes: tidyquant, Brewer, & Viridis (9:14)
 
 Aesthetic Mappings: color (5:56)
 
 Aesthetic Mappings: fill (3:33)
 
 Aesthetic Mappings: size (3:40)
 
 Faceting (7:06)
 
 Position Adjustments: Bar Plot, Stacked & Dodge (3:57)
 
 Stacked Area: geom_area() (1:21)
 
 Scales: Setup (8:22)
 
 Scales: Scale Color Continuous (7:22)
 
 Scales: Scale Color Discrete (5:57)
 
 Scales: Scale Fill Discrete (2:21)
 
 Scales: Scale X&Y (4:40)
 
 Labels & Legends: labs() (5:04)
 
 Theme: theme() (9:25)
 
 Putting It All Together (11:05)
 
 🔽 Code Checkpoint (File Download)
## 4.4 Advanced Business Plotting with ggplot2
 
 🔽 Advanced Business Plotting: Setup (File Download) (1:19)
 
 Top N Customers: Lollipop Plot, Part 1 - Data Manipulation (14:44)
 
 Top N Customers: Lollipop Plot, Part 2 - Geometries (11:07)
 
 Top N Customers: Lollipop Plot, Part 3 - Formatting (10:50)
 
 Customer Buying Habits: Heatmap, Part 1 - Data Manipulation (8:37)
 
 Customer Buying Habits: Heatmap, Part 2 - Geometries & Scales (8:37)
 
 Customer Buying Habits: Heatmap, Part 3 - Labels & Theme (9:59)
 
 🔽 Code Checkpoint (File Download)
# Module 5: Functional Programming & Iteration with purrr
 
 Functional Programming & Iteration - Overview (0:59)
## 5.1 Functional Programming
 
 Cheat Sheet: Base R (3:10)
 
 🔽 Setup: Functional Programming (File Download) (3:44)
 
 Anatomy of a Function, Part 1: Why Customize the mean() Function? (3:53)
 
 Anatomy of a Function, Part 2: Customizing the mean() Function (5:41)
 
 Example Data Manipulation: Sales By Year & Category 2 (9:45)
 
 Example Data Visualization: Sales By Year & Category 2 (5:42)
 
 The 2 Types of Functions: Vectorized vs Data Frame (5:27)
 
 Controlling Flow: If Statements, Messages, Warnings, & Errors (9:41)
 
 detect_outliers(), Part 1: Building A Vectorized Function (3:08)
 
 detect_outliers(), part 2: Function Setup (3:54)
 
 How A Box Plot Detects Outliers (1:03)
 
 detect_outliers(), Part 3: Implement Box Plot Outlier Logic (6:07)
 
 detect_outliers(), Part 4: Adding a Flag with case_when() (3:07)
 
 detect_outliers(), Part 5: Testing Our Function (1:23)
 
 detect_outliers(), Part 6: Visualizing Outliers (5:24)
 
 separate_bike_model(), Part 1: A Data Frame Function (8:34)
 
 separate_bike_model(), Part 2: Testing Our Function (2:38)
 
 Saving Functions, Part 1: Creating Files & Folders (2:16)
 
 Saving Functions, Part 2: Creating a header with write_lines() (4:12)
 
 Saving Functions, Part 3: Writing Functions with dump() (1:31)
 
 Saving Functions, Part 4: Loading Functions with source() (1:32)
 
 🔽 Checkpoint: Functional Programming (File Download)
## 5.2 Iteration with purrr
 
 Cheat Sheet: purrr (5:16)
 
 🔽 Setup: Iteration with purrr (File Download) (3:39)
 
 purrr primerrr, Part 1: Reading Many Excel Files in a Directory (3:08)
 
 purrr primerrr, Part 2: For Loop (3:26)
 
 purrr primerrr, Part 3: map() (6:23)
 
 purrr primerrr, Part 4: Reading Multiple Excel Sheets in an Excel File (2:20)
 
 Mapping Over Data Frames (10:01)
 
 Nested Data, Part 1: unnest() (5:42)
 
 Nested Data, Part 2: nest() (1:33)
 
 Mapping Nested Data, Part 1: Create Function that Works on 1 Element (4:21)
 
 Mapping Nested Data, Part 2: Scale with mutate() + map() (6:21)
 
 Modeling with purrr, Part 1: LOESS Smoother for Time Series (4:58)
 
 Modeling with purrr, Part 2: Make a LOESS model with loess() (7:31)
 
 Modeling with purrr, Part 3: Intro to broom, augment() (3:42)
 
 Modeling with purrr, Part 4: Creating a tidy_loess() function for mapping (8:53)
 
 Modeling with purrr, Part 5: Mapping tidy_loess() to all Categories (8:10)
 
 🔽 Checkpoint: Iteration with purrr (File Download)
# Module 6: Modeling, Part 1 - K-Means Clustering & UMAP
 
 Modeling, Part 1: Overview - K-Means & UMAP (0:46)
 
 Clustering & Dimensionality Reduction - Key Concepts & Theory Explained
 
 🔽 Cheat Sheet Download: Segmentation and Clustering (File Download) (0:48)
 
 Segmentation & Clustering Workflow (9:22)
## 6.1 Customer Segmentation with K-Means Clustering & UMAP
 
 🔽 Customer Segmentation with K-Means Clustering Setup (File Download) (2:53)
 
 Analyzing Customer Trends & The User-Item Matrix (2:17)
 
 Setting Up Customer Trends, Part 1: Aggregation (7:44)
 
 Setting Up Customer Trends, Part 2: Normalization (3:42)
 
 User-Item Matrix (3:50)
 
 K-Means Clustering for Customer Segmentation: Algorithm Overview (4:23)
 
 kmeans() Function (6:56)
 
 broom: Tidy the kmeans() Output (5:44)
 
 purrr: Cluster Iteration with map() (8:37)
 
 Scree Plot: Visualize & Evaluate K-Means Clusters (7:36)
 
 K-Means Recap (1:30)
 
 UMAP: High-Performance Dimension Reduction (1:09)
 
 umap() Function (8:36)
 
 Combining UMAP & K-Means Results (4:48)
 
 Customer Segment Visualization (6:36)
 
 Customer Segment Purchasing Trends Analysis, Step 1: Joining Clusters (3:15)
 
 Customer Segment Purchasing Trends Analysis, Step 2: Binning Price (5:47)
 
 Customer Segment Purchasing Trends Analysis, Step 3: Rearranging Columns (2:58)
 
 Customer Segment Purchasing Trends Analysis, Step 4: Aggregation (2:29)
 
 Customer Segment Purchasing Trends Analysis, Step 5: Normalization (1:46)
 
 Customer Segment Purchasing Trends Analysis, Step 6: Cluster 1 (4:01)
 
 Customer Segment Purchasing Trends Analysis, Step 7: Clusters 2-4 (4:39)
 
 Customer Segment Purchasing Trends Analysis, Step 8: Visualization (8:03)
 
 🔽 Code Checkpoint (File Download)
# Module 6: Challenge 1 - Company Segmentation with Stock Prices
 
 🔽 Challenge Setup: Overview & Data (File Download) (6:46)
 
 Challenge Questions (8:37)
 
 Challenge Bonus - Exploring Clusters with an Interactive Plot (0:51)
 
 🔽 Challenge Solution (File Download) (25:21)
# Module 6: Modeling, Part 2 - Machine Learning (Regression)
 
 Learning Plan - Zero to Machine Learning Pro in Hours (Not Years)
 
 🔽 Cheat Sheet: Machine Learning for Regression (File Download) (2:24)
 
 🔽 [UPDATES]: Fixes to Module 6 Part 2 Code
 
 🔽 R File: separate_bikes_and_outlier_detection.R
### 6.2.1 Machine Learning Concepts
 
 Introduction to Machine Learning - Key Concepts Explained
 
 Machine Learning Summary & Terminology (9:16)
 
 Machine Learning: Model List & Model Overview (11:18)
### 6.2.2 Business Problem & Data Preparation
 
 🔽 Regression Modeling Setup (FIle Download) (9:31)
 
 Documentation: parsnip, rsample, recipes, & yardstick (8:19)
 
 Business Problem Review: Product Gaps (7:23)
 
 Train / Test Part 1: Data Preparation & Feature Engineering (4:37)
 
 Train / Test Part 2: Splitting the Data with rsample::initial_split() (8:06)
### 6.2.3 Linear Algorithms
 
 Linear Regression - Theory Explained
 
 Parsnip Model List (Amazing Resource) (1:56)
 
 Linear Regression, Part 1 (Model 01): The parsnip::linear_reg() function (8:14)
 
 Linear Regression, Part 2 (Model 01): The predict() function (2:29)
 
 Linear Regression, Part 3 (Model 01): Calculating Model Metrics (6:49)
 
 Model Interpretability for Linear Models - How it works
 
 Linear Regression, Part 4 (Model 01): Model Explanation (11:37)
 
 Calculating Metrics: Model Helper (3:44)
 
 Linear Regression Complex (Model 02): Adding Engineered Features (6:44)
 
 Linear Regression Complex (Model 02): Model Explanation (4:51)
 
 GLM Regularized Regression: Theory Explained
 
 GLM Regularized Regression (Model 03): GLMNET (Elastic Net) (9:01)
 
 GLM Regularized Regression (Model 03): Model Explanation (3:53)
### 6.2.4 Tree-Based Algorithms
 
 Tree-Based Methods & Parsnip Documentation (2:37)
 
 Decision Trees: Theory Explained
 
 Decision Trees (Model 04): rpart (8:39)
 
 Decision Trees (Model 04): Model Explanation with rpart.plot() (8:57)
 
 Random Forest: Theory Explained
 
 Random Forest (Model 05): ranger (12:01)
 
 Random Forest (Model 05): Ranger Model Explanation (7:20)
 
 Random Forest (Model 06): randomForest (3:26)
 
 Random Forest (Model 06): randomForest Model Explanation (5:22)
 
 Reproducibility: set.seed() (2:09)
 
 Gradient Boosted Machines (GBM): Theory Explained
 
 Gradient Boosted Machines (Model 07): XGBoost (7:53)
 
 Mini Challenge: Tune Your XGBoost Model (0:31)
 
 Mini Challenge Solution: Tune Your XGBoost Model (1:23)
 
 Gradient Boosted Machines (Model 07): XGBoost Model Explanation (5:05)
### 6.2.5 Testing the Models & Visualization
 
 Prediction & Evaluation Overview (1:47)
 
 Predicting New Bike Model: Over Mountain - Aluminum - Jekyll (10:46)
 
 Plotting Predictions: Over Mountain - Aluminum - Jekyll (5:39)
# Module 6 - Challenge 2: Predicting New Bike Model
 
 Challenge: New Triathlon - Aluminum - Slice (0:36)
 
 Challenge Solution: New Triathlon - Aluminum - Slice (10:05)
### 6.2.6 Modeling Recap
 
 Modeling Recap & Next Steps (7:09)
### 6.2.7 BONUS - Preprocessing & Support Vector Machines
 
 Preprocessing Pipelines with recipes (10:03)
 
 Applying Transformations & Getting Step Information with tidy() (4:14)
 
 Support Vector Machine (SVM): Theory Explained
 
 Support Vector Machine (Model 08): kernlab (7:46)
 
 Support Vector Machine (Model 08): Tuning the Model (3:32)
 
 SVM (Model 08): Testing on New Bike Models (6:32)
### 6.2.8 BONUS - Saving & Loading Models
 
 Saving & Loading Models - With tibbles! (10:14)
 
 🔽 Code Checkpoint (File Download)
# Module 7: Communication
 
 Module 7 Kickoff! (1:08)
## 7.1 RMarkdown Primer
 
 RMarkdown Cheat Sheet (5:58)
 
 🔽 Setup - RMarkdown (File Download) (8:30)
 
 YAML: Controlling Your Document Properties (10:11)
 
 Knitr Global Options, Part 1: echo, eval, results, fig.keep (7:42)
 
 Knitr Global Options, Part 2: message, warning, dpi, and more (4:00)
 
 RMarkdown: Used for Reports, Websites, Books, Apps, & More! (3:23)
 
 RMarkdown: Key Resources To Get Started (1:33)
 
 RMarkdown: Headers, Text, & Lists (4:05)
 
 RMarkdown: Tabsets & Images (6:50)
 
 RMarkdown: Code Chunks (3:32)
 
 RMarkdown: Plotting (3:25)
 
 RMarkdown: Tables & Footnotes (5:38)
## 7.2 Building Interactive Plots with Plotly
 
 🔽 Setup - Plotly (File Download) (3:15)
### 7.2.1 Part 1: Total Sales vs Time - Interactive Plotting Function
 
 plot_total_sales(): A Custom Interactive Plotting Function (1:52)
 
 Preparing Data for Plotting (5:30)
 
 String-Format-Time Expressions: strftime Cheat Sheet (2:18)
 
 Formatting Time Stamps with strftime Expressions (5:11)
 
 Making the Interactive Plot with plotly & ggplot2 (8:35)
 
 plot_total_sales(), Part 1: Setting up the custom time series function (6:39)
 
 plot_total_sales(), Part 2: Integrating ggplot() & ggplotly() (5:00)
### 7.2.2 Building Interactive Plots with plotly - Part 2: Sales By Category vs Time
 
 plot_categories(): A Custom Interactive Faceted Plotting Function (1:38)
 
 Preparing Data For Plotting (5:43)
 
 Making the Interactive Plot with plotly & ggplot2 (8:51)
 
 plot_categories(), Part 1: Handling the Data (5:33)
 
 plot_categories(), Part 2: Handling the Inputs & Filter Logic (7:21)
 
 plot_categories(), Part 3: Generating the Interactive Plot (5:23)
 
 Saving Our Functions (1:59)
 
 🔽 Code Checkpoint (File Download)
## 7.3 Sales Report with RMarkdown
 
 Building an Interactive Sales Report - HTML & PDF - RMarkdown & Plotly (1:40)
 
 RMarkdown Setup (2:35)
 
 YAML Setup (5:43)
 
 Knitr Global Options (3:01)
 
 Plotting Function Setup - RMarkdown (5:46)
 
 Report: Total Sales Section (8:39)
 
 Report: Road Bikes Section (6:00)
 
 Report: Mountain Bike Section (1:17)
 
 Converting to PDF Format (2:16)
 
 🔽 Code Checkpoint (File Download)
## Project 1 Report - Product Pricing Prediction Algorithm with XGBoost
 
 New Product Pricing Report - What You're Building! (1:19)
 
 🔽 Setup (File Download) (4:45)
 
 Data Science Report Structure - How to Communicate Data Science Effectively (2:10)
 
 ### Gap Analysis, Part 1: Bike List & get_bike_features() (7:12)
 
 Saving Functions with dump() & Loading Functions with source() (2:17)
 
 ### Gap Analysis, Part 2: Analyzing the Product Gaps & plot_bike_features(), Part 1 (8:52)
 
 plot_bike_features(), Part 2: Formatting the Plot (6:47)
 
 ### Saving Our Functions & Re-Knitting Our Report (3:59)
 
 Price Prediction Algorithm, Part 1 (4:56)
 
 Price Prediction Algorithm, Part 2 (6:06)
 
 Formatted Tables: knitr::kable() (2:10)
 
 Solution Summary (3:03)
 
 🔽 Code Checkpoint (File Download)
## Project 2 Report - Customer Segmentation with K-Means & UMAP
 
 Customer Segmentation Report - Yep, you're going to build this! (2:18)
 
 🔽 Setup (File Download) (3:34)
 
 ### Report Overview - Customer Segementation (2:16)
 
 Heat Map, Part 1 - Data Manipulation (7:35)
 
 Heat Map, Part 2 - Static Visualization with ggplot2 (8:32)
 
 Heat Map, Part 3 - Interactive Plot with ggplotly() (6:10)
 
### Saving Functions & Adding Your Analysis To The Report (4:48)
 
 Customer Segmentation, Part 1 - Customer Trends (7:18)
 
 Customer Segmentation, Part 2 - K-Means Clustering (4:51)
 
 Customer Segmentation, Part 3 - UMAP (6:02)
 
 Customer Segmentation, Part 4 - Combining K-Means & UMAP (2:54)
 
 Customer Segmentation, Part 5 - Plotting Function (9:10)
 
 ### Saving Functions & Adding Your Analysis to the Report (2:45)
 
 Customer Preferences, Part 1 - Overview (1:25)
 
 Customer Preferences, Part 2 - Data Manipulation 1 (6:33)
 
 Customer Preferences, Part 3 - Data Manipulation 2 (5:50)
 
 Customer Preferences, Part 4 - Visualization 1 (9:47)
 
 Customer Preferences, Part 5 - Visualization 2 (5:22)
 
 Saving & Loading the Functions - dump() & source() (1:53)
 
 ### Completing the Analysis - Customer Preferences Statement & Solution Summary (6:02)
 
 🔽 Code Checkpoint (File Download)
Course Completion - Hooray!
 
 Congrats! You Did It! (1:12)
 
 About Data Science for Business Part 2: Learn H2O, LIME, & the BSPF (2:30)
 
 Get Your Certificate & Show It To The World! (1:07)
