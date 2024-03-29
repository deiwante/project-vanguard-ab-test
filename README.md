## Project Documentation: Vanguard Online Process Redesign Analysis


# Metadata:


- client_id: Unique ID for each client.
- variation: Indicates if a client was part of the experiment.
- visitor_id: Unique ID for each client-device combination.
- visit_id: Unique ID for each web visit/session.
- process_step: Marks each step in the digital process.
- date_time: Timestamp of each web activity.
- clnt_tenure_yr: Client's tenure with Vanguard in years.
- clnt_tenure_mnth: Client's tenure with Vanguard in months.
- clnt_age: Age of the client.
- gendr: Gender of the client.
- num_accts: Number of accounts the client holds with Vanguard.
- bal: Total balance spread across all client accounts.
- calls_6_mnth: Number of times the client reached out over a call in the past six months.
- logons_6_mnth: Frequency of client logins to Vanguard’s platform over the last six months.


# Introduction:
This project analyzes client behavior data from Vanguard's online process, aiming to understand the impact of a redesign. The documentation covers data exploration, cleaning, analysis, and hypothesis testing.

**EDA & Data Cleaning:**


Merged multiple datasets.
Standardized column names.
Cleaned missing values and data inconsistencies.
Created visualizations for data exploration.

**Client Behavior Analysis:**


Analyzed primary client demographics and behavior.
Explored client account holdings and balances.
Investigated completion rates and errors in the online process.

**Performance Metrics:**


Calculated completion rates for the control and test groups.
Analyzed time spent on each step of the online process.
Evaluated error rates, including backward movements.

**Redesign Outcome:**


Compared new design performance against the old one.
Reviewed completion rates, time per step, and errors.

**Hypothesis Testing:**


Conducted hypothesis tests on completion rates.
Assessed completion rate changes with a cost-effectiveness threshold.

**Design Effectiveness:**


Evaluated experiment structure, randomization, and biases.
Assessed the adequacy of the experiment timeframe.
Identified potential additional data needs.

**Conclusion:**


The analysis provides insights into the impact of the online process redesign on client behavior and completion rates. Further experimentation or data collection may enhance the analysis.

# Libraries Used:
- pandas
- seaborn
- matplotlib.pyplot
- numpy
- scipy.stats
- glob
- statsmodels
