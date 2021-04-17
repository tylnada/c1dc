# c1dc Trip
approches and problems statements

## ROI elements
  1. rental income - must
  2. home equity - optional
  3. depreciation - optional

## Data issues
* ### **Airbnb**
1. missing zipcodes
2. wait

* ### **Zillow**

## Check lists:
1. Missing data
  * missing zipcode - pygeocoder
3. Feature Selection:
    * Unsupervised: not using the target variable (e.g. remove redundant variables)
      * Correlation
    * Supervised: using the target variable (e.g. remove irrelevant variables)
      * Wrapper: Search for well-performing subsets of features.
        *  RFE
      * Filter: Select subsets of features based on their relationship with the target.
        * Statistical Methods
        * Feature Importance Methods
      * Intrinsic: Algorithms that perform automatic feature selection during training.
        * Decision Trees
        * Lasso
4. Feature engineering
    * Dimensionality Reduction
      * PCA 


#### references:
1. https://github.com/shivayogibeeradar/Capital-One-Data-Challenge
2. https://github.com/aadishchopra/CapitalOneDataChallenge/blob/master/data_analysis_documentation.pdf
3. https://machinelearningmastery.com/feature-selection-with-real-and-categorical-data/
