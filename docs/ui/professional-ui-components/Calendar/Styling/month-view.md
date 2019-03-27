---
title: Month view mode
page_title: RadCalendar month view mode styling | Progress NativeScript UI Documentation
description: A month view mode style customization guide page for RadCalendar for NativeScript.
slug: calendar-monthview-styling
tags: radcalendar, cell, styling, month, calendar, cells, nativescript, professional, ui
position: 9
publish: true
---

# Styling the RadCalendar Month View

To apply custom style for the month view, you need to initialize the `monthViewStyle` property of `RadCalendar` with a `CalendarMonthViewStyle` instance.

## View Styling

`CalendarMonthViewStyle` provides the following styling properties:

* `backgroundColor`: Gets or sets the background color.
* `showTitle`: Shows or hides the month view title.
* `showWeekNumbers`: Shows or hides week numbers.
* `showDayNames`: Shows or hides the names of days.
* {% typedoc_link classes:CalendarMonthViewStyle,member:selectionShape %}: Gets or sets the decoration shape drawn in the center of a selected cell within the month view. Accepts values from the {% typedoc_link enums:CalendarSelectionShape %} enumeration.
* {% typedoc_link classes:CalendarMonthViewStyle,member:selectionShapeSize %}: Gets or sets the size of the decoration shape drawn in the center of a selected cell within the month view. If the shape is {% typedoc_link enums:CalendarSelectionShape,member:Square %}, the property determines the side of the square. If the shape is {% typedoc_link enums:CalendarSelectionShape,member:Round %}, the property determines the radius of the circle.
* {% typedoc_link classes:CalendarMonthViewStyle,member:selectionShapeColor %}: Gets or sets the color of the shape.

## Cell Styling

To style any of the available cell types, you need to initialize the corresponding style property of the `CalendarMonthViewStyle` class. The following styling properties are available:

* `dayCellStyle`: Styles the cells that represent a regular day in a month. This is the default style. Initialize this property with a `CalendarDayCellStyle` instance.
* `selectedDayCellStyle`: Styles the selected cell. Initialize this property with a `CalendarDayCellStyle` instance.
* `todayCellStyle`: Styles the cell that shows today's date. Initialize this property with a `CalendarDayCellStyle` instance.
* `dayNameCellStyle`: Styles the cell that shows the name of the day. Initialize this property with a `CalendarCellStyle` instance.
* `weekNumberCellStyle`: Styles the cells that show the week number. Initialize this property with a `CalendarCellStyle` instance.
* `weekendCellStyle` Styles the weekend day cells. Initialize this property with a `CalendarDayCellStyle` instance.
* `titleCellStyle`: Styles the month title. Initialize this property with a `CalendarCellStyle` instance.

### All Cells

`CalendarCellStyle` provides the following styling properties:

* `cellBorderWidth`: Gets or sets the border width of the cell.
* `cellBorderColor`: Gets or sets the border color of the cell.
* `cellBackgroundColor`: Gets or sets the background color of the cell.
* `cellAlignment`: Gets or sets the alignment of the cell's contents.
* `cellTextColor`: Gets or sets the color of the cell's text contents.
* `cellTextFontName`: Gets or sets the font for the cell's text contents by name.
* `cellTextFontStyle`: Gets or sets the font style for the cell's text contents.
* `cellTextSize`: Gets or sets the text size of the cell's text contents.
* `cellPaddingHorizontal`: Gets or sets the amount of horizontal padding of the cell's contents.
* `cellPaddingVertical`: Gets or sets the amount of vertical padding of the cell's contents.  

### Date Cells

`CalendarDayCellStyle` inherits `CalendarCellStyle` and provides the following additional stying properties:

* `showEventsText`: Shows or hides the event text shown in the date cell. All events are indicated by a shape, regardless if the title is shown or not.
* `eventTextColor`: Gets or sets the text color for the events shown in the date cell.
* `eventFontName`: Gets or sets the font for the event text shown in the date cell by name.
* `eventFontStyle`: Gets or sets the font style for the event text in the date cell.
* `eventTextSize`: Gets or sets the font size of the event text in the date cell.

## Example

The following example shows how to style the month view:

<snippet id='calendar-monthview-styling'/>

The following screenshots show the example running on device:

![Calendar month view styling](../../../img/ns_ui/calendar_styling_month_ios.png "iOS")      ![Calendar month view styling](../../../img/ns_ui/calendar_styling_month_android.png "Android")

## References

Want to see more examples using this component?

Check out the [SDK examples repository on GitHub](https://github.com/telerik/nativescript-ui-samples/tree/master/calendar/app/calendar/cell-styling).

You might also like:

* [Styling Inline Events]({% slug calendar-features-styling-inlineevents %})
* [Styling Year View]({% slug calendar-features-styling-year-view %})
* [Styling Week View]({% slug calendar-features-styling-week-view %})
* [Styling Month Name]({% slug calendar-features-styling-monthnames-view %})