# Extended Practice: Thinking with Python

This file contains **additional practice problems (11–50)** for the book  
_**Python – Start Here**_.

These problems reinforce the same reasoning patterns introduced in **Chapter 15** using more varied and realistic scenarios.

You are **not expected to complete all of them at once**. Use them for:

- revision
- confidence building
- interview preparation
- deeper thinking practice

## Problem 11: Average Household Size

Census surveys collect household size data.

**Input:**
Household member counts

**Sample Input Data:**
[3, 5, 4, 2]

**Task:**
Calculate average household size

**Constraints:**
Values are positive integers

**Sample Output:**
3.5

## Problem 12: Ranking Sales Performance

Sales performance is compared across regions.

**Input:**
Region-to-sales mapping

**Sample Input Data:**
{"East": 12000, "West": 18000, "North": 15000}

**Task:**
Rank regions from highest to lowest sales

**Constraints:**
Sales values are numeric

**Sample Output:**
["West", "North", "East"]

## Problem 13: Detecting Missing Data

Incomplete datasets must be evaluated.

**Input:**
List containing values and None

**Sample Input Data:**
[12, None, 8, None, 15]

**Task:**
Count valid (non-missing) entries

**Constraints:**
None indicates missing data

**Sample Output:**
3

## Problem 14: Rule-Based Transaction Classification

Transaction sizes are grouped by thresholds.

**Input:**
Transaction amounts

**Sample Input Data:**
[250, 1200, 5600]

**Task:**
Label amounts as Small, Medium, or Large

**Constraints:**
Thresholds are predefined

**Sample Output:**
["Small", "Medium", "Large"]

## Problem 15: Weekly Step Summary

Fitness trackers summarize daily activity.

**Input:**
Daily step counts

**Sample Input Data:**
[4500, 7000, 8000, 6000, 7500]

**Task:**
Calculate total and average steps

**Constraints:**
Steps are non-negative

**Sample Output:**
{"total": 33000, "average": 6600}

## Problem 16: Data Consistency Check

Paired values must follow logical rules.

**Input:**
List of (min, max) pairs

**Sample Input Data:**
[(2, 5), (10, 7), (3, 9)]

**Task:**
Identify invalid pairs

**Constraints:**
min should not exceed max

**Sample Output:**
[(10, 7)]

## Problem 17: Counting Category Frequencies

Sales data contains repeated categories.

**Input:**
Product categories list

**Sample Input Data:**
["Food", "Clothing", "Food", "Electronics"]

**Task:**
Count frequency of each category

**Constraints:**
Categories are strings

**Sample Output:**
{"Food": 2, "Clothing": 1, "Electronics": 1}

## Problem 18: Population Percentage Share

District populations must be compared.

**Input:**
District population mapping

**Sample Input Data:**
{"A": 2000, "B": 3000, "C": 5000}

**Task:**
Compute percentage share per district

**Constraints:**
Total is sum of all values

**Sample Output:**
{"A": 20, "B": 30, "C": 50}

## Problem 19: Identifying Above-Average Scores

Class performance analysis requires comparisons.

**Input:**
Exam scores list

**Sample Input Data:**
[55, 65, 70, 40, 90]

**Task:**
Identify scores above the class average

**Constraints:**
Average is computed from the same list

**Sample Output:**
[65, 70, 90]

## Problem 20: Safe Numeric Processing

Real data may contain invalid entries.

**Input:**
Mixed-value list

**Sample Input Data:**
[10, "NA", 5, None, 20]

**Task:**
Process only valid numeric values

**Constraints:**
Ignore invalid entries

**Sample Output:**
[10, 5, 20]

## Problem 21: Monthly Expense Aggregation

Expenses are grouped by category.

**Input:**
(category, amount) pairs

**Sample Input Data:**
[("Food", 1200), ("Travel", 3000), ("Food", 800)]

**Task:**
Compute total expense per category

**Constraints:**
Amounts are positive

**Sample Output:**
{"Food": 2000, "Travel": 3000}

## Problem 22: Flagging Outliers

Measurements may exceed safe limits.

**Input:**
Measurement list

**Sample Input Data:**
[45, 78, 120, 65]

**Task:**
Identify values above limit (100)

**Constraints:**
Limit is fixed

**Sample Output:**
[120]

## Problem 23: Attendance Risk Indicator

Attendance percentages indicate risk.

**Input:**
Attendance percentages

**Sample Input Data:**
[92, 68, 75, 45]

**Task:**
Label each as "Normal" or "At Risk"

**Constraints:**
Risk threshold is predefined

**Sample Output:**
["Normal", "At Risk", "Normal", "At Risk"]

## Problem 24: Loan Application Filtering

Applications must meet multiple conditions.

