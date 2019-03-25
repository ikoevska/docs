---
title: Overview
page_title: RadAutoCompleteTextView Overview | Progress NativeScript UI Documentation
description: This article is a short description and summary of RadAutoCompleteTextView's features.
slug: autocomplete-overview
tags: autocomplete, overview, autocompletetextview, nativescript, professional, ui, radautocompletetextview
position: 0
publish: true
---

# RadAutoCompleteTextView Overview

`RadAutoCompleteTextView` (also, **AutoCompleteTextView**) automatically completes user input strings by comparing the text being entered to all strings in the associated data source. The component provides easy customization and data management.

## Features

### Suggest Modes

`RadAutoCompleteTextView` provides the following suggest modes:

* `Suggest`: Shows suggestions in a drop-down list below the input field.
* `Append`: Shows only one suggestion as an appended text to the input. 
* `SuggestAppend`: Applies `Suggest` and `Append` simultaneously.

### Display Modes

`RadAutoCompleteTextView` provides the following display modes:

* `Plain`: Users can select only one suggestion. The selected item appears on the screen as plain text in the input field.
* `Tokens`: Users can select multiple suggestions. The selected items appear on the screen as tokens.

### Tokens Layout Modes

When the `Tokens` display mode is active, `RadAutoCompleteTextView` provides the following layouts for the tokens:

* `Wrap`: Tokens are aligned in a grid. 
* `Horizontal`: Tokens are aligned horizontally.

### Completion Modes

`RadAutoCompleteTextView` provides the following completion modes:

* `StartsWith`: Shows only suggestions which start with the typed text.
* `Contains`: Shows suggestions which contain the typed text.

## Screenshots

#### Figure 1. RadAutoCompleteTextView (iOS/Android)
![RadAutoCompleteTextView: Overview](../../img/ns_ui/autocomplete-overview-ios.png "RadAutoCompleteTextView in iOS") ![RadAutoCompleteTextView: Overview](../../img/ns_ui/autocomplete-overview-android.png "RadAutoCompleteTextView in Android") 