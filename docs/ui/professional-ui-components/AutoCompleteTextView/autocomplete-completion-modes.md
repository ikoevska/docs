---
title: Completion modes
page_title: RadAutoCompleteTextView Completion Modes | Telerik UI NativeScript
description: This page is dedicated to the Completion Modes provided by the RadAutoCompleteTextView control.
slug: autocomplete-completion-modes
tags: radautocompletetextview, completionmodes, autocompletetextview, nativescript, professional, ui
position: 2
publish: true
---

# RadAutoCompleteTextView Completion Modes

`RadAutoCompleteTextView` provides the following modes for the filtering of suggestions: 

- {% typedoc_link enums:AutoCompleteCompletionMode,member:StartsWith %}
- {% typedoc_link enums:AutoCompleteCompletionMode,member:Contains %}

You can change the completion mode with the {% typedoc_link classes:RadAutoCompleteTextView,member:completionMode %} property of `RadAutoCompleteTextView`. The default value is {% typedoc_link enums:AutoCompleteCompletionMode,member:StartsWith %}.

<snippet id='autocomplete-completion-mode'/>

## StartsWith Mode

In `StartsWith` mode, the component shows only suggestions that begin with the typed phrase.

## Contains Mode

In `Contains` mode, the component shows all suggestions that contain the typed phrase, anywhere within the suggested text.

> **IMPORTANT:** Do not use the `Contains` completion mode with the `Append` and `SuggestAppend` suggest modes. 
 Both suggest modes append the rest of the suggestion to the typed text. Combining them with the `Contains` completion mode might confuse the user. 

## References

Want to see more examples using this component?

Check out [SDK examples repository on GitHub](https://github.com/telerik/nativescript-ui-samples/tree/master/autocomplete/app/examples/).

You might also find useful:

* [**Display Modes**]({% slug autocomplete-display-modes %})
* [**Suggest Modes**]({% slug autocomplete-suggest-modes %})