---
title: MonthNames view mode
page_title: RadCalendar year view mode styling | Progress NativeScript UI Documentation
description: A MonthNames view mode style customization guide page for RadCalendar for NativeScript.
slug: calendar-monthnamesview-styling
tags: radcalendar, cell, styling, monthnames, month, calendar, cells, nativescript, professional, ui
position: 12
publish: true
---

# Styling the RadCalendar MonthNames View

Тo apply custom styling to the month names view, you need to initialize the `monthNamesViewStyle` property of `RadCalendar` with a `CalendarMonthNamesViewStyle` instance.

In this view, you can customize two cell types: the title bar cell and the month name cell.

To apply custom styling to the title, you need to initialize the `titleCellStyle` property with a `CellStyle` instance.

To apply custom styling to the month name, you need to initialize the `monthNameCellStyle` property with a `CellStyle` class.

You can use any of the available `CellStyle` properties.

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

## Example

The following example shows how to style the month view:

<snippet id='calendar-monthnamesview-styling'/>

The following screenshots show the example running on device:

![Calendar year view styling](../../../img/ns_ui/calendar_styling_month_names_ios.png "iOS")      ![Calendar year view styling](../../../img/ns_ui/calendar_styling_month_names_android.png "Android")

## References

Want to see more examples using this component?

Check out the [SDK examples repository on GitHub](https://github.com/telerik/nativescript-ui-samples/tree/master/calendar/app/calendar/cell-styling).

You might also like:

* [Styling Inline Events]({% slug calendar-features-styling-inlineevents %})
* [Styling Year View]({% slug calendar-features-styling-year-view %})
* [Styling Week View]({% slug calendar-features-styling-week-view %})
* [Styling Month View]({% slug calendar-features-styling-month-view %})