---
title: Year view mode
page_title: RadCalendar year view mode styling | Progress NativeScript UI Documentation
description: A year view mode style customization guide page for RadCalendar for NativeScript.
slug: calendar-yearview-styling
tags: radcalendar, cell, styling, year, calendar, cells, nativescript, professional, ui
position: 11
publish: true
---

# Styling the RadCalendar Year View

To apply custom styling to the year view, you need to initialize the `yearViewStyle` property of `RadCalendar` with a `CalendarYearViewStyle` instance.

## All Cells

`CellStyle` provides the following styling properties:

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

## Title Cell

To apply custom styling to the title, you need to initialize the `titleCellStyle` property with a `CellStyle` instance.

## Month Cells

To apply custom styling to month cells, you need to initialize the `monthCellStyle` property with a `MonthCellStyle` instance. `MonthCellStyle` provides the following styling properties:

* `weekendTextColor`: Gets or sets the text color for weekend days.
* `todayTextColor`: Gets or sets the text color for today's date.
* `dayTextColor`: Gets or sets the text color for regular days.
* `dayFontName`: Gets or sets the font for days by name.
* `dayFontStyle`: Gets or sets the font style for days.
* `dayTextSize`: Gets or sets the font size for days.
* `dayNameTextColor`: Gets or sets the text color for day names.
* `dayNameFontName`: Gets or sets the font for day names by font name.
* `dayNameFontStyle`: Gets or sets the font style for day names.
* `dayNameTextSize`: Gets or sets the text size for day names.
* `monthNameTextColor`: Gets or sets the text color for the month name.
* `monthNameFontName`: Gets or sets the font name for the month name by font name.
* `monthNameFontStyle`: Gets or sets the font style for the month name.
* `monthNameTextSize`: Gets or sets the text size for the month name.

## Example

The following example shows how to style the year view:

<snippet id='calendar-yearview-styling'/>

The following screenshots show the example running on device:

![Calendar year view styling](../../../img/ns_ui/calendar_styling_year_ios.png "iOS")      ![Calendar year view styling](../../../img/ns_ui/calendar_styling_year_android.png "Android")

## References

Want to see more examples using this component?

Check out the [SDK examples repository on GitHub](https://github.com/telerik/nativescript-ui-samples/tree/master/calendar/app/calendar/cell-styling).

You might also like:

* [Styling Inline Events]({% slug calendar-features-styling-inlineevents %})
* [Styling Month Name]({% slug calendar-features-styling-monthname-view %})
* [Styling Week View]({% slug calendar-features-styling-week-view %})
* [Styling Month View]({% slug calendar-features-styling-month-view %})