**Input:**
List of application records

**Sample Input Data:**
[{"income": 40000, "credit": 720}, {"income": 25000, "credit": 680}]

**Task:**
Select applications meeting all criteria

**Constraints:**
Conditions are numeric comparisons

**Sample Output:**
[{"income": 40000, "credit": 720}]

## Problem 25: Building a Summary Report

Analysts often produce compact summaries.

**Input:**
Daily visitors list

**Sample Input Data:**
[120, 150, 130]

**Task:**
Produce total, average, max, min

**Constraints:**
Use core Python only

**Sample Output:**
{"total": 400, "average": 133.33, "max": 150, "min": 120}

Perfect — continuing **Exercise 26 → Exercise 50** in the **same exact locked format**, with **no deviation**.

## Problem 26: Currency Conversion

Travelers need to understand prices in their home currency.

**Input:**
Foreign currency prices and exchange rate

**Sample Input Data:**
Prices: [10, 25, 40], Rate: 82

**Task:**
Convert each price into home currency

**Constraints:**
Single exchange rate applies to all items

**Sample Output:**
[820, 2050, 3280]

## Problem 27: Temperature Alert Classification

Server rooms must stay within safe temperature limits.

**Input:**
Single temperature reading

**Sample Input Data:**
32

**Task:**
Classify temperature as "Safe", "Warning", or "Critical"

**Constraints:**
Warning ≥ 25°C, Critical ≥ 30°C

**Sample Output:**
"Critical"

## Problem 28: Student Pass–Fail Count

Schools track pass and fail statistics.

**Input:**
Exam score list

**Sample Input Data:**
[45, 67, 82, 39, 50]

**Task:**
Count how many students passed and failed

**Constraints:**
Passing score is 50

**Sample Output:**
{"pass": 3, "fail": 2}

## Problem 29: Grocery Budget Check

Households track spending against a budget.

**Input:**
Item prices and monthly budget

**Sample Input Data:**
Prices: [120, 340, 560], Budget: 900

**Task:**
Calculate remaining or exceeded budget

**Constraints:**
Prices are non-negative

**Sample Output:**
{"total": 1020, "exceeded_by": 120}

## Problem 30: Shipping Weight Validation

Shipping categories depend on package weight.

**Input:**
Package weights list

**Sample Input Data:**
[12, 18, 22, 9]

**Task:**
Filter packages eligible for standard shipping (< 20 kg)

**Constraints:**
20 kg is excluded

**Sample Output:**
[12, 18, 9]

## Problem 31: Sentiment Keyword Counter

Feedback tags are scanned for sentiment.

**Input:**
Feedback tag list

**Sample Input Data:**
["Excellent", "Poor", "excellent", "Good"]

**Task:**
Count positive ("Excellent") and negative ("Poor") tags

**Constraints:**
Case-insensitive comparison

**Sample Output:**
{"excellent": 2, "poor": 1}

## Problem 32: Sales Tax Application

Retail prices must include tax.

**Input:**
Product prices and tax rate

**Sample Input Data:**
Prices: [100, 250], Tax Rate: 5%

**Task:**
Compute final prices including tax

**Constraints:**
Uniform tax rate

**Sample Output:**
[105, 262.5]

## Problem 33: Membership Eligibility

Organizations classify members by age.

**Input:**
Birth years list

**Sample Input Data:**
[2005, 1998, 2012]

**Task:**
Label each as "Minor" or "Adult"

**Constraints:**
Current year is 2026, Adult ≥ 18

**Sample Output:**
["Adult", "Adult", "Minor"]

## Problem 34: Sensor Range Normalization

Sensor data may contain impossible values.

**Input:**
Humidity readings

**Sample Input Data:**
[-5, 45, 110, 80]

**Task:**
Replace invalid readings with 0

**Constraints:**
Valid range is 0–100

**Sample Output:**
[0, 45, 0, 80]

## Problem 35: Attendance Percentage

Weekly attendance summaries are required.

**Input:**
Attendance log (True/False)

**Sample Input Data:**
[True, True, False, True, False]

**Task:**
Calculate attendance percentage

**Constraints:**
Week has 5 working days

**Sample Output:**
60.0

## Problem 36: Inventory Shortage Detection

Stores must identify low-stock items.

**Input:**
Inventory dictionary

**Sample Input Data:**
{"Rice": 3, "Oil": 12, "Sugar": 5}

**Task:**
Identify items needing restock (≤ 5)

**Constraints:**
Return item names only

**Sample Output:**
["Rice", "Sugar"]

## Problem 37: Unique Visitor Count

Web analytics track distinct visitors.

**Input:**
Visitor ID list

**Sample Input Data:**
[101, 102, 101, 103, 102]

