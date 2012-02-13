# jQuery Checkbox Switch

This is a replacement for a standard checkbox control, offering a more aesthetically pleasing on/off style switch-button.

The plugin was inspired by http://devgrow.com/iphone-style-switches/. Any suggestions for improvement are welcome!

## Demo

For some live examples, visit http://www.devigninnovation.com/jquery-checkbox-switch/index.html

## Plugin options

All of these are optional.

* border-color: CSS color for border of control, e.g. "#111"
* border-radius: Corner radius of control, e.g. "2px"
* padding: Padding around text, e.g. "8px"
* on-text: Text to display as the ON part of the button, e.g. "Yes"
* off-text: Text to display as the OFF part of the button, e.g. "No"
* off-gradient-start: start color for gradient in unselected state
* off-gradient-end: end color for gradient in unselected state
* on-gradient-off-start: start color for gradiant in selected state for OFF side
* on-gradient-off-end: end color for gradient in selected state for OFF side
* on-gradient-on-start: start color for gradient in selected state for ON side
* on-gradient-on-end: end color for gradient in selected state for ON side

## Installation

1. Download and add jquery-checkbox-switch.js to the head of your HTML file.

```html
<script src="/path/to/jquery-checkbox-switch.js"></script>
```

2. Initialize control for any checkbox, as required.

```javascript
$("#id_checkbox").CheckboxSwitch();
```
