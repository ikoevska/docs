---
title: Event Handling
page_title: RadCalendar Event handling | Progress NativeScript UI Documentation
description: An event handling page for RadCalendar for NativeScript.
slug: calendar-event-handling
tags: radcalendar, event, handling, calendar, callbacks, nativescript, professional, ui
position: 4
publish: true
---

# RadCalendar Event Handling

{% typedoc_link classes:RadCalendar %} exposes events that notify you about changes in the state of the component resulting from user interactions. By handling these events, you can perform actions on date selection, when changing the view, and so on. 

{% typedoc_link classes:RadCalendar %} exposes the following events:

* {% typedoc_link classes:RadCalendar,member:dateSelectedEvent %}: Fires when a date is selected programmatically or by the end user.
* {% typedoc_link classes:RadCalendar,member:dateDeselectedEvent %}: Fires when a date is deselected programmatically or by the end user.
* {% typedoc_link classes:RadCalendar,member:inlineEventSelectedEvent %}: Fires when an inline event is selected.
* {% typedoc_link classes:RadCalendar,member:navigatedToDateEvent %}: Fires when the user navigates to a date.
* {% typedoc_link classes:RadCalendar,member:navigatingToDateStartedEvent %}: Fires when navigation to a date begins.
* {% typedoc_link classes:RadCalendar,member:viewModeChangedEvent %}: Fires when the view changes to another [view mode]({% slug calendar-view-modes %}).
* {% typedoc_link classes:RadCalendar,member:dayViewEventSelectedEvent %}: Fires when an event, part of the list of events in the day view area of the calendar, is selected.


## Providing Handlers

You can handle {% typedoc_link classes:RadCalendar %} events in the familiar {N} way. 

The following example shows how to subscribe for all available events in your `XML`:

<snippet id='calendar-handling-events-xml'/>

The following example shows how to define the event handlers in the code-behind file associated with the `XML` page:

<snippet id='calendar-handling-events'/>

## Event Arguments

All {% typedoc_link classes:RadCalendar %} events provide additional information to their handlers. The handlers require this information for proper event handling.

The following event arguments are available:

* {% typedoc_link classes:RadCalendar,member:dateSelectedEvent %} and {% typedoc_link classes:RadCalendar,member:dateDeselectedEvent %} deliver their data as a {% typedoc_link classes:CalendarSelectionEventData %} class instance. This class provides the following properties:
	* `eventName`: The name of the event.
	* `date`: The selected date.
	* `object`: The object that fires the event.
* {% typedoc_link classes:RadCalendar,member:inlineEventSelectedEvent %} delivers its data as a {% typedoc_link classes:CalendarInlineEventSelectedData %} class instance. This class provides the following properties:
	* `eventName` : The name of the event.
	* `object`: The object that fires the event.
	* `eventData`: A {% typedoc_link classes:CalendarEvent %} class instance representing the selected event.
* {% typedoc_link classes:RadCalendar,member:navigatedToDateEvent %} delivers its data as a `CalendarNavigationEventData` {% typedoc_link classes:CalendarNavigationEventData %} class instance. This class provides the following properties:
	* `eventName`: The name of the event.
	* `object`: The object that fires the event.
	* `date`: The date the navigation leads to.
* {% typedoc_link classes:RadCalendar,member:dayViewEventSelectedEvent %} delivers its data by as a {% typedoc_link classes:CalendarDayViewEventSelectedData %} class instance. This class provides the following properties:
	* `eventName`: The name of the event.
	* `object`: The object that fires the event.
	* `eventData`: A {% typedoc_link classes:CalendarEvent %} class instance representing the selected event.
	
## References

Want to see more examples using this component?

Check out the [SDK examples repository on GitHub](https://github.com/telerik/nativescript-ui-samples/tree/master/calendar/app/calendar/events).