**Task:**
Count unique visitors

**Constraints:**
Use core Python only

**Sample Output:**
3

## Problem 38: Average Rainfall Summary

Weather reports use average rainfall.

**Input:**
Rainfall measurements

**Sample Input Data:**
[5.2, 0.0, 12.3, 7.5]

**Task:**
Calculate average rainfall

**Constraints:**
Handle empty list safely

**Sample Output:**
6.25

## Problem 39: Password Length Validation

User inputs must meet length rules.

**Input:**
Password list

**Sample Input Data:**
["hello", "secure123", "admin"]

**Task:**
Label each password as "Valid" or "Too Short"

**Constraints:**
Minimum length is 8

**Sample Output:**
["Too Short", "Valid", "Too Short"]

## Problem 40: Price Discount Logic

Stores apply conditional discounts.

**Input:**
Item prices

**Sample Input Data:**
[80, 150, 300]

**Task:**
Apply discount based on price tiers

**Constraints:**

> 100 → 10%, otherwise 5%

**Sample Output:**
[76, 135, 270]

## Problem 41: Survey Score Distribution

Survey ratings must be summarized.

**Input:**
Score list (1–5)

**Sample Input Data:**
[5, 4, 3, 5, 2, 5]

**Task:**
Count frequency of each score

**Constraints:**
Scores range from 1 to 5

**Sample Output:**
{1: 0, 2: 1, 3: 1, 4: 1, 5: 3}

## Problem 42: Product Name Search

Search systems match keywords.

**Input:**
Product name list and search term

**Sample Input Data:**
Products: ["Smartphone", "Headphone", "Laptop"], Term: "phone"

**Task:**
Return matching product names

**Constraints:**
Partial match allowed

**Sample Output:**
["Smartphone", "Headphone"]

## Problem 43: Delivery Zone Assignment

Delivery fees depend on distance.

**Input:**
Distance list

**Sample Input Data:**
[3, 8, 20]

**Task:**
Assign delivery zones

**Constraints:**
Zone 1: 0–5, Zone 2: 5–15, Zone 3: >15

**Sample Output:**
["Zone 1", "Zone 2", "Zone 3"]

## Problem 44: Peak Value Identification

Extreme values indicate peaks.

**Input:**
Numeric list

**Sample Input Data:**
[45, 82, 67, 99, 71]

**Task:**
Find the maximum value manually

**Constraints:**
Do not use built-in max()

**Sample Output:**
99

## Problem 45: Email Domain Extraction

Marketing teams analyze email providers.

**Input:**
Email address list

**Sample Input Data:**
["[a@gmail.com](mailto:a@gmail.com)", "[b@yahoo.com](mailto:b@yahoo.com)"]

**Task:**
Extract email domains

**Constraints:**
Emails are valid

**Sample Output:**
["gmail.com", "yahoo.com"]

## Problem 46: GPA Calculation

Academic performance is summarized numerically.

**Input:**
Letter grade list

**Sample Input Data:**
["A", "B", "C", "A", "F"]

**Task:**
Convert grades to points and compute average

**Constraints:**
Ignore unrecognized grades

**Sample Output:**
2.6

## Problem 47: Transaction Sanitization

Financial logs contain missing values.

**Input:**
Transaction list with None

**Sample Input Data:**
[1200, None, -500, None, 300]

**Task:**
Remove invalid entries

**Constraints:**
Preserve original order

**Sample Output:**
[1200, -500, 300]

## Problem 48: Top Performer Identification

Organizations reward top contributors.

**Input:**
Sales dictionary

**Sample Input Data:**
{"Amit": 120, "Riya": 180, "Kunal": 150}

**Task:**
Identify top performer

**Constraints:**
No ties exist

**Sample Output:**
"Riya"

## Problem 49: Simple Data Masking

Sensitive IDs are lightly transformed.

**Input:**
Numeric ID list

**Sample Input Data:**
[1, 4, 9]

**Task:**
Increment digits with wraparound

**Constraints:**
9 wraps to 0

**Sample Output:**
[2, 5, 0]

## Problem 50: Multi-Metric Traffic Report

Analysts summarize traffic trends.

**Input:**
Daily website visitors list

**Sample Input Data:**
[120, 150, 130, 160]

**Task:**
Compute total, average, highest, and lowest values

**Constraints:**
Use core Python only

**Sample Output:**
{"total": 560, "average": 140, "max": 160, "min": 120}

## How to Use This Practice Pack

- Attempt problems without looking at solutions
- Write clear, readable Python
- Focus on correctness and reasoning, not clever tricks
- Revisit earlier problems after gaining confidence

These exercises exist to strengthen **judgment**, not syntax speed.

_End of Extended Practice_
