# ChartJS Horizontal Line Plugin

I found this code at http://stackoverflow.com/questions/38324238/draw-horizontal-lines-in-chart-js-2-0 and it helped me immensely, so I packaged it as an NPM module for others to easily add to their project.

## Installation

1. Install with npm: `npm install --save chartjs-horizontal-line-plugin`. 
2. Include the dist/chartjs-horizontal-line-plugin.js file (after ChartJS).

## Usage

Add one (or both!) of the following array to your chart's `options` property:

```
    "horizontalLine": [{
        "y": 260,
        "style": "rgba(255, 0, 0, .4)",
        "text": "max"
    },{
        "y": 220,
        "style": "rgba(0, 255, 0, .4)",
        "text": "min"
    }],
    "verticalLine": [{
        "x": 260,
        "style": "rgba(255, 0, 0, .4)",
        "text": "max"
    },{
        "x": 220,
        "style": "rgba(0, 255, 0, .4)",
        "text": "min"
    }]
```

That's it!