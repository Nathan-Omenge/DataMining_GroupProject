DSA 2040A Group Project – End-to-End Data Mining
zaky Shafi
Katt- Analyst
Aaron Irakoze - visualizer
Nathan
James Mponzi - Analyst

Role	Responsibilities

(ETL Lead	Designs and runs the pipeline) : ensures data accuracy, manages folder structure, and version control.
(Data Analyst)	: Examines cleaned data, performs exploratory and statistical analysis, and identifies trends and correlations.
(Visualizer)	: Builds visualizations or dashboards (Plotly Dash, Power BI) and presents insights.
(Documenter)	: Writes and updates README, summarizes weekly progress, and keeps group deliverables consistent.

Topic : Finance (Budgeting and insights)
This project appplies the full pipleine(ELT, Data mining and insights) using a raw perosnal finance data set that contain transaction- level data such as:
- Date
- merchant
- amount
- payement mode
- category
  
This process reflects on  what what has been done, issues faced and how they are solved starting with:

using the uplodaded raw data set ([budgetwise_synthetic_dirty_raw.csv](https://github.com/user-attachments/files/23227184/budgetwise_synthetic_dirty_raw.csv) 
We unfold with the process by assigning roles for the project which include( ETL lead (extract,transform,load), data analyst, visualizer, documenter)
The selected data set is associated with finance, the goal is to intentionally get a raw fiancial data with clear quality errors e.g (rows and columns contiang errors, wrong formats, duplicates, and missing fields).


Exploration and visulation tools in use for the process.

Seaborn - visualization , correlations, category comparisons and fruther trends(either going up or down)
Matplotlib - creating plots such as line graphs, bar charts and and other spending visulas.
Pandas- CLeaning, reading, transforming and meriging with the raw dataset to get a valuable dataset to work with.
 When extracting data sets not everything comes with a correct output meaning missing values, duplicates etc. problems such as:
 -missing values : some trancsations lack amount or dates
-duplicate records: repeated imports or logs from more than two accounts.
-Outliers: Amounts which are too high or  too low
-Category (errors in naming) : Transactions mislabeled or uncategorized
-Unbalnced date (more expenses than income) - missing accounts and expensse are higher than income.

The data set is not in order leaving it disorganized and inconsistent making it difficult to draw a relible financial output/conclusions.
- clean and standerdize messy data for anlaysis
- Detect spending trends and patterns
- Help users understand ehre their income goes.
- Provide insights (visualizations) to improve and savings.
  Basically, turn raw data and unreliable data into a meaningful and decison ready informations

Expanding the ETL pipeline goes throght the process such as
-extracting and validating the raw data
cleaning and tranforming it into a much more structured data set
-the display the final transformed files for data mining

What We Have to Do About the Raw Dataset
-Conduct data profiling: understand column meanings, missing counts, and outlines.
-Apply consistent outline enforcement: define correct data types (float, string, datetime).
-Develop cleaning scripts in Python (Jupyternotebook) for repeatability.
-Save intermediate outputs for comparison and versioning.
-Members of the group should review the transofrmation for accuracy.






