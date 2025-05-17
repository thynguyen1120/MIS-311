1. Data Overview
The dataset contains 202 rows and 4 columns: brand, color, size, and price. It represents shoe retail data, likely from an e-commerce platform, with prices ranging from $80 to $350. The data supports analysis of pricing patterns and market positioning.

2. Data Cleaning
Missing Values:
The dataset contained only a very small number of missing values (one row missing a price, and one row missing a color). Since these account for less than 1% of the total data, removing these rows has a negligible impact on overall analysis and avoids potential bias from imputing or guessing values. This approach ensures the remaining data is complete and reliable.

Outlier Removal (Size 41):
The value 41 in the size column is an extreme outlier, as the vast majority of shoe sizes in the dataset range from 2 to 13. Retaining this outlier would distort the descriptive statistics (such as mean and standard deviation) and reduce the accuracy of insights about typical customers. Therefore, this value was removed to better reflect the main market segment.

Duplicate Values:
Three duplicate rows were found and removed to ensure each entry in the dataset represents a unique product record. This was performed in Excel by selecting the entire data table, navigating to the Data tab on the ribbon, and clicking Remove Duplicates. This step guarantees that statistical analysis is not skewed by repeated data.

Data Type Verification:
Confirmed that size and price columns are of numeric data types for correct calculation and charting.

These data cleaning steps ensure the quality, accuracy, and reliability of the analysis results.

3. Descriptive Statistics
Price: Mean = $212.23, Median = $212, Min = $80, Max = $350, Std Dev = $78.89

Size: Mean = 7.26, Median = 7, Min = 2, Max = 13, Std Dev = 2.61

Pivot Table (Average Price by Brand):

Franco Leone (~$224.65)

Tresmode (~$223.92)

Hush Puppies (~$219.50)

Crocs (~$212.39)

4. Insights
Insight 1: Average Price by Brand (Bar Chart)
Franco Leone has the highest average price (~$224.65), exceeding the overall mean ($212.23), indicating a premium brand. Retailers should promote Franco Leone to high-spending customers to maximize profits.

Insight 2: Price Distribution (Histogram)
Most shoes are priced between $150–$250 (median $212), showing a focus on the mid-range market. Retailers should prioritize stocking shoes in this price range to meet mainstream customer demand.

5. Visualizations
Figure 1: Average Price by Brand (Bar Chart, in "Brand_Analysis" sheet).

Figure 2: Price Distribution (Histogram, bins $0–400, in "Stats" sheet).

6. Interesting Fact
Crocs prices range from $86 to $327, showing unexpected diversity for what is usually considered an affordable brand.

7. Conclusion
Franco Leone is positioned as a premium brand, while the overall market emphasizes mid-range prices ($150–$250).
Retailers can optimize marketing and inventory by targeting affluent customers with premium brands and ensuring sufficient stock of popular mid-range shoes.
