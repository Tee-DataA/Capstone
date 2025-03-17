# Capstone Project

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


Welcome to my captsone project! I decided to see which countries are emerging in the manufacturing industry. I chose this because the data was available and I found it intruiging. It was very important to me that I used real data as this gives a sense of Authethenticity and relevance to the analysis, ensuring that the insights and conclusions drawn are grounded in actual industry trends and economics.

## Dataset Content
* Dataset shows the value both in local currency and USD of different industries from various countries around the world. The data begins in 2000 and goes up to 2021. Initial scan of the database show that not every country has data in every year, so the exported csv files will be adjusted to take 2018 at the latest as this has the most significant data. I will also be using GDP data from the Worldbank website to help support my analysis as the features in my main dataset aren't enough to draw conclusions on their own.

https://www.iea.org/data-and-statistics/data-product/energy-and-emissions-per-value-added-database

https://data.worldbank.org/indicator/NY.GDP.MKTP.CD

## User Profile
User Profile: Global Manufacturing Investor
Name: John Smith
Occupation: Senior Investment Analyst at Global Ventures Capital
Background:
John Smith is a seasoned investment analyst with over 15 years of experience in the financial industry. He holds a Master's degree in Finance from the London School of Economics and has worked with several top-tier investment firms. John specializes in identifying high-growth investment opportunities in emerging markets and has a keen interest in the manufacturing sector.

Investment Focus:
John's primary focus is on the manufacturing industry, where he seeks to identify sectors with significant growth potential and strong returns on investment. He is particularly interested in industries that are poised for expansion due to technological advancements, favorable economic policies, and increasing global demand.

Geographic Interest:
As a global investor, John is open to investment opportunities across the world. However, he has a particular interest in Europe and the UK, given his familiarity with the region's economic landscape and regulatory environment. He is also keen on exploring opportunities in emerging markets, where he believes there is substantial untapped potential.

Investment Criteria:

Growth Potential: John looks for industries that have shown consistent growth over the years and have the potential for future expansion.
Economic Stability: He prefers countries with stable economic conditions and favorable government policies that support industrial growth.

Technological Advancements: John is interested in industries that are leveraging new technologies to improve efficiency and productivity.

Market Demand: He seeks sectors with increasing global demand, ensuring a steady market for the products.

Risk Management: John evaluates the risks associated with each investment, including political, economic, and market risks, and seeks to mitigate them through diversification and strategic planning.

Data Requirements:
To make informed investment decisions, John requires comprehensive data on the manufacturing industries, including:

Historical and current values (in USD) of different manufacturing sectors.
Year-over-year growth rates of these industries.
Comparative analysis of manufacturing sectors across different countries.
Insights into the economic conditions and policies of the countries in question.
Visualizations and dashboards that provide a clear overview of industry trends and performance metrics.
Use of Data:
John will use the data to:

Identify the most promising manufacturing sectors for investment.
Assess the performance and growth potential of these sectors over time.
Compare the manufacturing industries across different countries to determine the best investment destinations.
Develop investment strategies that align with his firm's goals and risk tolerance.
Present data-driven insights to stakeholders and clients to support investment decisions.
Goals:
John aims to leverage the data to:

Maximize returns on investment by identifying high-growth manufacturing sectors.
Diversify his investment portfolio by exploring opportunities in different regions.
Stay ahead of market trends and make proactive investment decisions.
Contribute to the growth and development of the global manufacturing industry by supporting innovative and sustainable practices.
By utilizing the comprehensive data on the value (USD) of 12 manufacturing industries across the globe, John Smith can make well-informed investment decisions that align with his firm's objectives and drive significant returns.


## Hypothesis and how to validate?

# Hypothesis 1: #
The manufacturing industry in Asia has experienced the highest growth in value (USD) from 2000 to 2018.

How to Test:

Aggregate the data to calculate the total value (USD) of the manufacturing industry for each continent.
Calculate the percentage growth for each continent from 2000 to 2018.
Compare the growth rates to identify the continent with the highest growth.

# Hypothesis 2:#
Hypothesis: The manufacturing of machinery sector has shown the most significant increase in value (USD) across all countries from 2000 to 2018.

