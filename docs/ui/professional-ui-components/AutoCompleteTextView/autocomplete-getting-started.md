---
title: Getting Started
page_title: RadAutoCompleteTextView Getting Started | Progress NativeScript UI Documentation
description: A getting started page for RadAutoCompleteTextView for Android. This article explains what are the steps to create a RadAutoCompleteTextView instance from scratch.
slug: autocomplete-gettingstarted
tags: radautocompletetextview, gettingstarted, autocomplete, list, autocompletetextview, nativescript, professional, ui
position: 1
publish: true
---

# Getting Started with RadAutoCompleteTextView

Learn how to initialize `RadAutoCompleteTextView` and use its basic configuration.

## Installation

Run the following command to add the plugin to your application:

```Shell
tns plugin add nativescript-ui-autocomplete
```

## Initialization

To add a {% typedoc_link classes:RadAutoCompleteTextView %} instance in a page of your application, complete the following steps: 

1. Define the following XML namespace:

	```XML
	xmlns:au="nativescript-ui-autocomplete"
	``` 

2. Add the `RadAutoCompleteTextView` tag in your `.xml` file and configure its properties.
	* The `items` property defines the collection of `TokenModel` objects which will be used to provide suggestions to the user input.<br/>The `TokenModel` object is a data model used by the autocomplete to populate the suggestion view and the chosen items.
	* The `hint` property sets a placeholder text displayed when there is no input.
	* The `text` property sets the autocomplete text or gets the current user input.

	<snippet id='autocomplete-getting-started'/>

3. In your model, create the collection of `TokenModel` objects used for populating the list of suggestions.

	<snippet id='autocomplete-generate-data'/>

4. Add a `SuggestionView` tag in your `.xml` file and provide a template for the layout of each suggestion. The suggestion view shows the available suggestions on the screen.
	* The `suggestionViewHeight` property lets you control the height of the suggestion view.
	* The `suggestionItemTemplate` sets the layout for each item of the suggestion view.

	<snippet id='autocomplete-suggestion-view-xml'/>

## References

Want to see more examples using this component?

Check out the [SDK examples repository on GitHub](https://github.com/telerik/nativescript-ui-samples/tree/master/autocomplete/app/examples/).