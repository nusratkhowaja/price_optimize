# Boosting Sales Margin with Data-Driven Price Optimization

## Introduction
This project is an exploration of how data analytics and optimization strategies can significantly enhance the profitability of products sold on e-commerce platforms. There are a lot of factors that may influence the price of a product and the likelihood of the customer to buy that product at a price point. 

`Price optimization deals with analyzing the historical transaction data and figuring out trends and abnormalities in the sales of a product to predict the best price of that product that would not only increase the likelihood of the customer purchasing the product but at the same time increases the profit margin of the company by increasing the sales.`

This is achieved by modeling and training historical data using various machine learning algorithms resulting in a demand curve that would pinpoint the approximate best price of the product. We are considering sales volume as our major factor while trying to reach to an optimal price point.

## Project Objective
The primary goal is to identify a product from a top-selling category and implement data-driven pricing strategies to maximize its sales margin. This involves extensive data cleaning, exploratory data analysis (EDA), and the application of advanced analytical techniques.

## Dataset
The project utilizes the Brazilian public E-commerce dataset, which contains real transactional data from the Olist store based in Brazil. This dataset comprises over 100,000 records and 40 features spanning from 2016 to 2018. The consolidated dataset includes features relevant to the project's objectives.

## Methodology

### Data Cleaning and Preprocessing
- **Incomplete Records Analysis**: Investigated and addressed incomplete records in the dataset.
- **Duplicate Records Check**: Ensured the uniqueness of the dataset by checking for duplicates.
- **Order Status Filtering**: Focused analysis on 'delivered orders' to maintain relevance to the objective.

### Dimensionality Reduction
- Principal Component Analysis (PCA) is employed for dimensionality reduction, transforming the data from a high-dimensional to a low-dimensional space.
- This aids in retaining important features for modeling. PCA is applied to 24 features, reducing them to 17 components which retained almost 90% of the variance after encoding categorical features using Label Encoding.

<img width="848" alt="image" src="https://github.com/gaurichaudhari9/Boosting-Sales-Margin-of-a-product-using-Price-Optimization/assets/25304556/896baea2-7642-4220-bd0f-b0e21d4a5d47">

### Exploratory Data Analysis (EDA)
Data analysis provides insights into various aspects, such as product categories, sales trends, and revenue generation. 

**Key findings**  include the impact of time on order counts, top revenue-generating categories, and sales spikes on events like Black Friday.


### Price Optimization Modeling**: Developed model to determine the optimal pricing strategy for the selected product

The project involves training data using Linear Regression, Ridge, and Lasso algorithms to predict prices. Model evaluation includes Mean Squared Error (MSE) calculations. The project also explores a profit function and generating a demand curve, aiming to predict optimal prices for specific products.

<img width="860" alt="image" src="https://github.com/gaurichaudhari9/Boosting-Sales-Margin-of-a-product-using-Price-Optimization/assets/25304556/9e4e1101-4d1f-4904-8647-a2273ebf0408">

## Results
- **Improved Sales Margin**: Demonstrated a significant increase in the sales margin of the selected product through the application of the optimized pricing strategy. Based on the modeling results, adjusting the price of a specific product (437c05a395e9e47f9762e677a7068ce7) from **$50.03 to $39.59** is predicted to increase sales volume by **45%**, resulting in a projected revenue increase of **78%**.
- **Data-Driven Decisions**: Enabled informed decision-making by providing a data-backed rationale for pricing adjustments.

- While linear regression shows promise in predicting optimal prices, there is room for further improvement through advanced techniques like neural networks. This project highlights the significance of price optimization in enhancing customer purchases and company profits within an e-commerce context.


## Future Work
- Expand the analysis to multiple products and categories.
- The project acknowledges the potential for further optimization using neural networks or hybrid algorithms.
- Integrate real-time data feeds for dynamic pricing strategies.

## References

- [Tryolabs - Price Optimization Using Machine Learning](https://tryolabs.com/blog/price-optimization-machine-learning)
- [Unraveling Brazilian E-commerce Dataset](https://medium.com/hamoye-blogs/unraveling-brazilian-e-commerce-dataset-e78463d77340)
- [Price Optimization in Fashion E-commerce](https://www.semanticscholar.org/paper/Price-Optimization-in-Fashion-E-commerce-Kedia-Jain/69d699ca6ac62c759c6372aa86a10756c8f509ce)
- [Price Optimization with Machine Learning](https://7learnings.com/blog/price-optimization-with-machine-learning-what-every-retailer-should-know/)
- [Arxiv - Price Optimization in Fashion E-commerce](https://arxiv.org/abs/2007.05216)
- [Arxiv - Brazilian E-commerce Dataset](https://arxiv.org/pdf/2007.05216v2.pdf)