How to Test:

Filter the data to include only the electronics manufacturing sector.
Aggregate the data to calculate the total value (USD) for each year.
Calculate the percentage growth of the machinery sector from 2000 to 2021.
Compare the growth rate with other sectors to determine if it is the highest.

# Hypothesis 3:
Hypothesis: European countries have more stable manufacturing growth compared to other regions.

How to Test:

Calculate the year-over-year growth rate of the manufacturing industry for each country.
Compute the standard deviation of the growth rates for each region.
Compare the standard deviations to assess the stability of manufacturing growth across different regions.

## Project Plan
* After loading and cleaning the dataset, columns and data will be adjusted to make it easier to read and perform analysis on. 
* Data is collected through the IEA website which works with governments and industries to shape a secure and sustainable energy future. The data is readily available and free to access. Datais also collected from the worldbank website.

The research methodologies were chosen based on the specific requirements and goals of the project. The primary objective was to provide actionable insights for the user looking to invest in new industries. The methodologies were selected to ensure comprehensive, accurate, and relevant analysis. Here are the key reasons for choosing the methodologies:

1. **Descriptive Statistics:**
   - **Purpose:** To summarize and describe the main features of the dataset.
   - **Reason:** Descriptive statistics provide a clear overview of the data, including measures of central tendency (mean, median) and dispersion (standard deviation, range). This helps in understanding the general trends and patterns in the data.

2. **Time Series Analysis:**
   - **Purpose:** To analyze data points collected or recorded at specific time intervals.
   - **Reason:** Time series analysis is essential for identifying trends, seasonal patterns, and cyclical behavior in the data over time. This is crucial for understanding how industries have developed and predicting future trends.

3. **Comparative Analysis:**
   - **Purpose:** To compare different groups or categories within the dataset.
   - **Reason:** Comparative analysis allows for the evaluation of different industries and countries, highlighting the most promising investment opportunities and identifying areas of growth.

4. **Data Visualization:**
   - **Purpose:** To represent data graphically.
   - **Reason:** Visualizations such as graphs, charts, and dashboards make complex data more accessible and understandable. They help in communicating insights effectively to both technical and non-technical audiences.

5. **Exploratory Data Analysis (EDA):**
   - **Purpose:** To analyze data sets to summarize their main characteristics.
   - **Reason:** EDA helps in uncovering initial insights, detecting anomalies, and testing hypotheses. It is a crucial step in understanding the data before applying more complex analytical techniques.

### Justification for Methodologies

The chosen methodologies align with the project's goals of providing clear, actionable insights for investment decisions. They ensure a thorough analysis of the data, considering both historical trends and future projections. By combining descriptive statistics, time series analysis, comparative analysis, and data visualization, the project delivers a comprehensive view of the data, supporting informed decision-making.

Additionally, the use of machine learning techniques (if applicable) and exploratory data analysis further enhances the robustness and depth of the analysis, ensuring that the insights are both accurate and relevant to the user's needs.

## The rationale to map the business requirements to the Data Visualisations
* The business requirements for this project focus on providing actionable insights for a global manufacturing investor. The data visualizations are designed to meet these requirements by presenting complex data in an accessible and understandable format. Here’s how the visualizations map to the business requirements:



## Analysis techniques used

* In this project, various data analysis techniques were employed to provide actionable insights for a global manufacturing investor. Here are the key techniques used:

# Descriptive Statistics:

Purpose: To summarize and describe the main features of the dataset.
Techniques Used: Measures of central tendency (mean, median) and dispersion (standard deviation, range).
Rationale: Descriptive statistics provide a clear overview of the data, helping to understand general trends and patterns.

# Time Series Analysis:

Purpose: To analyze data points collected or recorded at specific time intervals.
Techniques Used: Line charts and trend analysis.
Rationale: Time series analysis is essential for identifying trends, seasonal patterns, and cyclical behavior in the data over time, which is crucial for understanding how industries have developed and predicting future trends.

# Comparative Analysis:

Purpose: To compare different groups or categories within the dataset.
Techniques Used: Bar charts, heatmaps, and comparative statistics.
Rationale: Comparative analysis allows for the evaluation of different industries and countries, highlighting the most promising investment opportunities and identifying areas of growth.

