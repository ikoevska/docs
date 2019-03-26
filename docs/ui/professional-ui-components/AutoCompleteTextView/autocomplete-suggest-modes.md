---
title: Suggest modes
page_title: RadAutoCompleteTextView Suggest Modes | Progress NativeScript UI Documentation
description: This page is dedicated to the Suggest Modes provided by the RadAutoCompleteTextView control.
slug: autocomplete-suggest-modes
tags: radautocompletetextview, suggestmodes, autocompletetextview, nativescript, professional, ui
position: 4
publish: true
---

# RadAutoCompleteTextView Suggest Modes

`RadAutoCompleteTextView` provides the following suggest modes: 

* {% typedoc_link enums:AutoCompleteSuggestMode,member:Suggest %}
* {% typedoc_link enums:AutoCompleteSuggestMode,member:Append %}
* {% typedoc_link enums:AutoCompleteSuggestMode,member:SuggestAppend %}

You can set the suggest mode with the {% typedoc_link classes:RadAutoCompleteTextView,member:suggestionMode %} property. The default value is {% typedoc_link enums:AutoCompleteSuggestMode,member:Suggest %}.

<snippet id='autocomplete-suggest-mode'/>

## Suggest Mode

In `Suggest` mode, the component shows a list of matching suggestions in a pop-up view.

## Append Mode

In `Append` mode, the component shows the first matching suggestion by appending it to the user input.

## SuggestAppend Mode

In `SuggestAppend` mode, the component shows all matching suggestions in a pop-up view and appends the first of them to the user input.

## References

Want to see more examples using this component?

Check out the [SDK examples repository on GitHub](https://github.com/telerik/nativescript-ui-samples/tree/master/autocomplete/app/examples/).

You might also like:

* [**Display Modes**]({% slug autocomplete-display-modes %})
* [**Completion Modes**]({% slug autocomplete-completion-modes %})