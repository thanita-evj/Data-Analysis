## IT Spend Analysis using Power BI

[itspend]: https://drive.google.com/file/d/1C87Sm7WkmqhxedKdhtYvWGUl-zs2Vsv-/view?usp=sharing

>[!NOTE]
**For a comprehensive analysis, please refer to this [Full Report][itspend] Document.**

### 1. Objective

The objective of IT spend analysis dashboard is to provide an overview of IT spending, including actual spending, budgeted amounts, forecasts, and variances across different IT departments. This dashboard aims to have better financial management for decision-making, which targets to present to IT manager, department head, and financial controller. 

### 2. Methodology

#### 2.1 Dataset

The analysis used IT spend dataset consists of seven tables and separated into four of lookup tables and three of data tables for the creation of dashboard’s relationship.  The table variables are described as below:

Lookup Tables

•	Table 1 – Cost Elements: Business Area, Cost Element, Cost Element Group

•	Table 2 – Departments: Dept. Manager, IT Area, IT Department

•	Table 3 – Region: Country, Region

•	Table 4 – Calendar: Date 

Data Tables

•	Table 5 – Budget: Budget, CostElement, Country, Date, IT Dep.  

•	Table 6 – Forecast: CostElement, Country, Date, Forecast, IT Dep.

•	Table 7 - Actuals: Date, CostElement, Country, Date, IT Department.

#### 2.2 Relationship between Tables

<img width="439" alt="Picture1" src="https://github.com/thanita-evj/Data-Analysis/assets/145984336/48966661-1118-4984-812b-b6d5b1cb69dc">

#### 2.3 Data Analysis Expression (DAX)

Running Total (RT), is the sum of a sequence of numbers that is updated whenever a new number is added to the sequence by adding the value of the new number to the previous running total. 

Running time is normally used to show the total sum of a variable on an ongoing basis tracking over time.  

### 3. Dashboard

#### 3.1 Dashboard Explanation

1) Slicer that is an interactive and affect the visuals in real-time by selecting or deselecting in the slicer.
2) Area chart between sum of actual and sum of budget by month, it shows the change of budget and actual spending over months.
3) KPI visual indicates the forecasted IT spending by date exceeds the planned budget or not.
4) Line chart of sum of actual, budget, and forecast by month, it compares the three different lines to see the alignment and difference between actual spending, budget amount, and forecasted spending over time.
5) Area chart of running total of actual, budget, and forecast by month, by comparing three areas to track the cumulative spending over time and see how closely actual spending aligns with budgeted and forecasted amounts.
6) Line and stacked column chart of the difference between total budget and forecast amounts (budget vs forecast) by month. Stacked column chart is used to compare the difference between budget and forecast amounts and line chart is used to show the percentage difference between the budget and forecast.
7) Horizontal bar chart of the difference between total budget and forecast amount by region, is used to present the deviation between budget and forecast spending across different regions.
8) Horizontal bar chart of the difference between total budget and forecast percentage by cost element group, is used to present the percentage difference between the budget and forecast amounts for each cost element group.
9) Horizontal bar chart of the difference between total budget and forecast percentage by IT area, is used to present the percentage difference between the budget and forecast amounts for each IT area. 

#### 3.2 Dashboard Findings

In 2020, the IT spend dashboard revealed that actual spending surpassed budgeted amounts, especially between January and May, with forecasting consistently higher than set budgets. Latin America dominated the budget allocation, while regions like Europe and North America trailed in budget-forecast alignment. Notably, administrative functions received the bulk of allocations, with Latin America's infrastructure category showing the most significant budget-forecast discrepancy.

#### 3.3 Recommendation

•	Review the budgeting to ensure more accurate alignment with actual spending, especially for the first half of the year when actual spending consistently exceeded the budget.

•	Reassess the forecasted amount that should provide more realistic estimate of expected spending and should be more closely with the budget.

•	Redistribute the budget across regions to be better align with the forecast for each region.


