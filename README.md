# 05 Third-Party APIs: Work Day Scheduler

## Description and Task 

My task is to create a simple calendar application that allows a user to save events for each hour of the day. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.

[Moment.js](https://momentjs.com/) library is used to work with date and time. 

## User Story

```md
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```
## Acceptance Criteria Simplified

The following are completed tasks for this project:

* Shows the current day at the top of the calendar (day and date, see gif for format)
* A series of timeblock elements exists on the page. 
* Each timeblock has an hour associated with it. Taken the current time into account and compare it to the hour of the timeblock. Each timeblock has a specific color depending on if it has already happened, is happening now, or will happen in the future.
* It has a textbox inside each timeblock, to allow entering events.
* There is a button to the right of each timeblock. When this button is clicked, save the corresponding event to localstorage for that time slot.
* When loading the page, all the stored data were fetched for each timeslot from localstorage and put those values in the corresponding textboxes for the given timeblocks.

## Mock Up

The following animation demonstrates the application functionality:

![planner-sc](https://user-images.githubusercontent.com/112984208/224219773-95402c8f-051c-4c1a-8157-9bf9fe88365e.png)

##  Follow the link to view the deployed application (https://miniigrace.github.io/05-Work-Day-Scheduler/) 
