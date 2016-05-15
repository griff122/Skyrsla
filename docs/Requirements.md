#Requirements

---

###Description:
---
Below are a list of requirements for the application.

---

### Main requirements

* Needs a secure login interface.
* Front page should be a summary of most worked tasks (or most recent [update query accordingly]).
* Should be able to review past week logs.
⋅⋅* View logs for a specified date range, project, etc.
⋅⋅⋅⋅* Need the ability to query most if not all pieces of the logs.
* Should be able to create a log for a specified date
⋅⋅* A log should be able to be broken up by projects and tasks.
⋅⋅⋅⋅* When entering a log, should need to specify a project, and then can add as many tasks as needed to the project group.
⋅⋅⋅⋅* Input:
⋅⋅⋅⋅⋅⋅1. Project
⋅⋅⋅⋅⋅⋅2. Task
⋅⋅⋅⋅⋅⋅3. Estimated time for task
⋅⋅⋅⋅⋅⋅4. Actual time taken for a task
⋅⋅⋅⋅⋅⋅5. Notes
⋅⋅* Should be able to edit past logs
⋅⋅* When creating a log, first need to specify the date (or select a previous date).
⋅⋅⋅⋅* The reviewing portion might play a crucial part here.
* Need to be able to generate reports for a given week (or range or weeks).
⋅⋅* Should automatically fill in with the current week.
⋅⋅* Should be able to also specify what projects/weeks to generate for (or what to exclude, if necessary).
⋅⋅* Once a report is generated, show it to the user. Then they can enter emails to send the report to.
⋅⋅* Should also have the ability to switch from HTML and plain text versions of the report.
⋅⋅⋅⋅* Try to include graphics in the HTML version of the report (a simple bar chart with day/week breakdowns of time spend on each project (or tasks if project count is insufficent).

---

#Extra goals
* Setup a way for a user to customize their interface.
⋅⋅* This can include simple things such as changing colors, to being able to customize the landing page.
