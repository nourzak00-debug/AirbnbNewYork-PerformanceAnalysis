Airbnb Data Analysis Project (New York)

First: Technical Aspect (Data Preparation & DAX)
Data Cleaning:
Unnecessary columns were removed. To ensure data accuracy, numeric null values were replaced with the Median, while textual null values were replaced with the Mode.

DAX Expressions:

DATEDIFF: Used to calculate time differences, property age metrics, and the duration since the last review.

CALCULATE: Used to manipulate the Filter Context and accurately calculate revenues across different categories.

Conditional IF: Used to create calculated columns that determine property status and activity levels.

Second: Key Insights by Page
Property Category
Overall Performance: The project recorded $33.96 million in total revenue across 7,167 units, maintaining a strong average rating of 4.53 out of 5.

Customer Behavior: Entire home/apartment rentals account for 36% of the market share and serve as the primary revenue driver, generating $18.80 million (more than half of the total revenue).

Property Type: Traditional apartments and private rooms yield the highest returns, whereas hotels and farm stays show negligible financial contribution.

Region
Manhattan in the Lead: Manhattan is the primary financial driver, generating $15.4 million—double the revenue of Brooklyn, which ranks second at $7.5 million.

Stagnation: Staten Island contributes the least to the market, with a modest revenue of only $0.3 million.

Reviews
Strong Stagnation Indicator: The average number of days since the last review is exceptionally high (671 days), and the active unit rate stands at just 20.2%. This indicates a large volume of inactive listings that require reactivation strategies.

Consistent Customer Satisfaction: Overall ratings remain strong and consistent across all regions. This proves that lower revenue in certain neighborhoods is driven by a shortage of units or lower pricing models, rather than poor service quality.
