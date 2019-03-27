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
* `allDayText`: Sets the text indicating that the top area shows All Day events.
* `allDayTextIsVisible`: Shows or hides the text indicating that the top area shows All Day events.

## Example

The following example shows the use of the of `dayEventsViewStyle` and `allDayEventsViewStyle`:

<snippet id='calendar-dayview-styling'/>

The following screenshots show the example running on device:

![Calendar day view styling](../../../img/ns_ui/calendar_styling_day_ios.png "iOS")      ![Calendar day view styling](../../../img/ns_ui/calendar_styling_day_android.png "Android")

## References

Want to see more examples using this component?

Check out the [SDK examples repository on GitHub](https://github.com/telerik/nativescript-ui-samples/tree/master/calendar/app/calendar/cell-styling).

You might also like:

* [Styling Inline Events]({% slug calendar-features-styling-inlineevents %})
* [Styling Month Name]({% slug calendar-features-styling-monthname-view %})
* [Styling Week View]({% slug calendar-features-styling-week-view %})
* [Styling Month View]({% slug calendar-features-styling-month-view %})
* [Styling Year View]({% slug calendar-features-styling-year-view %})