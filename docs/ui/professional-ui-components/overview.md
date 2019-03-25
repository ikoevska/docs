---
title: Overview
description: Overview of the professional user interface elements (widgets) available in NativeScript UI, including AutoComplete, SideDrawer, ListView, Calendar, Chart, DataForm, and Gauges. 
position: 10
tags: ui components, user interface components, nativescript components, nativescript pro ui components
slug: ns-ui-overview
publish: true
---

# NativeScript UI Overview

**Progress NativeScript UI** is a set of free\* components for building rich UI application for iOS and Android with [NativeScript](https://www.nativescript.org). The widget collection is built on top of natively implemented components targeting iOS and Android. 

The components from the **Progress NativeScript UI** set are available for download on [npmjs.com](https://www.npmjs.com/).

> \*The components are free but their code base is proprietary. For more information, see the [license of the components](https://github.com/telerik/nativescript-ui-feedback/blob/master/LICENSE.md). 

> If you want to contribute to the code base, see the available [contributing options](https://github.com/telerik/nativescript-ui-feedback#contributing-to-nativescript-ui).

> If you're looking for a more hands-on experience with the components, jump to the [Take it for a sping](#take-it-for-a-spin) section.

## Components

### RadSideDrawer

[{% nativescript %}[Documentation]({% slug sidedrawer-overview %}){% endnativescript %}{% angular %}[Documentation]({% slug sidedrawer-overview-angular %}){% endangular %}] [{% nativescript %}[Sample Code](https://github.com/telerik/nativescript-ui-samples/tree/master/sidedrawer){% endnativescript %}{% angular %}[Sample Code](https://github.com/telerik/nativescript-ui-samples-angular/tree/master/sidedrawer){% endangular %}][[Download from npm](https://www.npmjs.com/package/nativescript-ui-sidedrawer)]

The **SideDrawer** (`RadSideDrawer` in the code base) lets you follow a popular application pattern to show a hidden view which contains navigation UI or common settings. With **SideDrawer**, you can:

* Embed any content inside the sliding panel: from text and icons to sliders and filters.
* Set the control to slide in from any of the four sides of the screen.
* Apply any from a large set of polished out-of-the-box transition modes.
* Control programmatically the state of the side drawer.
* Cover the navigation or action bar with the side drawer.

![sidedrawer ios](../../img/ui-for-nativescript/sidedrawer-ios.png "sidedrawer ios") ![sidedrawer android](../../img/ui-for-nativescript/sidedrawer-android.png "sidedrawer android")


### RadListView

[{% nativescript %}[Documentation]({% slug listview-overview %}){% endnativescript %}{% angular %}[Documentation]({% slug listview-overview-angular %}){% endangular %}] [{% nativescript %}[Sample Code](https://github.com/telerik/nativescript-ui-samples/tree/master/listview){% endnativescript %}{% angular %}[Sample Code](https://github.com/telerik/nativescript-ui-samples-angular/tree/master/listview){% endangular %}][[Download from npm](https://www.npmjs.com/package/nativescript-ui-listview)]

The **ListView** component (`RadListView` in the code base) lets you implement advanced functionality to a list of items. With **ListView**, you can:

* Pull to refresh.
* Load on demand.
* Swipe to execute.
* Apply header and footer.
* Apply any of four available item animations when the user scrolls.
* Apply any of three available layout modes (`Linear`, `Grid`, or `Staggered`) with a choice of horizontal and vertical scrolling.
* Provide single and multiple selection modes to users.
* Use smart defaults for gestures: selection on long press, special action on swipe, reordering of items on long press and drag, refreshing the list on swipe, and loading more items only when needed.

![listview ios](../../img/ui-for-nativescript/listview-ios.png "listview ios") ![listview android](../../img/ui-for-nativescript/listview-android.png "listview android")

### RadCalendar

[{% nativescript %}[Documentation]({% slug calendar-overview %}){% endnativescript %}{% angular %}[Documentation]({% slug calendar-overview-angular %}){% endangular %}] [{% nativescript %}[Sample Code](https://github.com/telerik/nativescript-ui-samples/tree/master/calendar){% endnativescript %}{% angular %}[Sample Code](https://github.com/telerik/nativescript-ui-samples-angular/tree/master/calendar){% endangular %}][[Download from npm](https://www.npmjs.com/package/nativescript-ui-calendar)]

The **Calendar** (`RadCalendar` in the code base) lets you implement a highly customizable calendar. With **Calendar**, you can:

* Use any of four different view modes: `Week`, `Month`, `MonthNames`, and `Year`.
* Use any of three date selection modes: `Single`, `Multiple`, and `Range`.
* Create inline and popover events;
* Control styling and cell customization options.

![calendar ios](../../img/ui-for-nativescript/calendar-ios.png "calendar ios") ![calendar android](../../img/ui-for-nativescript/calendar-android.png "calendar android")


### RadChart

[{% nativescript %}[Documentation]({% slug chart-overview %}){% endnativescript %}{% angular %}[Documentation]({% slug chart-overview-angular %}){% endangular %}] [{% nativescript %}[Sample Code](https://github.com/telerik/nativescript-ui-samples/tree/master/chart){% endnativescript %}{% angular %}[Sample Code](https://github.com/telerik/nativescript-ui-samples-angular/tree/master/chart){% endangular %}][[Download from npm](https://www.npmjs.com/package/nativescript-ui-chart)]

The **Chart** (`RadChart` in the code base) lets you visualize data in a human-readable way through lines, areas, bars, pies, and more. With **Chart**, you can:

* Visualize a wide range of supported data types: numerical, string, or `DateTime`.
* Implement smooth interaction and zooming.
* Implement various chart series:
	* Show trends with `Line`, `Area`, and `Spline Area` charts.
	* Compare sets of data with `Bar` charts.
	* Illustrate proportions with `Pie` and `Donut` charts and use `Spline` and `Spline Area` charts to plot data that require the use of curve fittings.
	* Show relationships with `Scatter` and `Bubble` series.
	* Use `Financial` series and indicators.
* Add annotations, tooltips, and trackball behavior.
* Implement multiple axis.

![chart ios](../../img/ui-for-nativescript/chart-ios.png "chart ios") ![chart android](../../img/ui-for-nativescript/chart-android.png "chart android")


### RadAutoCompleteTextView

[{% nativescript %}[Documentation]({% slug autocomplete-overview %}){% endnativescript %}{% angular %}[Documentation]({% slug autocomplete-overview-angular %}){% endangular %}] [{% nativescript %}[Sample Code](https://github.com/telerik/nativescript-ui-samples/tree/master/autocomplete){% endnativescript %}{% angular %}[Sample Code](https://github.com/telerik/nativescript-ui-samples-angular/tree/master/autocomplete){% endangular %}][[Download from npm](https://www.npmjs.com/package/nativescript-ui-autocomplete)]

The **AutoCompleteTextView** (`RadAutoCompleteTextView` in the code base) lets you provide suggested options to your users based on the characters they type. With **AutoCompleteTextView**, you can:

* Implement different suggest modes: show suggestions in a drop-down list, one suggestion at a time in the text input, or a combination of both.
* Implement `StartsWith` and `Contains` completion modes.
* Implement a `Plain` display mode (only one item can be selected) or a `Tokens` display mode (multiple selection of suggestions - each displayed as a token).
* Choose between a `Wrap` and a `Horizontal` token layout mode.

![autocompletetextview ios](../../img/ui-for-nativescript/autocompletetextview-ios.png "autocompletetextview ios") ![autocompletetextview android](../../img/ui-for-nativescript/autocompletetextview-android.png "autocompletetextview android")


### RadDataForm

[{% nativescript %}[Documentation]({% slug dataform-overview %}){% endnativescript %}{% angular %}[Documentation]({% slug dataform-overview-angular %}){% endangular %}] [{% nativescript %}[Sample Code](https://github.com/telerik/nativescript-ui-samples/tree/master/dataform){% endnativescript %}{% angular %}[Sample Code](https://github.com/telerik/nativescript-ui-samples-angular/tree/master/dataform){% endangular %}][[Download from npm](https://www.npmjs.com/package/nativescript-ui-dataform)]

The **DataForm** (`RadDataForm` in the code base) lets you build mobile forms based on the public members of a provided data object. With **DataForm**, you can:

* Bind a form to a data object with a single line of code.
* Take advantage of more than **15** built-in editors (or provide your own custom editor).
* Create groups of editors, allow them to be collapsed, and style them.
* Display a form in `ReadOnly` mode.
* Take control over collected data with built-in data validation by a provided validator or a custom one.

![dataform ios](../../img/ui-for-nativescript/dataform-ios.png "dataform ios") ![dataform android](../../img/ui-for-nativescript/dataform-android.png "dataform android")


### RadGauge

[{% nativescript %}[Documentation]({% slug gauges-overview %}){% endnativescript %}{% angular %}[Documentation]({% slug gauges-overview-angular %}){% endangular %}] [{% nativescript %}[Sample Code](https://github.com/telerik/nativescript-ui-samples/tree/master/gauge){% endnativescript %}{% angular %}[Sample Code](https://github.com/telerik/nativescript-ui-samples-angular/tree/master/gauge){% endangular %}][[Download from npm](https://www.npmjs.com/package/nativescript-ui-gauge)]

The **Gauge** (`RadRadialGauge` in the code base) lets you display the current status of a value within a range of upper and lower bounds, visualize progress towards a goal, or show a summary of a fluctuating metric. With **Gauge**, you can:

* Add one or more `RadialScale` instances to your gauge.
* Use `Bar` indicators to visualize a range of values.
* Use a `Needle` indicator to point to a specific value.
* Apply ready-to-use animations for smooth transition effects.

![gauges ios](../../img/ui-for-nativescript/gauges-ios.png "gauges ios") ![gauges android](../../img/ui-for-nativescript/gauges-android.png "gauges android")

## Take It For A Spin

### The Components In Action

To see how the components look like on device, get the official NativeScript and Progress NativeScript UI app from the [App Store](https://itunes.apple.com/us/app/examples-nativescript/id1046772499?ls=1&mt=8) or [Google Play](https://play.google.com/store/apps/details?id=org.nativescript.examples).

If you're interested in the code at the core of the working app, check it out in [GitHub](https://github.com/NativeScript/nativescript-marketplace-demo).

### Code To Start With

Some getting started code with extensive usage examples for each component is available in the {% nativescript %}[NativeScript UI sample app on GitHub](https://github.com/telerik/nativescript-ui-samples){% endnativescript %}{% angular %}[NativeScript UI sample app on GitHub](https://github.com/telerik/nativescript-ui-samples-angular){% endangular %}. 

For more information about how to run the application, see the respective README file.

## Feedback

Your feedback will be highly appreciated and will directly influence the development of **Progress NativeScript UI**.

You can submit issues and feedback to the [dedicated feedback GitHub repository](https://github.com/telerik/nativescript-ui-feedback).