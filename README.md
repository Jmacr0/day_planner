# Day Planner

The purposes of this application is to create a calendar that allows the user to save events for each hour of the day.

This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.

The app will display standard business hours (9 a.m. to 5 p.m.). Each time slot represents one hour and contains the following:

* The time

* A field to hold user input

* A save button

Clicking on the save button will store the time and user input in `localStorage`.

Near the top of the calendar, the application displays the current day. 

Additionally, each hour is color coded to reflect whether the time slot is in the past, the present, or the future. 

This will change depending on the time of day.

## Live Version:

https://jmacr0.github.io/day_planner/

## User Story

AS AN employee with a busy schedule

I WANT to add important events to a daily planner

SO THAT I can manage my time effectively 

## Business Context

Poor time management can result in missed meetings and deadlines or create the appearance of unprofessionalism. A daily planner allows employees to see their day at a glance, schedule time effectively, and improve productivity. 

## Features

* The application displays timeblocks for standard business hours (9 a.m. to 5 p.m.).

* Each timeblock contains an input field and save button.

* Clicking a timeblock's "Save" button stores the input text in local storage, allowing the text to persist when the application is refreshed.

* The current day is displayed at the top of the calendar.

* Each timeblock is color coded to indicate whether it is in a past, present, or future hour.

```
GIVEN that an employee adds events to a specific hour in a calendar

WHEN the employee clicks the save button

THEN events are saved in the timeblock for that hour
```
- - -


