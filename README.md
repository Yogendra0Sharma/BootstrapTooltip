# Bootstrap Tooltip

This widget adds a tooltip to a user defined field, containing for example help text or extra information.

## Contributing

For more information on contributing to this repository visit [Contributing to a GitHub repository](https://world.mendix.com/display/howto50/Contributing+to+a+GitHub+repository)

## Typical usage scenario

Add helptext to an inputfield on focus.
Informative text for buttons on hover.

## Installation

Import the widget to your project and add the Bootstrap Tooltip on a page.

## Configuration

Configure the properties to determine how the widget will behave in your application.

Tip: Locate the widget as close to the target element as possible. (Preferably next to it)

## Features and limitations

-   Based on Bootstrap's Tooltip.js

## Properties

-   _Target element classname_ The class name of the field to attach the tooltip to.
-   _Default text_ Text being displayed when no data source microflow is defined.
-   _Tooltip position_ The location of the tooltip relative to the field. Values: top, left, bottom, right
-   _Tooltip mode_ When to show the tooltip. Values: On hover, On click
-   _Tooltip source microflow_ Return value: Text to display in tooltip.
