# NYC Public School Test Scores Analysis
## Project Overview
This Project explores the SAT Performance of Public Schools across New York City's boroughs. Analyzing the performance of schools is important for a variety of stakeholders, including policy and education professionals, researchers, government, and even parents considering which school their children should attend.The goal is to identify trends and patterns in educational outcomes.
## Key Insights and Questions Addressed
In this analysis, I Focused on Three Key questions about the NYC Public School system:

**Best Math Results:**
Which NYC Schools have the best math results (specifically, a score of 80% or higher?

**Top 10 Schools:**
What are the top 10 performing schools based on a Combined SAT score (Math + Reading + Writing)?

**Borough Variability:**
Which Single borough has the Largest Standard Deviation in the combined SAT score, indicating the widest gap in student Performance?

## The Dataset:
The dataset contains SAT scores for NYC Public schools. Key columns used:
* 'school_name' : Name of the high School.
* 'borough' : The NYC borough the school is located in.
* 'average_math' : average math score of school in Particular borough.
* 'average_reading' : average reading score of school in Particular borough.
* 'average_writing' : average writing score of school in Particular borough.
* 'total_SAT' : A calculated column representing the sum of Math, Reading and Writing scores.

## My Approach:
1. **Filtering for Excellence:**
I applied a threshhold of 80% (640 or higher )of maximum possible score of 800 to 'average_math' to identify top-tier math schools.
2. **Feature Engineering:**
I Created a 'total_SAT' column to get a holistic view of School Performance.
3. **Statistical Analysis:**
I grouped the data by 'borough' to calculate the mean and standard deviation of scores.

## Technologies used:
* Python
* Pandas
* Seaborn

## How to Run:
1. Clone the repo.
2. Open the notebook/Script in your Preferred IDE.
