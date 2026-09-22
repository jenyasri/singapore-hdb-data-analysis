# Singapore HDB Resale Price Analysis
An exploratory data analysis of Singapore's HDB resale market using Python, examining how resale prices vary across towns and what these differences may suggest about housing affordability and accessibility.
This was my first independent data analysis project, completed after learning the fundamentals of Python and before beginning my BSc in Data Science and Business Analytics.

## Research Question:
**How do HDB resale prices vary across towns, and what does this reveal about inequality and accessibility in Singapore?**

Through this project, I aimed to explore:
* How HDB resale prices have changed over time
* How resale prices differ across towns
* Differences in prices across flat types
* Factors associated with resale prices, including floor area and remaining lease
* What these patterns may suggest about housing affordability and accessibility in Singapore

## Tools & Libraries

The analysis was conducted in Python using:
* **Pandas** — data cleaning, manipulation and analysis
* **NumPy** — numerical operations
* **Matplotlib** — data visualisation
* **Seaborn** — statistical visualisation
* **Scikit-learn** — predictive modelling

The project was developed using Jupyter Notebook.

## Analysis

### 1. Data Cleaning & Preparation

Before beginning the analysis, I explored and prepared the dataset by checking its structure, identifying missing values and ensuring variables were suitable for analysis.
I also created additional variables, including **price per square metre**, to make comparisons across properties and towns more meaningful.

### 2. HDB Resale Prices Over Time

I examined how average HDB resale prices changed across the period covered by the dataset. The analysis showed an overall upward trend in average resale prices, with the increase becoming more pronounced during the later years of the period analysed.

### 3. Differences Across Towns

One of the clearest patterns was the variation in average resale prices between different parts of Singapore.

In the dataset analysed:

* **Bukit Timah:** approximately S$779,000
* **Bishan:** approximately S$712,000
* **Central Area:** approximately S$692,000
* **Queenstown:** approximately S$641,000
* **Bukit Merah:** approximately S$639,000
* **Yishun:** approximately S$452,000

These differences suggest that the affordability of resale HDB flats can vary substantially depending on location. 
However, these figures represent average transaction prices and do not control for differences in factors such as flat type, floor area, remaining lease or transaction period.

### 4. Flat Type & Floor Area

Larger flat types generally had higher resale prices. 
I also examined the relationship between floor area and resale price. 
The analysis showed a positive relationship, suggesting that larger properties generally command higher resale prices. 
However, size alone does not explain all of the variation in resale prices.

### 5. Remaining Lease

I investigated whether the remaining lease of a flat was associated with its resale price.
The analysis indicated a positive relationship between remaining lease and resale price, suggesting that flats with longer remaining leases generally tended to have higher resale values in the dataset.

### 6. Correlation Analysis

A correlation analysis was used to investigate relationships between several numerical variables.
This helped identify variables associated with resale price and demonstrated that HDB resale prices are related to multiple property characteristics rather than a single factor.

### 7. Predictive Modelling

I also experimented with using machine learning to predict HDB resale prices.
This part of the project introduced me to the process of preparing data for modelling, selecting features, training a model and evaluating its predictions.
Rather than treating the model as a definitive predictor of HDB prices, I used it as an opportunity to explore how the relationships identified during exploratory analysis could be applied to a predictive task.

## Key Takeaways

Some of the main observations from the project were:

* HDB resale prices showed an overall upward trend during the period analysed.
* Average resale prices differed considerably between towns.
* Larger flats generally had higher resale prices.
* Floor area and remaining lease were both positively associated with resale price.
* Comparing price per square metre provided another way of examining differences between towns beyond total resale price.
* HDB resale prices appear to be associated with a combination of location and property characteristics.

These findings are descriptive and should not be interpreted as establishing causal relationships.

## What I Learned

This project was an opportunity to move beyond Python exercises and apply what I had learned to an open-ended, real-world dataset.

Through the project, I gained experience in:

* Cleaning and preparing real-world data
* Exploratory data analysis
* Creating and interpreting data visualisations
* Working with Pandas and NumPy
* Using Matplotlib and Seaborn
* Investigating correlations between variables
* Building and evaluating a basic predictive model
* Communicating findings from data
* Recognising the difference between correlation and causation

Most importantly, the project taught me that data analysis involves much more than writing code. Deciding what questions to ask, determining which comparisons are meaningful and understanding the limitations of an analysis are equally important parts of the process.

## Limitations

This project is primarily exploratory.
The analysis does not establish that any individual factor causes changes in HDB resale prices. Differences between towns may reflect several underlying factors, including flat type, property size, remaining lease, location and the timing of transactions.
Average prices between towns should therefore be interpreted carefully, as the composition of flats sold may differ between locations.
Future analysis could control for these factors more systematically and incorporate additional variables such as proximity to MRT stations, amenities and other location characteristics.

## Future Improvements

As I continue developing my data science skills, some possible extensions to this project include:

* Incorporating MRT and geographical data
* Analysing proximity to amenities and transport
* Building more advanced predictive models
* Comparing different machine-learning algorithms
* Performing feature engineering to improve model performance
* Creating an interactive dashboard to explore HDB resale prices
* Conducting a more detailed analysis of housing affordability

## Repository

The full analysis, code and visualisations can be found in:

**`hdb_resale_analysis.ipynb`**

## Author

**Jenyasri senthil Kumar**

BSc Data Science and Business Analytics undergraduate

Interested in data science, analytics and using data to understand real-world problems.
