
# gongtimer

A quarto extension for `reveal.js` that adds an elapsed time bar at the
bottom of the presentation.

This is based on the `ElapsedTimeBar` Reveal.js extension

https://github.com/tkrkt/reveal.js-elapsed-time-bar

## Installation

To install this extension in your current directory (or into the Quarto
project that you’re currently working in), use the following command:

``` shell
quarto install extension andrie/quarto-gongtimer
```

## Enabling

Add the plugin to your quarto `yaml` header

``` yaml
revealjs-plugins: 
  - gongtimer
```

## Changing options

To change default options, use:

``` yaml
format: 
  revealjs:
    gongtimer:
      - allottedTime: 1 # time in minutes
revealjs-plugins: 
  - gongtimer
```

You can change these options:

| Option              | Description                                                 |
|---------------------|-------------------------------------------------------------|
| `allottedTime`      | Time in minutes for the presentation (default is 5 minutes) |
| `progressBarHeight` | Height (in pixels) of the page / time progress bar          |
| `barColor`          | Bar color, expressed as hex `#00ff00` or `rgb(0, 255, 0)`   |

## More information about Quarto extensions

Refer to https://quarto.org/docs/extensions/

## License

This work is licensed under an MIT license, (c) 2024 Andrie de Vries
