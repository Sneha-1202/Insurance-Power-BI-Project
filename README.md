
## Insurance Data Analysis

## Project Statement

This dashboard gives the company a clearer picture of its customers. It shows which policy types are the most popular and among which age groups, helping the company refine its strategies. By identifying active and inactive customers, they can spot areas that need improvement and enhance their services. It also highlights different coverage amounts across policy types, giving insight into customer preferences and what drives their choices.Additionally, by using sentiment analysis, the company can interpret customer feedback and leverage these insights for more informed decision-making.

### Steps followed 

- Step 1 : Import  data from excel as it is a csv file to MS SQL server.
- Step 2:  Load data from MS SQL server to Power BI 
- Step 3 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 4: It was observed that in none of the columns errors & empty values were present except column named "Claim Date".
- Step 5 : Since by default, profile will be opened only for 1000 rows so we need to select "column profiling “ based on the entire dataset".
- Step 6: Three card visuals were added to show the total number of claim amount, premium amount and coverage amount .
- Step 7- Slicers were also added for policy number , claim number and customer id .
- Step 8 - Two new columns - Age Group and Active /Inactive customers were created for providing insights.
- Step 9 - Drill Through function created to show the impact of different policy types on the entire table.
- Step 10- Performed Row-Level-Security (RLS) for data privacy and security access.
- Step 11- Finding the score sentiments of the customer feedback using text analysis and then representing them visually.
- Step 12 - Publishing the report to Power BI Service.
