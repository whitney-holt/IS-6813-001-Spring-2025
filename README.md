# IS-6813-001-Spring-2025
Required GitHub Portfolio for IS 6813 in Spring '25.

# Summary of Business Problem and Project Objective
## Business Problem
Swire Coca-Cola (SCCU) aims to optimize delivery logistics by shifting low-volume customers to cost-efficient Alternate Routes to Market (ARTM/white truck delivery) using third-party services. However, this shift may inadvertently move high-growth potential customers to less personalized service, risking revenue loss and weakened relationships.

## Project Objective
The objective of this project is to establish a reliable, data-informed, systematic method to identify and predict high-potential customers, balancing efficiency with sustainable growth.

# Solution to the Business Problem
Our team deployed over 20 advanced models, with Linear Regression achieving the best performance. By integrating regression forecasting, Swire could refine its 400-unit threshold for smarter routing decisions.

We also developed a Tableau Dashboard for real-time ‘what-if’ analyses, enabling teams to determine optimal White Truck vs. Red Truck assignments.

Looking ahead, clustering analysis could uncover deeper customer patterns, while black-box machine learning models could improve predictive power, ultimately balancing cost efficiency and growth.

# Business Value of the Solution
## Value of the Tableau Dashboard
- Interactive filters empower Swire Coca-Cola (SCCU) teams to perform real-time 'what-if' analysis by adjusting the threshold for white truck assignments. For example, a team could explore how total delivery cost changes across delivery methods when adjusting the threshold from 400 units to 1,000 units.
- Drill-down capability to customer-level statistics allows SCCU to identify individual customer trends, outliers, and performance metrics. For instance, the dashboard could highlight customers who consistently fall below the threshold but show growth potential.
- Clear and intuitive graphics make it easy for decision-makers to spot patterns, pinpoint inefficiencies, and prioritize actions, such as flagging high-potential customers at risk of misclassification.

## Value of Our Highest Performing Predictive Model
- The model enables SCCU to accurately predict high-potential customers. For example, it could identify specific customers who would benefit from personalized service, allowing teams to proactively build stronger relationships.
- With similar R-squared values for the train and test sets, the model demonstrates robust generalization to unseen data, ensuring reliable predictions even in changing market conditions.
- By uncovering the top five predictors of customer potential—such as order volume trends or geographical factors—the model provides actionable insights that SCCU can use for deeper analysis and strategic decision-making.

# Difficulties Encountered Along the Way
## Exploratory Data Analysis
- Missing values
- Collinearity among predictors
- Potential outliers and noise

## Modeling
- Needing to aggregate the data for models to run in a timely manner
- Using two years' worth of data to predict a third year
- Employing feature engineering in a way that made sense to the business and could be replicated easily

# My Contribution to the Project
Working with three phenomenal teammates, my personal contributions to the project included:
- Conducting independent exploratory data analysis (EDA), constructing a Tableau workbook with dozens of graphics
- Building several predictive models, including baseline mean and median, RIDGE, LASSO, and Elastic Net Regression models
- Constructing an interactive packaged Tableau dashboard, ultimately delivered to Swire Coca-Cola
- Presenting the interactive Tableau dashboard to Swire Coca-Cola live, demonstrating key features and functionalities
- Coordinating group meetings, establishing a consistent meeting schedule, and supporting Zoom meetings

# Lessons Learned
## Defining and Redefining the Business Problem
Our group ended up redefining the business problem more than once as we gained additional knowledge and understanding of Swire Coca-Cola and its data—and that was perfectly okay! If we had shied away from redefining the business problem, we would have missed opportunities to provide real business value.

## Exploring More than One Solution
Our team was open to various solutions, producing over 20 predictive models. In the end, we decided to pair our predictive model with an interactive Tableau dashboard, allowing for descriptive analytics alongside predictive analytics. These two components together helped shape our team's business solution and enabled prescriptive analytics. If we had been dead-set on a predictive model alone, we wouldn't have been able to produce such a comprehensive solution.

## Working in a Team
Each member of our team brought their own strengths. While it was essential that each of us participate in every step along the way, our individual strengths were complementary and allowed for a better solution than we could have developed as individuals.
