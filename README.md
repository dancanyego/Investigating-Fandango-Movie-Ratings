# Is Fandango Still Inflating Ratings?

## Project Overview
In this project, we analyze recent movie ratings data to determine if Fandango’s rating system has changed since Walt Hickey's analysis in 2015. By comparing two data samples — one collected before Hickey's study and one after — we investigate whether Fandango's ratings for popular movies in 2016 differ from those in 2015.

## Dataset Information
We work with two datasets:
1. **Before Hickey’s Analysis**: `fandango_score_comparison.csv` (Movies released in 2015)
2. **After Hickey’s Analysis**: `movie_ratings_16_17.csv` (Movies released in 2016 and 2017)

### Columns in the Datasets:
- **Fandango Ratings**: Star ratings for each movie on Fandango.
- **Other Ratings**: Ratings from other sources like RottenTomatoes, Metacritic, and IMDb.

## Analysis Process

### 1. Initial Data Exploration
We loaded the data and examined the structure to understand key columns and ensure data integrity. Only columns relevant to Fandango’s ratings were selected for comparison.

### 2. Redefining the Research Goal
Our goal shifted to determine if Fandango's ratings for popular movies differed between 2015 and 2016.

### 3. Data Preparation
- **2015 Data**: Extracted movies released in 2015 from the `fandango_score_comparison.csv` dataset.
- **2016 Data**: Extracted movies released in 2016 from the `movie_ratings_16_17.csv` dataset.

### 4. Analyzing Distribution Shapes
We compared the distributions of ratings for 2015 and 2016 using kernel density plots. Results revealed that while both distributions are left-skewed, the 2016 ratings distribution is slightly shifted to the left.

### 5. Statistical Comparison
We computed summary statistics (mean, median, mode) for both years and created visual comparisons using bar charts.

## Key Findings
- **Slight Decrease in Ratings**: On average, popular movies released in 2016 were rated lower than those in 2015. The mean rating dropped by 0.2 stars (approximately 5%).
- **High Ratings Declined**: In 2016, fewer movies received the highest ratings (4.5 and 5 stars) compared to 2015.

## Conclusion
Our analysis suggests that Fandango’s ratings for popular movies in 2016 were slightly lower than in 2015. This might be due to adjustments made after Hickey’s critique of Fandango’s inflated rating system.

## Visualizations
- **Kernel Density Plot**: Comparing the distribution of Fandango ratings in 2015 vs. 2016.
- **Bar Charts**: Showing the mean, median, and mode ratings for each year.

![image](https://github.com/user-attachments/assets/d233e59e-bdd1-45ec-b312-e2c488d0c949)

![image](https://github.com/user-attachments/assets/de676191-4000-4110-b6c0-fe92f55d4cd2)

