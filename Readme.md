## Mernis Data Analysis Project
**Goal**

The goal of the project is to complete some statistics and advanced predictions of MERNIS database with pyspark, including demographic analysis, population prediction and so forth. The algorithms and analysis results would be supportive for decision-making and risk-prevention. Furthermore, the project could be improved in computation resources, the integrity of data and scaling of analysis to provide more solid and precise results.


### Environment
The project read data from PostgreSQL database. In this project, the version of PostgreSQL is 13 and the version of pyspark is 3.1.1. 
Before analysis, the .dat file was read into PostgreSQL with all its original configurations and pyspark uses JDBC to read from the database.

### Discussion
**Potential applications**

The project depicts a demographic profile of Turkish citizen, which could be supportive for decision- making. For instance, the algorithm judges which city is aging may inform the government to design and announce relating policies. The month with the highest birth rate could motivates business to offer various discounts and coupons. The results analyzed from all these data are valuable for many agents.

The project provides several prediction model based on some demographics of Turkish citizen, which could be supportive for decision-making and risk-prevention. For instance, the algorithm predicting the new-born population could imply the market power of infants in the following year, which is beneficial for business analysis. The models analyzed from all these data are valuable for many agents.

![img](MernisDataAnalysis/pred.png)