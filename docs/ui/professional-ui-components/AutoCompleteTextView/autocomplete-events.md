---
title: Events
page_title: RadAutoCompleteTextView Events | Progress NativeScript UI Documentation
description: This page is dedicated to the events provided by the RadAutoCompleteTextView control.
slug: autocomplete-events
tags: radautocompletetextview, events, autocompletetextview, nativescript, professional, ui
position: 5
publish: true
---

# RadAutoCompleteTextView Events

The `RadAutoCompleteTextView` events notify you when a particular action, in the workflow of the control, has occurred. They are useful when executing logic based on the component state. 

## Available Events

`RadAutoCompleteTextView` provides the following events:

* `tokenAdded`: Triggers whene a token is added.
* `tokenRemoved`: Triggers when a token is removed.
* `tokenSelected`: Triggers when a token is selected.
* `tokenDeselected`: Triggers when a token is deselected.
* `textChanged`: Triggers when the `text` property is changed.
* `didAutoComplete`: Triggers when an item from the suggestions list is selected.
* `suggestionViewBecameVisible`: Triggers when the suggestion view is shown.

All events have identical logical structure and workflow. 

## Usage

To be notified when one of the `RadAutoCompleteTextView` events occur, use the following structure with the respective type of event that you want to capture.

<snippet id='autocomplete-events-xml'/>
<snippet id='autocomplete-events-ts'/>

## References

Want to see more examples using this component?

Check out the [SDK examples repository on GitHub](https://github.com/telerik/nativescript-ui-samples/tree/master/autocomplete/app/examples/).

You might also like:

* [Events Examples](https://github.com/telerik/nativescript-ui-samples/tree/master/autocomplete/app/examples/events)