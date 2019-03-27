---
title: Async data fetch
page_title: RadAutoCompleteTextView Display Modes | Progress NativeScript UI Documentation
description: This page is dedicated to the async data fetch API provided by the RadAutoCompleteTextView control.
slug: autocomplete-async-data
tags: radautocompletetextview, asyncdata, AutoCompleteTextView, nativescript, professional, ui
position: 6
publish: true
---

# Using Async Data Fetch with RadAutoCompleteTextView

`RadAutoCompleteTextView` provides an API for asynchronous loading of data. You might find this useful when you need to load your data from a remote provider, such as a web service. 

> All examples use a `JSON` list of airports.

## Implementation

To populate the autocomplete list asynchronously, use a promise which handles the data fetch and returns a collection of `TokenModel` objects.

Assign the promise to the `loadSuggestionsAsync` property of the `RadAutoCompleteTextView` object. The component executes this promise every time a symbol is typed and then generates suggestions based on the collection returned by the promise.

Create a page that contains the `RadAutoCompleteTextView` component and configure the component. Bind `RadAutoCompleteTextView` to the source collection (`dataItems` in the example).

Configure a `suggestionItemTemplate` that represents each suggestion.

<snippet id='autocomplete-async-xml'/>

Retrieve the `RadAutoCompleteTextView` object initialized in the `.xml` file. Set its `loadSuggestionsAsync` property to a function which accepts one parameter (the typed text). In this function, define a promise, load the remote data in it, and then return the promise.

Later, the autocomplete will invoke the `loadSuggestionsAsync` function and when the promise is resolved,
it will use the returned items to complete its population. 

<snippet id='autocomplete-async-model'/>

## References

Want to see more examples using this component?

Check out the [SDK examples repository on GitHub](https://github.com/telerik/nativescript-ui-samples/tree/master/autocomplete/app/examples/).

You might also like:

* [Remote Data Fetch Example](https://github.com/telerik/nativescript-ui-samples/tree/master/autocomplete/app/examples/remote-data-fetch)