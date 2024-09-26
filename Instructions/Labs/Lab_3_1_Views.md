---
lab:
    title: 'Lab 3.1: Visualize data with views'
---

# Lab 3.1: Visualize data with views

## Scenario

Bellows College is an educational organization with multiple campuses and programs. Many of Bellow Colleges instructors and administrators need to attend events, and purchase items. Historically tracking these expenses has been a challenge.

Campus administration would like to modernize their expense reporting system by providing employees with a digital way to report expenses.

Throughout this course, you will build applications and perform automation to enable the Bellows College employees to manage expenses.

## High-level lab steps

As part of creating the model-driven app, you will complete the following:

Create different views for viewing expense report elements.

We will work with the following components:

Views: Views allow the user to display the existing data in the form table.

## Prerequisites

Completion of Module 1 Lab 0 - Validate lab environment

## Exercise 1: Manage views

**Objective:** In this exercise, you will create a new view that can be used later in model-driven apps.

### Task #1: Edit the different Expense Lines views

1. If you are not already, sign in to https://make.powerapps.com
2. Select the environment that you imported the Expense Report solution into at the top right if it is not already selected.
3. Using the navigation on the left, select Solutions.
4. Open the Expense Report solution.
5. Locate and open the Expense Line table.
6. Under Data experiences, select Views.
7. Open the Active Expense Lines view.
8. Select View Column and from the menu that appears, select Expense Date:
9. Select View Column and from the menu that appears, select Item Description:
10. Repeat step nine to add the following columns:
    - Expense Type
    - Expense Amount
11. Locate and Select the Created On column, from the menu that appears select Remove.
12. Your view should have the Expense Title, Expense Date, Item Description, Expense Type and Expense Amount columns on it.
13. Select the Save and publish button.
14. Select the Back button to return to the list of views.

Next, we will repeat that process to update the Expense Line Associated View. This is the view that will appear when you are looking at Expense Lines from a parent table such as Expense Report.

1. Locate and open the Expense Line Associated view.
2. Select View Column and from the menu that appears, select Expense Date:
3. Select View Column and from the menu that appears, select Item Description:
4. Repeat step nine to add the following columns:
    - Expense Type
    - Expense Amount
5. Locate and Select the Created On column, from the menu that appears select Remove.
6. Your view should have the Expense Title, Expense Date, Item Description, Expense Type and Expense Amount columns on it.
7. Select the Save and publish button.
8. Select the Back button to return to the list of views.

Finally, we will repeat that process one more time to update the Quick Find Active Expense Lines View. This is the view that is used whenever a user uses the search field to look for a specific Expense Line.

1. Locate and open the Quick Find Active Expense Lines view.
2. Select View Column and from the menu that appears, select Expense Date:
3. Select View Column and from the menu that appears, select Item Description:
4. Repeat step nine to add the following columns:
    - Expense Type
    - Expense Amount
5. Locate and Select the Created On column, from the menu that appears select Remove.
6. Your view should have the Expense Title, Expense Date, Item Description, Expense Type and Expense Amount columns on it.
7. On the right side of the screen, in the Find by section, select Edit Find Table Columns.
8. Add the following columns:
    - Expense Date
    - Expense Type
9. Select the Apply button.
10. Select the Save and publish button.
11. Select the Back button to return to the list of views.

### Task #2: Edit the different Expense Reports views

1. If you are not already, sign in to https://make.powerapps.com
2. Select the environment that you imported the Expense Report solution into at the top right if it is not already selected.
3. Using the navigation on the left, select Solutions.
4. Open the Expense Report solution.
5. Locate and open the Expense Report table.
6. Under Data experiences, select Views.
7. Open the Active Expense Reports view.
8. Select View Column and from the menu that appears, select Report Purpose:
9. Select View Column and from the menu that appears, select Report Due Date:
10. Repeat step nine to add the following columns:
    - Report Total
    - Last Date for Approval
11. Locate and Select the Created On column, from the menu that appears select Remove.
12. Your view should have the Report Purpose, Report Due Date, Report Total, and Last Date for Approval columns on it.
13. Select the Save and publish button.
14. Select the Back button to return to the list of views.

Next, we will repeat that process to update the Inactive Expense Reports view.

1. Locate and open the Inactive Expense Reports view.
2. Select View Column and from the menu that appears, select Report Purpose:
3. Select View Column and from the menu that appears, select Report Due Date:
4. Repeat step nine to add the following columns:
    - Report Total
    - Last Date for Approval
5. Locate and Select the Created On column, from the menu that appears select Remove.
6. Your view should have the Report Purpose, Report Due Date, Report Total, and Last Date for Approval columns on it.
7. Select the Save and publish button.
8. Select the Back button to return to the list of views.

Finally, we will repeat that process one more time to update the Quick Find Active Expense Reports View. This is the view that is used whenever a user uses the search field to look for a specific Expense Report.

1. Locate and open the Quick Find Active Expense Reports view.
2. Select View Column and from the menu that appears, select Report Purpose:
3. Select View Column and from the menu that appears, select Report Due Date:
4. Repeat step nine to add the following columns:
    - Report Total
    - Last Date for Approval
5. Locate and Select the Created On column, from the menu that appears select Remove.
6. Your view should have the Report Purpose, Report Due Date, Report Total, and Last Date for Approval columns on it.
7. On the right side of the screen, in the Find by section, select Edit Find Table Columns.
8. Add the Report Purpose column.
9. Select the Apply button.
10. Select the Save and publish button.
11. Select the Back button to return to the list of views.

### Task #3: Create a new view called Expenses Reports Due today

1. If you are not already, sign in to https://make.powerapps.com
2. Select the environment that you imported the Expense Report solution into at the top right if it is not already selected.
3. Using the navigation on the left, select Solutions.
4. Open the Expense Report solution.
5. Locate and open the Expense Report table.
6. Under Data experiences, select Views.
7. Open the Active Expense Reports view.
8. Select the Save As button.
9. Change the Name to Expense Reports Due Today.
10. Select the Save button.
11. In the Filter By section, select Edit filters.
12. Select the Add button, from the menu that appears, select Add Row.
13. Select the drop-down arrow in the first blank row, from the menu that appears, select the Report Due Date column.
14. Change the Equals field to Today.
15. Select the OK button.
16. Select the Save and Publish button.
