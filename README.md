# Data Analyst Associate Case Study: Data Validation and Discovery

## Data Validation

The dataset underwent a thorough data validation process, ensuring the accuracy and appropriateness of data types for analysis:

- **Claim ID**: Converted from `object` to `character` type.
- **Time to Close**: Changed from `int64` to `numeric` to accommodate a broader range of values.
- **Claim Amount**: Transformed from `object` to `numeric` for accurate financial analysis.
- **Amount Paid**: Modified from `float64` to `numeric` for consistency in financial data.
- **Location**: Updated from `object` to `character` to reflect the nature of the data accurately.
- **Individuals on Claim**: Changed from `int64` to `numeric` to include all relevant entities.
- **Linked Cases**: Maintained as `binary`/`bool` to represent the presence or absence of linked cases.
- **Cause**: Updated from `object` to `character` for clear categorization.

Additional observations included:

- No duplicate records were found, ensuring data uniqueness.
- Data covered the total number of days to close each case, the claim amount, amount paid, and the number of individuals for each claim.
- Identified 4 locations with varying numbers of cases and 9 instances of linked cases.
- Causes of claims predominantly revolved around food poisoning, with meat and vegetables being the most common sources.

## Data Discovery and Visualization

### Claims Distribution Across Locations

- The analysis included a total of 98 cases across 4 locations. Sao Luis led with 30 cases, followed by Recife (25), Fortaleza (22), and Natal (21).

### Time to Close Claims

- A significant decrease in the time to close claims was observed from 2010 to 2020, with the longest case in 2010 taking 3591 days to close, compared to 349 days in 2020.

### Average Time to Close Claims by Location

- Sao Luis recorded the highest average time to close at 1030 days, followed by Recife, Fortaleza, and Natal, showcasing variations in processing efficiency across locations.

### Year-on-Year Performance

- From 2016 to 2020, a year-on-year improvement in the average time to close cases was observed across three locations, with Natal showing a unique trend of improvement after a spike in 2017.

### Cause of Claims and Settlement Costs

- A noteworthy point is that 78 of the 98 cases had 'unknown' listed as the cause of food poisoning, indicating a gap in data recording. Since 2016, claim settlement costs have seen a significant rise, highlighting the need for detailed investigation into each case to potentially reduce claims and associated costs.

## Conclusion

This case study underscores the importance of data validation, the insightful analysis of claim distributions and processing times, and the impact of detailed cause analysis on managing and reducing claim settlement costs. The findings suggest areas for further investigation and potential operational improvements within the legal team's processes.
