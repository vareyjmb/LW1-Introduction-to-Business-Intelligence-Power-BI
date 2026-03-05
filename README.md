PART 1: Launching Power BI & Loading Data
Step 1: Open Power BI Desktop
● Click Start
● Open Microsoft Power BI Desktop
● Wait for the startup screen
![part1](https://github.com/user-attachments/assets/b6293f32-52c3-4bf0-98dc-8715ac3547a6)

PART 1: Launching Power BI & Loading Data
Step 2: Load the Dataset
1. Click Home Tab
2. Click Get Data
3. Select Text/CSV
4. Browse and select:
Week1_Basic_Sales_Data.csv
5. Click Load
6. ![part1-a](https://github.com/user-attachments/assets/f71b04be-8db1-4da2-b0a9-384716c0c23d)

PART 1: Launching Power BI & Loading Data
Step 3: Verify Data in Data View1. Click the Data View icon (table icon on the left)2. Check:
○ Are all columns visible?
○ Is “Date” formatted as Date?
○ Is “Sales” formatted as Decimal Number?
If Data Type is Incorrect:
1. Click the column2. Go to Column Tools3. Change Data Type accordingly:
○ Date → Date○ Sales → Decimal Number○ Product/Category/Region → Text
![part1 b](https://github.com/user-attachments/assets/9e9d64a4-44b9-499b-922c-b242caf97938)

PART 2: Exploring the Interface
![part2-dataview](https://github.com/user-attachments/assets/bbbe38aa-ee4f-4bd8-8d57-631bc4c88a0c)
![part2-modelview](https://github.com/user-attachments/assets/26507971-9fc9-4263-83d8-bacacadfb606)
![part2-reportview](https://github.com/user-attachments/assets/56624780-21d5-4309-b486-8fd44238e13e)

PART 3: Creating Auto-Generated Visuals
Step 1: Quick Visualization1. Drag Sales into canvas2. Power BI automatically creates a visualQuestion:
   ![sum-of-sales](https://github.com/user-attachments/assets/f8df6c7f-4314-404b-8302-72bb483e862e)
● What type of chart was created?
 - The chart shows Sum of Sales ≈ 0.2M (200,000+).
● What does it show?
  -Power BI automatically aggregated Sales using SUM, showing the total sales of the dataset.

PART 3: Creating Auto-Generated Visuals
Step 2: Create a Sales by Region Chart
1. Click blank canvas
2.  Select Clustered Column Chart
3. Drag:
○ Region → X-axis○ Sales → ValuesQuestion:
![sales-by-region](https://github.com/user-attachments/assets/0da990aa-c86f-4b7e-aadf-ed2d1b9f5ea2)
● Which region has highest sales?
-According to the chart, it shows that the West Region has the highest sales

PART 3: Creating Auto-Generated Visuals
Step 3: Sales by Category
1. Insert a Pie Chart
2. Drag:
○ Category → Legend○ Sales → Values
![sales-by-category](https://github.com/user-attachments/assets/b375248a-57ac-40c9-8c5d-3f24d50fee21)
Question:● Which category dominates?
-  Electronics by 40.82%
● Is the distribution balanced?
-  I would say no since the North only got 19.99% compare toothers 40.82% and 39.19%

PART 3: Creating Auto-Generated Visuals
Step 4: Sales Over Time
1. Insert Line Chart
2. Drag:
○ Date → X-axis○ Sales → Values
![line-chart](https://github.com/user-attachments/assets/f6bbd476-47ce-4246-a48e-36582fbbfac6)
Question:● Is there growth?
-No, since the line chart is going down
● Any noticeable trend?
-No noticeable trend

PART 4: Basic Data Insight InterpretationQuestion:
● Which region contributes most revenue?
- The region that contributes most revenue is West Region
● Which product category performs best?
- TheElectronics category
● Are sales consistent across dates?
-I would say no since the North only got 19.99% compare to others 40.82% and 39.19%
● What business recommendation can you suggest?
-I would recommend the Office Supplies

LABORATORY QUESTIONS
Part A – Technical Questions
1. What are the five columns in the dataset?
-Date, Product, Category, Region, Sales 
2. What data type is assigned to the “Sales” column?
- Decimal Number
3. Which Power BI view allows you to see raw data?
- data view
4. What chart type is best for showing trends over time?
- line chart
5. What aggregation is automatically applied to Sales?
- SUM (sumof sales)

Part B – Analytical Questions  

6. Which region has the highest total sales?-West region. From the sorted bar chart , West has the tallest bar, followed closely by East, then South, with North recording the lowest figures.
7.Which category has the lowest performance?
-Office Supplies. The pie chart shows it accounts for only 19.99% (~44K) of total sales, compared to Electronics (40.82%, ~90K) and Furniture (39.19%, ~86K).
8. Are sales increasing, decreasing, or stable?
-Decreasing over the observed period. The line chart (p. 9) shows a steep downward slope from ~0.2M in 2024 to near zero in 2025, indicating a significant sales drop — likely due to incomplete 2025 data.
9. If you were a manager, which region would you prioritize?
-North region should be prioritized for investigation and improvement, as it is the weakest performer. West and East should be studied as best-practice regions to replicate their success strategies.
10. Provide one actionable recommendation based on the data.
Shift marketing and sales focus from Office Supplies to Electronics and Furniture (~80% of revenue). In the North region, replicate the West region's sales strategy.

ENHANCEMENT SECTION
Advanced ExplorationStudents must perform the following:
Task 1: Add a Card Visualization1.
Insert Card2.
Drag Sales3. Format:
○ Increase font size○ Change title to “Total Sales”
![total-sales](https://github.com/user-attachments/assets/fc800019-4658-4ecd-bf81-1569c0460e20)

Question:● What is the total sales amount?
- Total Sales amount: 220k











