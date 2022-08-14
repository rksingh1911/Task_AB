# Task_AB
simple todo application
a simple To Do List application. A typical To Do List application allows a user to keep a list of important tasks that they want to keep track of. In our application, a “To Do” item simply consists of:

Task description
an email address of the person responsible for the task
a priority level, either Low, Medium or High

The application will consist of following controllers:
a) ‘/’ route- responsible for showing the current list of To Do items in a HTML table and showing an HTML form to submit a new To Do list item.
b)  ‘/submit’ route - will accept data from the HTML form, add the To Do list item to a global list of items, and redirect back to the first controller. 
c)  ‘/clear’, which will be responsible for clearing the list of To Do items and redirecting back to the first controller.
