---
title: Getting started
page_title: Getting started | Progress NativeScript UI Documentation
description: Getting started with Progress NativeScript UI
slug: ns-ui-getting-started
tags: getting, started, ui, nativescript
position: 20
publish: true
---

# NativeScript UI Getting Started

Before you start, make sure that you meet the following prerequisites:

* You have installed the latest version of NativeScript.
* You have [created a NativeScript application]({% slug introduction %}).

## Installing the Components

1. Open a console window and navigate to the root directory of your NativeScript application.
2. Use the `plugin add <component-name>` command to install the respective package.<br/>For example, if you want to use the chart, run the following command: 

	```Shell
	$ tns plugin add nativescript-ui-chart
	```

3. Import the installed component in your app.

	```TypeScript
	import * as chartModule from "nativescript-ui-chart";
	```
	```JavaScript
	var chartModule = require("nativescript-ui-chart");
	```
{% angular %}

## Usage in Angular

You can find the plugin's Angular directives in the `angular` folder in the plugin's main folder. To be able to use the NativeScript UI components, you can choose one of the following approaches:

* (Recommended) Import the NgModule of the UI component you want to use and add it to the bootstrapped module of your application. This enables [ahead-of-time compilation (AoT)](https://angular.io/guide/aot-compiler) and [lazy loading](https://angular.io/guide/ngmodule#lazy-loading-modules-with-the-router).
* Bootstrap your application using the global NativeScript UI directives.
* Import the needed directives in your Angular components and use them where needed.

### Enabling Ahead-of-Time Compilation and Lazy Loading

To make your project compatible with AoT, add the plugin's built-in modules to your bootstrapped Angular `NgModule` or to each lazy loaded one. You can find the module for each UI component in its respective `nativescript-ui-<component-name>/angular` folder. Import the ones that you want to use in your project and add them to the `imports`. For more information about how to bundle your application, see [Using Webpack to Bundle Your Code]({% slug bundling-with-webpack %}).

To use [lazy loading](https://angular.io/guide/ngmodule#lazy-loading-modules-with-the-router), add the component's NgModule to your `imports`. For more information about lazy loading with NativeScript and Angular, see [What is Lazy Loading (and why you should use it)?]({% slug lazy-loading %})

If your project does not use lazy loading, add the modules to the imports of your `AppModule`.
{% endangular %}