---
title: Inline events
page_title: RadCalendar inline events styling | Progress NativeScript UI Documentation
description: Inline events customization guide page for RadCalendar for NativeScript.
slug: calendar-inlineevents-styling
tags: radcalendar, cell, styling, inline, events, calendar, cells, nativescript, professional, ui
position: 13
publish: true
---

# Styling RadCalendar Inline Events

Inline events are time-boxed calendar events within a selected day in Month or Week view. To style inline events, you need to initialize the `inlineEventCellStyle` member of `CalendarMonthViewStyle` or `CalendarWeekViewStyle` with an instance of the `InlineEventCellStyle` class.

`InlineEventCellStyle` provides the following properties:

* `cellBackgroundColor`: Gets or sets the background color of the inline event's cell.
* `eventTextColor`: Gets or sets the text color for the inline event.
* `eventFontName`: Gets or sets the font for the inline event by font name.
* `eventFontStyle`: Gets or sets the font style for the inline event.
* `eventTextSize`: Gets or sets the text size for the inline event.
* `timeTextColor`: Gets or sets the color for the time of the inline event.
* `timeFontName`: Gets or sets the font for the time of the inline event by font name.
* `timeFontStyle`: Gets or sets the font style fo the time of the inline event.
* `timeTextSize`: Gets or sets the text size for the time of the inline event.

To set a color for the inline event's cell indicator (the shape that indicates the event in the corresponding day cell), use the `eventColor` property of the `CalendarEvent` class. When `CalendarEventsViewMode.Inline` is set, you can apply additional styling options to the cells of the table view shown for inline events.

## Example

The following example shows the use of `InlineEventCellStyle`:

<snippet id='calendar-inlineevents-styling'/>

The following screenshots show the example running on device:

![Calendar year view styling](../../../img/ns_ui/calendar_styling_inline_events_ios.png "iOS")      ![Calendar year view styling](../../../img/ns_ui/calendar_styling_inline_events_android.png "Android")

## References

Want to see more examples using this component?

Check out the [SDK examples repository on GitHub](https://github.com/telerik/nativescript-ui-samples/tree/master/calendar/app/calendar/cell-styling).

You might also like:

* [Styling Month Name]({% slug calendar-features-styling-monthnames-view %})
* [Styling Year View]({% slug calendar-features-styling-year-view %})
* [Styling Week View]({% slug calendar-features-styling-week-view %})
* [Styling Month View]({% slug calendar-features-styling-month-view %})