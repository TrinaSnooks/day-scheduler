# Challenge 5 - day-scheduler

<https://trinasnooks.github.io/day-scheduler/>

## Description

The purpose of the project is to create a daily scheduler. Where past time blocks are greyed out, current time block is pink and future time blocks are green.

## User Story

```md
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

## Acceptance Criteria

```md
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
```

The following animation demonstrates the application functionality:

<!-- @TODO: create ticket to review/update image) -->
![A user clicks on slots on the color-coded calendar and edits the events.](./Assets/05-third-party-apis-homework-demo.gif)

## Usage

Screenshots:


    ![screenshot 1]((assets/images/screenshot-1.png)
    ![screenshot 2]((assets/images/screenshot-2.png)
    ![screenshot 3]((assets/images/screenshot-3.png)
    ![screenshot 4]((assets/images/screenshot-4.png)
    ![screenshot 5]((assets/images/screenshot-5.png)
    ![screenshot 6]((assets/images/screenshot-6.png)

## Credits

## Features
- record and keep daily schedule with the use of local storage
- use day.js to indicate date
