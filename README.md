# Marketing_Data_Optimization
This project focuses on enhancing product data by cleaning inconsistencies, handling missing values, standardizing attributes, and optimizing product titles for better readability, usability, and SEO performance. The dataset includes product IDs, descriptions, bullet points, and dimensions.

## Objectives
- Improve data quality by cleaning inconsistencies and handling missing values.
- Standardize and structure product attributes for better usability.
- Optimize product titles for better clarity and search engine visibility.

  ## Data Cleaning Steps
- Removed duplicates using the `PRODUCTID`.
- Handled missing values in key fields like `TITLE`, `BULLET_POINTS`, and `DESCRIPTION`.
- Standardized text formatting (capitalization, removal of special characters).
- Replaced unnecessary blanks with ‘Not Applicable’.
- Validated `PRODUCT TYPE ID` and `PRODUCT LENGTH`.

## Data Preparation Steps
- Extracted key phrases from `BULLET_POINTS` and `DESCRIPTION`.
- Structured fields by categorizing product types.
- Normalized `PRODUCT LENGTH` for uniformity.
- Cleaned extra spaces and trailing characters using Excel formulas like `SUBSTITUTE` and `TRIM`.

## Title Optimization
- Made titles concise and informative with key details (Brand, Category, Attributes).
- Maintained 30–50 character limits for better visibility.
- Used `PROPER()` function to capitalize titles.
- Removed unnecessary symbols to enhance readability.

## Reporting and Insights
- Presented a clean dataset with optimized titles and structured attributes.
- Showcased before-and-after comparisons of `TITLE`, `BULLET_POINTS`, and `DESCRIPTION`.
- Excel formulas were used to automate and accelerate data transformation.

## Conclusion
These steps improved the overall quality of the dataset, making it more usable, engaging, and consistent across platforms. The optimization ensures better discoverability and a more professional presentation of product data.

## Visualizations

### Before and After – Title Column
https://github.com/SHALOM-1434/Marketing_Data_Optimization/commit/44b2fbe25f45a68d811ba40fff3ae08e98238d04

### Before and After – Bullet Points

### Before and After – Description Column




