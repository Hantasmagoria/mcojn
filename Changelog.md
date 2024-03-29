# Changelog
All notable changes to this project will be documented in this file.

## [Version 3.0.7 - 27/8/2019 (current)]
###Fixed
-alert error when picking date.
>>upon picking a date that was in a week that included days of the next month, an alert pops up preventing the selection of date.

## Version 3.0.6 - 6/8/2019
###Minor feature implementations:
>>Toggle between calendar and bookings display using the Bookings button.

## Version 3.0.5 - 5/8/2019
###Fixed
-system not accepting proper date values.
>>upon picking a date that was in a week that is supposed to be valid, an alert pops up saying otherwise.

## Version 3.0.4 - 1/8/2019
###Fixed
-alert error when picking date.
>>upon picking a date that was in a week that included days of the next month, an alert pops up preventing the selection of date.

## Version 3.0.3
###Fixed
-Retention of entire calendar when changing 'Facilitiy Name' dropdown.
>>upon switching facilities using the filters on the left-side container, and then clicking on "Bookings", calendar was changed to the calendar values that were from the previous facility booking calendar.
>>This issue existed whether or not the calendar was displayed as a calendar or data.

-Issue of adding too many buttons when running the script multiple times.
>>running the script more than one time will add another set of buttons each time the script is run.

## Version 3.0.2
###Minor feature implementations:
>>Toggle between calendar and bookings display using the Bookings button.

## Version 3.0.1
###Added
>>Initialize today's current date as the date upon running the script.

## Version 3
###Changed 
-Style and design of the displayed data.
###Added
>>Error sequence when trying to display bookings when there is no date specified.
>>Error sequence when trying to input a date not within the currently displayed week.
>>Error sequence when there is no bookings for the date specified.

## Version 2.1.14
###Fixed
-Retention of output after switching 'Facility Name' dropdown.
>>upon switching facilities using the filters on the left-side container, and then clicking on "Bookings", the results showed a significant number of data results containing mostly 'undefined'. 
>>upon further repetition of the above, the quantity of the 'undefined' results increased.

## Version 2
###Added
-Buttons.
>Offloaded the functionality of the script into two buttons that appear on the page upon loading the script onto the website.
###Fixed
-Issue where script needed to be copied and pasted multiple times for one job.

## Version 1
>Let there be light.

[Version 3.0.7 - 27/8/2019 (current)]: src/source.js
