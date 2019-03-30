<img alt="Loop" src="https://loopslider.io/assets/img/loop_logo@0.5x.png" width="200" height="143">

An Infinite Scrolling, Full-Width Slider. Built with jQuery.

** Work in Progress **

## Installation

Grab the CSS & JS files from this repository:
```html
<link rel="stylesheet" href="/path/to/loopslider.min.css">
<script src="/path/to/loopslider.js"></script>
```

## Basic example

Add the HTML snippet. Each image you wish to include is added as another `<li>` element.

```html
<div id="loop-slider" data-autoplay="true" data-speed="8000">
    <ul id="img-group">
        <li class="slide" data-img="/path/to/image.jpg"></li>
        <li class="slide" data-img="/path/to/image.jpg"></li>
        <li class="slide" data-img="/path/to/image.jpg"></li>
    </ul>
</div>
```
[Demo &rarr;](https://loopslider.io/demo.html)

This example has autoplay enabled, with a time of 8 seconds.

## Options

### Autoplay

You can set the autoplay to be `True` or `False`, with `False` being the default.
```html
data-autoplay="true"
```
### Speed

If autoplay is enabled, you can customise the rate at which the images change. The value is in milliseconds, with `8000` (8 seconds) being the default.
```html
data-speed="8000"
```
