
# SpendWise - Week 6 Web Development Assignment

## Project Description

SpendWise is an interactive budget tracking application
developed using HTML, CSS and JavaScript.

It helps users manage their monthly budgets, record
expenses and monitor their spending.

## Improvements Made This Week

I improved SpendWise by adding interactive features.

The application now allows users to:

- Set and update a monthly budget.
- Add new expenses.
- Delete existing expenses.
- Calculate total expenses automatically.
- View their remaining balance.
- Receive budget warning messages.
- Filter expenses by category.
- Save information using localStorage.

## 1. Conditional Statements

I used if, else if and else statements to make decisions.

For example, when expenses exceed the monthly budget,
the application displays a warning message.

It also warns users when they have used 80% of their budget.

## 2. Arrays

I used an array called expenses to store multiple
expense records.

Each record contains an expense name, amount,
category, date and unique ID.

I used push() to add expenses and filter() to
remove records or filter expenses by category.

## 3. Loops

I used for loops to process expense records.

The loops calculate the total expenses and display
all records in the expense table.

## 4. DOM Manipulation

I used DOM manipulation to update the webpage
without refreshing the browser.

The dashboard displays the monthly budget, total
expenses, remaining balance and budget messages.

I used getElementById(), createElement(),
appendChild() and textContent.

## 5. Event Listeners

I used addEventListener() to respond to user actions.

Users can add expenses, update their budget,
delete expenses and filter records.

## 6. Challenges and Solutions

One challenge was updating the dashboard after
adding or deleting expenses.

I solved this by creating functions to calculate
expenses and update the dashboard automatically.

Another challenge was keeping information after
refreshing the webpage.

I solved this by using localStorage to save
the budget and expense records.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Browser localStorage

## How to Run the Project

1. Download or clone the repository.
2. Open the project folder.
3. Open index.html in a web browser.
4. Set your monthly budget.
5. Add expenses and monitor your spending.

## Conclusion

This project helped me understand how JavaScript
makes websites interactive.

I learned how to use variables, arrays, loops,
conditional statements, DOM manipulation and
event listeners in a practical project.
