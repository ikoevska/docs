---
title: Migrating
page_title: Migrating | Progress NativeScript UI Documentation
description: Each component from NativeScript UI now has its own package available for all NativeScript developers on npm.
slug: nativescript-ui-migration
tags: migration, nativescript-pro-ui, nativescript, free, plugin
position: 100
publish: true
---

# NativeScript UI Migration Overview

Some time ago we [announced](https://www.nativescript.org/blog/nativescript-ui-whats-next) that each NativeScript UI component was soon to become as a standalone plugin. Now this change is a fact.

The [nativescript-pro-ui](https://www.npmjs.com/package/nativescript-pro-ui), [nativescript-telerik-ui](https://www.npmjs.com/package/nativescript-telerik-ui), and [nativescript-telerik-ui-pro](https://www.npmjs.com/package/nativescript-telerik-ui-pro) plugins are now deprecated. Read below to learn how to modify your existing applications to use the new standalone plugins.

## Steps

The following steps apply to all of the depecated plugins: `nativescript-pro-ui`, `nativescript-telerik-ui`, and `nativescript-telerik-ui-pro`:

1. Remove the old plugin by using the `plugin remove <plugin-name>` command.<br/>For example, to remove `nativescript-pro-ui`, run the following command:
        ```Shell
        tns plugin remove nativescript-pro-ui
        ```

2. Add the new plugins for each component that your application is using.<br/>For example, if you are using all components, run the following commands:
        ```Shell
        tns plugin add nativescript-ui-chart
        tns plugin add nativescript-ui-calendar
        tns plugin add nativescript-ui-autocomplete
        tns plugin add nativescript-ui-listview
        tns plugin add nativescript-ui-sidedrawer
        tns plugin add nativescript-ui-gauge
        tns plugin add nativescript-ui-dataform
        ```

3. Update your `.ts` and `.js` files to set the correct plugin import. Change the import from `nativescript-pro-ui/<component-name>` to `nativescript-ui-<component-name>`. If you're using Angular, change the import from `nativescript-pro-ui/<component-name>/angular` to `nativescript-ui-<component-name>/angular`.<br/>For example:
    * If you have a chart import `nativescript-pro-ui/chart`, change it to `nativescript-ui-chart`.
    * If you have an Angular chart import `nativescript-pro-ui/chart/angular`, change it to `nativescript-ui-chart/angular`.
     
    > **IMPORTANT:** The `NativeScriptUIGaugesModule` is renamed to `NativeScriptUIGaugeModule`. If you are using the Gauge in Angular, you need to change `import { NativeScriptUIGaugesModule } from "nativescript-pro-ui/gauges/angular";` to `import { NativeScriptUIGaugeModule } from "nativescript-ui-gauge/angular";`

4. Update any `.xml` files that contain imports of the old packages. Change the imports using the pattern from **Step 3**.

5. Rebuild the application.<br/>If you get an error during the build, delete the `node_modules` and `platforms` directories if you get an error during the build.