# Data Visualization:

Purpose: To represent data graphically.
Techniques Used: Graphs, charts, and dashboards.
Rationale: Visualizations make complex data more accessible and understandable, helping to communicate insights effectively to both technical and non-technical audiences.

# Exploratory Data Analysis (EDA):

Purpose: To analyze data sets to summarize their main characteristics.
Techniques Used: Data cleaning, outlier detection, and initial hypothesis testing.
Rationale: EDA helps in uncovering initial insights, detecting anomalies, and testing hypotheses, which is a crucial step in understanding the data before applying more complex analytical techniques.

# Limitations and Alternative Approaches

DThe dataset may have missing values or inconsistencies that could affect the analysis. To address this, data cleaning and imputation techniques were used. If the data had significant limitations, alternative data sources or additional data collection methods could be considered to enhance the analysis.

# Structuring Data Analysis Techniques
The data analysis techniques were structured to align with the project's goals of providing clear, actionable insights for investment decisions. The process included:

Data Cleaning and Preparation: Ensuring the dataset was accurate and complete.
Descriptive Statistics: Providing an initial overview of the data.
Time Series Analysis: Identifying trends and patterns over time.
Comparative Analysis: Evaluating different industries and countries.
Data Visualization: Communicating insights effectively.

# Use of Generative AI Tools
Generative AI tools were used to assist with ideation, code optimization and troubleshooting. These tools helped in:

# Ideation: Generating ideas for data visualizations and analysis techniques.

User Profile: The user profile was generated using AI by giving it information about the dataset and the relevant parties that were looking to benefit from it.

Code Optimization: Improving the efficiency and readability of the code.

Analysis data: Some of the data was described using AI such as the sunburst graph. AI was also used to suggest what analysis and graphs can and should be performed on the dataset presented and the relevant statistical tests to perfrom. 

Troubleshooting: Fixing issues with the code and helping with complex coding tasks

By employing these analysis techniques, the project aims to provide comprehensive and accurate insights that align with the investor's goals and support informed decision-making.

## Ethical considerations
* All of the data obtained publically available and obtained from well known established organisations. No private information was in the data

## Dashboard Design
The dashboard was designed in tableau as it is a powerful tool to perform live data analysis on. The graphs used were:

* World heat map: To quickly identify countries with high Value
* GDP vs Value area chart and line graph for year on year percentage change: Shows the value of the manufacturing industries compared to the total GDP and line graph quickly shows the growth of the GDP vs Value.

## Unfixed Bugs
* There are no unfixed bugs
*
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment


## Main Data Analysis Libraries
* Pandas:
   Purpose: Data manipulation and analysis.
   Example Usage: Loading datasets, cleaning data, filtering, and aggregating data.

* NumPy:
   Purpose: Numerical operations and array manipulation.
   Example Usage: Handling numerical data and performing mathematical operations.

* Matplotlib:
   Purpose: Data visualization.
   Example Usage: Creating static plots and charts.

* Seaborn:
   Purpose: Statistical data visualization.
   Example Usage: Creating advanced visualizations such as heatmaps and pair plots.

* Plotly:
   Purpose: Interactive data visualization.
   Example Usage: Creating interactive plots and dashboards.

## Evaluation

We will answer the following hypothesis here

# Hypothesis 1: #
The manufacturing industry in China has the largest value (USD) in 2018

Answer: I findings indicate that this is true.

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

# Hypothesis 1: #
The manufacturing industry in Asia has experienced the highest growth in value (USD) from 2000 to 2018.

According to our findings this is not the case.

# Hypothesis 2:#
Hypothesis: The manufacturing of machinery sector has shown the most significant increase in value (USD) across all countries from 2000 to 2018.


## Credits 
Data was obtained from the following websites:

https://www.iea.org/data-and-statistics/data-product/energy-and-emissions-per-value-added-database

https://data.worldbank.org/indicator/NY.GDP.MKTP.CD


## Acknowledgements (optional)
* Special thanks to Vasi Pavaloi who was readily available to give advice and direction when I was stuck