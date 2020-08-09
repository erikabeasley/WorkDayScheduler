# WorkDayScheduler

I created a daily planner application that allows a user to save events for each hour block of the work day from 9 to 5. (Except yes, I plan my morning routine as well as a vedge hour when I get home so, I created blocks from 8am to 7pm.

Moment.js was used to create a function displaying the current time and date. This was then used to allow a loop comparing whether the current time was past the time blocks on the calendar so that the user will see grey blocks for past times, red for the current time block, and green for future time blocks.

When the user opens the application the current date and time is displayed at the top of the page. The user can add important events to each hour block on the schedule. I added a save button to the end of each hour block row to store the events in local storage. If the user re-freshes the page the events will be saved and still be displayed to the user.

# Deployed Application

https://erikabeasley.github.io/WorkDayScheduler/

![WorkDay Scheduler](assets/capture.PNG)


