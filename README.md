EDA-for-titanic-dataset
As part of an AI/ML internship task, I conducted an Exploratory Data Analysis (EDA) on the famous Titanic dataset. The goal was to gain a deeper understanding of the data, uncover patterns, and identify important factors that influenced passenger survival. This foundational analysis helps in preparing the data for future predictive modeling

Getting to Know the Data
I started by loading the Titanic dataset and exploring its overall structure—checking the number of records, types of features, and missing values. This gave me a solid grasp of what kind of information was available and what might need cleaning.

Summarizing Key Statistics
Next, I looked at summary statistics for both numerical and categorical variables. This step helped me understand the typical values, ranges, and whether any data was skewed or unusual.

Visualizing the Data
Visualizations were a big part of the analysis. I created:
Histograms to see how numerical features like Age and Fare were distributed. Boxplots to compare Age and Fare between passengers who survived and those who didn’t. Countplots to examine counts of categories like gender, passenger class, and embarkation points. A correlation heatmap to reveal how numeric variables related to each other.
Drawing Insights
From the visualizations and summaries, a few patterns stood out:
Women were more likely to survive than men. Passengers in first class had higher survival rates than those in second or third class. Both Age and Fare had some extreme values and skewed distributions, which might affect modeling later on.

Tools I Used

Python for data analysis Pandas to manage and manipulate the dataset Matplotlib and Seaborn for clear, insightful visualizations
