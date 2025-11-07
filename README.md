# market-analysis
#  Market Basket Analysis using Instacart Dataset

###  Project Overview
This project explores customer purchasing behavior using the **Instacart Market Basket dataset**, applying **Association Rule Mining (Apriori Algorithm)** to uncover hidden patterns and relationships between products frequently bought together.

By identifying these associations, retailers can:
- Recommend relevant products
- Optimize store layout and product placement
- Develop personalized marketing strategies


###  Objectives
- Perform **data cleaning and preprocessing** on Instacart datasets
- Analyze **customer order patterns and trends**
- Apply **Apriori algorithm** to find association rules
- Visualize top frequent product combinations


###  Key Concepts
- **Support:** Frequency of an itemset appearing in transactions
- **Confidence:** Likelihood of buying item Y when item X is bought
- **Lift:** Strength of association between items (values >1 indicate strong relationships)


###  Dataset Information
The dataset includes multiple CSV files containing user orders and product details.


###  Step by step Workflow

####  Data Acquisition & Loading
Loaded Instacart CSV datasets and merged them into a unified dataframe.

####  Data Exploration & Cleaning
- Verified missing values
- Merged product, aisle, and department data for complete product info

####  Transaction Formatting
Created **transaction lists** (customer → product list) suitable for Apriori processing.

####  Market Basket Analysis (Apriori)
- Generated frequent itemsets using the **Apriori algorithm**
- Extracted **association rules** with minimum support and confidence thresholds

####  Visualization & Insights
- Visualized product frequency distribution
- Identified top 10 frequently bought product pairs
- Interpreted rules to find meaningful product relationships


###  Sample Insights
- **Bananas** and **strawberries** frequently appear together in orders.
- **Organic products** have high lift values, showing strong cross-purchase potential.
- Product recommendations can be personalized based on frequent patterns.


###  Tools/Libraries
-Python
-pandas
-numpy
-matplotlib
-seaborn
-mlxtend.frequent_patterns


###  Key Results
- Discovered **strong association rules** with high lift and confidence.
- Improved understanding of **customer purchasing patterns**.
- Demonstrated the practical application of **Apriori Algorithm** in retail analytics.

###  Future Enhancements
- Integrate with a **recommender system** using the mined rules
- Apply **FP-Growth algorithm** for performance comparison

###  Author
**Bernice Nhyira Konadu Eghan**  
 Data Science & Business Analytics Enthusiast  
 [Linkedin: BerniceEghan] |  [GitHub: https://github.com/BerniceEghan] | 📧 bern1iceeghan1@gmail.com
