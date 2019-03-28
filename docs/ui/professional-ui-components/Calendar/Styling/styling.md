---
title: Overview
page_title: RadCalendar styling overview | Progress NativeScript UI Documentation
description: A cell style customization guide page for RadCalendar for NativeScript.
slug: calendar-styling-overview
tags: radcalendar, cell, styling, calendar, cells, nativescript, professional, ui
position: 8
publish: true
---

# RadCalendar Styling

`RadCalendar` provides four view modes which you can customize to meet your application's visual requirements. You can customize the visual representation of the view and all visual items it consists of.

You can define and combine styles for any of the view modes for a single calendar instance. In this case, when you navigate from one view to another, different styles are applied for the view and its items.

Use the following calendar properties to style the various view modes:

* `monthViewStyle`: Styles the [month view]({% slug calendar-monthview-styling %} "Read more about styling in Month view mode"). Initialize this property with a `CalendarMonthViewStyle` instance.
* `weekViewStyle`: Styles the [week view]({% slug calendar-weekview-styling %} "Read more about styling in Week view mode"). Initialize this property with a `CalendarWeekViewStyle` instance.
* `yearViewStyle`: Styles the [year view]({% slug calendar-yearview-styling %} "Read more about styling in Year view mode"). Initialize this property with a `CalendarYearViewStyle` instance.
* `monthNamesViewStyle`: Styles the [month names view]({% slug calendar-monthnamesview-styling %} "Read more about styling in MonthNames view mode"). Initialize this property with a `CalendarMonthNamesViewStyle` instance.
* `dayViewStyle`: Styles the [day view]({% slug calendar-dayview-styling %} "Read more about styling in Day view mode"). Initialize this property with a `CalendarDayViewStyle` instance.

Every class provides additional properties for styling the various visual parts within the respective view.

## Example

The following example shows the use of some of the available styling options:

<snippet id='calenar-monthview-styling'/>

The following screenshots show the example running on device:

![Calendar month view styling](../../../img/ns_ui/calendar_styling_month_ios.png "iOS")      ![Calendar month view styling](../../../img/ns_ui/calendar_styling_month_android.png "Android")

## References

Want to see more examples using this component?

Check out the [SDK examples repository on GitHub](https://github.com/telerik/nativescript-ui-samples/tree/master/calendar/app/calendar/cell-styling).