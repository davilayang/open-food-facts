# Explore Open Food Facts

Data Analysis on Open Food Facts dataset

## Dataset

Open Food Facts is a food products database made by everyone, for everyone.

+ [Open Food Facts - World](https://world.openfoodfacts.org/)
+ [Open Food Facts data](https://world.openfoodfacts.org/data)

### Dataset Features/Attributes

1. Product features
    + some basic information about the product
    + its code, name, food category, other labels, packaging style, its ingredients ...etc
    + its processing stats, its brand
2. Geography features
    + some geographical information
    + its origin, its manufacturing country, its circulation country
3. Main Nutrition features
    + i.e. table of Nutriction Facts
4. Other Nutrition-related features
    + all the attributes are normalzied to by every 100 gram, contains how much amount
5. Nutrition Rating features
    + different grading scheme, mainly 3 types

## Data Preprocessing

+ Subset on full dataset
+ Handling Missing Values
+ Handling Outliers with KMeans and boxplot

## Exploratory Analysis

+ What are the correlations between the main nutrients?
+ Are all sweets (sugary snacks) unhealthy?
+ What is the distribution of cocoa content among all chocolate products?
+ Are products with ‘Organic’ label necessary healthy?

## Modelling

+ Can we estimate cocoa content using regression model?
+ Can we classify the food products into binary category: healthy or unhealthy?
