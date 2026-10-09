1.Title
Micro-Savings App with Goal Tracking for Personal Finance
2. Domain
Finance / Personal Budgeting / Data Analytics
3. Who is the user?
1. User (Individual)
Records daily expenses.
Views total spending and savings.
Tracks financial habits.
Sets savings goals and monitors progress.
Receives insights about spending patterns.
4. What problem are we solving?
Many individuals do not maintain a proper record of their daily expenses.
As a result, they often overspend and fail to manage their finances effectively.
Users are unable to clearly understand where their money is being spent,
and they lack proper tools to analyze their spending patterns.
There is also no simple system to track savings goals,
which leads to poor financial planning and reduced savings.
Real-life example:
A student receives monthly pocket money.
Without tracking expenses, they may spend money on food, shopping, and travel without realizing total spending.
Using the application, the user can record expenses and view insights
to understand spending habits and improve savings.
5. Proposed Solution
The application provides a simple and efficient system
to track expenses, analyze spending, and monitor savings goals.
Main Features
Add and manage expenses
View total expenses
Category-wise expense analysis
Monthly expense tracking
Budget limit setting
Savings goal tracking
Smart insights (highest spending category)
Data storage using file system
Data visualization using Power BI dashboard
6. Core Entities / Data Structure
Expense
Category
Month
Budget
SavingsGoal
Important Relationships
One user can have multiple expenses.
Expenses are grouped by category.
Expenses are tracked monthly.
Budget is compared with total expense.
Savings goal is calculated based on remaining amount.
7. User Roles & Permissions
User
Add expenses
View expenses
Analyze spending
Set budget
Track savings
(Single user system for simplicity)
8. Success Criteria
User should be able to add and view expenses.
System should calculate total expense correctly.
System should categorize expenses properly.
System should track monthly spending.
System should compare expenses with budget.
User should be able to track savings progress.
Power BI dashboard should display visual insights.
9. Out of Scope
Multi-user login system
Online payment integration
Bank account linking
Mobile application version
AI-based financial prediction
10. Chosen Track
Java (Core Java) + File Handling + Power BI
Future Enhancement
Database integration (MySQL)
Mobile app version
AI-based expense prediction
Smart saving suggestions
