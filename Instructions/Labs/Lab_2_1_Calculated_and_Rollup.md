
# Lab 2.1: Create calculated and rollup fields 

## Scenario
Bellows College is an educational organization with multiple campuses and programs. Many of Bellow Colleges instructors and administrators need to attend events, and purchase items. Historically tracking these expenses has been a challenge.
Campus administration would like to modernize their expense reporting system by providing employees with a digital way to report expenses.
Ideally, they want their users to complete an Expense Report after each event or purchase. For each Expense Report, they want them to be able to add individual expense line items. They have already started working on this solution. The Expense Report table has been created. You have been asked to take over the project and complete it.

## High-level lab steps
Upon Successful completion of this lab, you will:
- Import a Solution into your environment that includes the Expense Report Table.
- Create Expense line-item table
- Add the necessary columns to the Expense line-item table
- Add some sample data.

## Prerequisites
- Completion of Module 1 Lab 0 - Validate lab environment

## Things to consider before you begin
- Naming conventions - enter names carefully.

## Exercise 1: Import the Expense Report solution into your environment
**Objective:** In this exercise, you will import the Expense Report solution that includes the Expense Report table.

### Task #1: Import the solution
The Expense Report table will contain information about the expense report that the individual is submitting.
1. If you are not already signed in, sign into *An external link was removed to protect your privacy.*
2. From the Environment menu in the top right, ensure in the environment you imported the Expense Report solution into.
3. Using the navigation on the left, select Solutions.
4. On the command bar at the top select Import Solution.
5. Select the Browse button.
6. Locate and select the `ExpenseReport_1_0_0_1` solution file that was in your course materials.
7. Select the Import button.

*Note: it can take several minutes for the solution to be imported into your environment.*

## Exercise 1: Create Calculated and Rollup fields
**Objective:** In this exercise, create a rollup field on the expense report table that adds up the total of all expense lines for the report.

### Task #1: Add a rollup field to the Expense Report table
1. If necessary, navigate to the Power Apps Maker Portal.
2. Make sure that you are working in the environment that you imported the Expense Report solution into during the last exercise.
3. Using the navigation on the left, select Solutions.
4. Locate and select the Expense Report solution.
5. Locate and open the Expense Report table.
6. Under the Schema Group, select Columns.
7. Select + New column.
8. Enter Report Total for Display name.
9. Select Currency for Data type.
10. In Required, select Optional.
11. In the Behavior field, select Rollup.
12. Select the Save button. (You need to save the column before you can configure it.)
13. Once the Column is saved, a pop-up window should appear. (If you get a pop-up message, you may need to allow pop ups)
14. Under RELATED ENTITY, select + Add related entity.
15. Select (Expense Lines) Expense Report.
16. Select the Check mark button to accept the change.
17. Under AGGREGATION, select + Add aggregation.
18. Set Aggregate Function to Sum.
19. Set Aggregated Related Entity Field to (Expense Line) Expense Amount.
20. Select the Save and Close button.

### Task #2: Add a Power FX Formula Calculated field to the Expense Report table
1. If necessary, navigate to the Power Apps Maker Portal.
2. Make sure that you are working in the environment that you imported the Expense Report solution into during the last exercise.
3. Using the navigation on the left, select Solutions.
4. Locate and select the Expense Report solution.
5. Locate and open the Expense Report table.
6. Under the Schema Group, select Columns.
7. Select + New column.
8. Enter Last Date for approval for Display name.
9. Select Formula for Data type.
10. Enter the following formula: `DateAdd(‘Report Due Date’,2)`
11. Set the Format field to Date Only.
12. Select the Save button. (You need to save the column before you can configure it.)
```

Feel free to copy and paste this markdown content wherever you need it! If you have any other requests or need further assistance, just let me know.
