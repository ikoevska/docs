---
title: Day view mode
page_title: RadCalendar day view mode styling | Progress NativeScript UI Documentation
description: A day view mode style customization guide page for RadCalendar for NativeScript.
slug: calendar-dayview-styling
tags: radcalendar, cell, styling, day, calendar, cells, nativescript, professional, ui
position: 13
publish: true
---

# RadCalendar Day View Styling

To apply custom style for the day view mode, you need to initialize the `dayViewStyle` property of `RadCalendar` with a `CalendarDayViewStyle` instance.

To apply custom style to the cells displayed at the top, you can use the same properties available for [styling of the month view]({% slug calendar-monthview-styling %} "Read more about styling in Month view mode"). You can also use the following `CalendarDayViewStyle` properties specific to the day view: `dayEventsViewStyle` and `allDayEventsViewStyle` .

## dayEventsViewStyle

Use `dayEventsViewStyle` with a `DayEventsViewStyle` instance. The instance provides the following styling options:

* `backgroundColor`: Sets the background color for the events view.
* `timeLabelFormat`: Sets the display format for time labels in the timeline.
* `timeLabelTextColor`: Sets the color of the time labels in the timeline.
* `timeLabelTextSize`: Sets the font size of the time labels in the timeline.

## allDayEventsViewStyle

Use `allDayEventsViewStyle` with an `AllDayEventsViewStyle` instance. The instance provides the following styling options:

* `backgroundColor`: Sets the background color for the area where All Day events are shown.
* `allDayText`: Sets the text that indicates that the top area contains All Day events.
* `allDayTextIsVisible`: Shows or hides the text that indicates that the top area contains All Day events.

## Example
Here's an example of using the properties mentioned above:

<snippet id='calendar-dayview-styling'/>

This is how the calendar looks like in that case:

![Calendar day view styling](../../../img/ns_ui/calendar_styling_day_ios.png "iOS")      ![Calendar day view styling](../../../img/ns_ui/calendar_styling_day_android.png "Android")

## References
Want to see this scenario in action?
Check our SDK examples repo on GitHub. You will find this and many other practical examples with NativeScript UI.

* [Styling Example](https://github.com/telerik/nativescript-ui-samples/tree/master/calendar/app/calendar/cell-styling)

Related articles you might find useful:

* [**Styling Inline Events**]({% slug calendar-features-styling-inlineevents %})
* [**Styling Month Name**]({% slug calendar-features-styling-monthname-view %})
* [**Styling Week View**]({% slug calendar-features-styling-week-view %})
* [**Styling Month View**]({% slug calendar-features-styling-month-view %})
* [**Styling Year View**]({% slug calendar-features-styling-year-view %})
