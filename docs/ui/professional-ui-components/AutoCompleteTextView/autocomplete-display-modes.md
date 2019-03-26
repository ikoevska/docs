---
title: Display modes
page_title: RadAutoCompleteTextView Display Modes | Progress NativeScript UI Documentation
description: This page is dedicated to the Display Modes provided by the RadAutoCompleteTextView control.
slug: autocomplete-display-modes
tags: radautocompletetextview, displaymodes, autocompletetextview , nativescript, professional, ui
position: 3
publish: true
---

# RadAutoCompleteTextView Display Modes

`RadAutoCompleteTextView` provides the following display modes:

* {% typedoc_link enums:AutoCompleteDisplayMode,member:Plain %}
* {% typedoc_link enums:AutoCompleteDisplayMode,member:Tokens %}

You can set the display mode with the {% typedoc_link classes:RadAutoCompleteTextView,member:displayMode %} property of `RadAutoCompleteTextView`. The default value is {% typedoc_link enums:AutoCompleteDisplayMode,member:Plain %}.

<snippet id='autocomplete-display-mode'/>

## Plain Mode

In `Plain` mode, users can select only suggested item. `RadAutoCompleteTextView` shows the selected item as plain text.

## Tokens Mode

In `Tokens` mode, users can select multiple suggested items at once. `RadAutoCompleteTextView` shows the selected items as tokens which can be modified or replaced with custom ones.

In this mode, you can use one of the following token arrangements:

* {% typedoc_link enums:AutoCompleteLayoutMode,member:Horizontal %}
* {% typedoc_link enums:AutoCompleteLayoutMode,member:Wrap %}

You can set the layout mode of the tokens with the {% typedoc_link enums:RadAutoCompleteTextView,member:layoutMode %} property. The default value is {% typedoc_link enums:AutoCompleteLayoutMode,member:Wrap %}.

<snippet id='autocomplete-layout-mode'/>

### Wrap Layout

With the `Wrap` layout, tokens are arranged on multiple lines. When a new line is started, `RadAutoCompleteTextView` expands to show all tokens.

### Horizontal Layout

With the `Horizontal` layout, tokens are arranged on a single line which can be scrolled horizontally to display all tokens.

## References

Want to see more examples using this component?

Check out the [SDK examples repository on GitHub](https://github.com/telerik/nativescript-ui-samples/tree/master/autocomplete/app/examples/).

You might also like:

* [**Completion Modes**]({% slug autocomplete-completion-modes %})
* [**Suggest Modes**]({% slug autocomplete-suggest-modes %})
