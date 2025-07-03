# DSA-Capstone-Project-POWER-BI
Data cleaning, transformation, visualization, and modelling using Power Bi.
# Case Study 3: Palmora Group HR Analysis
 ## Overview
You are acting as an HR Analytics expert for Palmora Group, a manufacturing company in Nigeria that’s facing media backlash for gender inequality. You're hired to investigate and help address issues like gender distribution, pay gaps, and performance-based bonuses.
Dataset: The employee dataset includes (Name, gender, region, department, salary, rating), Bonus rules provided in a separate file (based on performance rating and department)
## Analysis Tasks
You are expected to: analyse gender distribution overall, by region and department. Compare performance ratings by gender. Identify gender pay gaps and where they occur (by region & department). Analyse salary distribution, who earns above or below $90,000? Create salary bands (e.g., $10k–$20k). Visualize by region. Calculate bonus amounts: based on rating and department. Compute total bonus per employee and per region.
## Methods used
Load the employee dataset (.csv) and bonus rule table (.xlsx) into Power BI. Handle missing values (especially in salary, gender, rating). Standardize text entries (e.g., gender capitalization). Remove duplicates and irrelevant records.
### Create calculated fields:	BonusKey: (combine Department and Rating to link with Bonus Rules.), Bonus Amount: (Salary × Bonus%), Total Pay: (Salary + Bonus), Salary Bands: categorize salary into defined brackets. Build relationships between Employee Table & Bonus Rules Table (using Rating or BonusKey).
### Analyse: Gender distribution (overall, by region, by department), Pay differences by gender, Rating comparisons by gender, Bonus distribution and total payout by region through the creation of visuals like Bar and pie charts for gender, department, and region, Boxplots or histograms for salary distribution, Matrix/table for total bonus per region. Assemble final dashboard for executive insights.

