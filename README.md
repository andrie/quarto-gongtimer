
# gong

A quarto extension for `reveal.js` that adds an elapsed time bar at the
bottom of the presentation.

This is based on the `ElapsedTimeBar` Reveal.js extension

https://github.com/wicksome/reveal.js-elapsed-time-bar

## Installation

To install this extension in your current directory (or into the Quarto
project that you’re currently working in), use the following command:

``` shell
quarto install extension andrie/quarto-gongtimer
```

## Enabling

Add this to your document or project options:

``` yaml
format: 
  revealjs:
    gongtimer:
      - allottedTime: 1
revealjs-plugins: 
  - gongtimer
```

## Global options

You can change these options:

| Option              | Description                                               |
|---------------------|-----------------------------------------------------------|
| `allottedTime`      | Time in minutes for the presentation                      |
| `progressBarHeight` | Height (in pixels) of the page / time progress bar        |
| `barColor`          | Bar color, expressed as hex `#00ff00` or `rgb(0, 255, 0)` |