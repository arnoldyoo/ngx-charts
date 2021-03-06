# ngx-charts (f.k.a. ng2d3)
[![Join the chat at https://gitter.im/swimlane/ngx-charts](https://badges.gitter.im/swimlane/ngx-charts.svg)](https://gitter.im/swimlane/ngx-charts?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) 
[![Build Status](https://travis-ci.org/swimlane/ngx-charts.svg?branch=master)](https://travis-ci.org/swimlane/ngx-charts) 
[![Code Climate](https://codeclimate.com/github/swimlane/ngx-charts/badges/gpa.svg)](https://codeclimate.com/github/swimlane/ngx-charts)
[![Test Coverage](https://codeclimate.com/github/swimlane/ngx-charts/badges/coverage.svg)](https://codeclimate.com/github/swimlane/ngx-charts/coverage)

Declarative Charting Framework for Angular2 and beyond!

**Note: ngx-charts 5.0.0 works only with Angular 4.x. 
To use ngx-charts with Angular 2.x, use ngx-charts 4.x.**

ngx-charts is unique because we don't merely wrap d3, nor any other chart engine for that matter. It is using Angular to render and animate the SVG elements with all of its binding and speed goodness, and uses d3 for the excellent math functions, scales, axis and shape generators, etc. By having Angular do all of the rendering it opens us up to endless possibilities the Angular platform provides such as AoT, Universal, etc. 

Data visualization is a science but that doesn't mean it has to be ugly. One of the big efforts we've made while creating this project is to make the charts aesthetically pleasing. The styles are also completely customizable through CSS, so you can override them as you please.

Also, constructing custom charts is possible by leveraging the various ngx-charts components that are exposed through the ngx-charts module.

For more info, check out the [documentation](https://swimlane.gitbooks.io/ngx-charts/content/) and the [demos](https://swimlane.github.io/ngx-charts/).

## Features
### Chart Types
- Horizontal & Vertical Bar Charts (Standard, Grouped, Stacked, Normalized)
- Line 
- Area (Standard, Stacked, Normalized)
- Pie (Explodable, Grid, Custom legends)
- Bubble
- Donut
- Gauge (Linear & Radial)
- Force Directed Graph
- Heatmap
- Treemap
- Number Cards

### Customization
- Autoscaling
- Timeline Filtering
- Line Interpolation
- Configurable Axis Labels
- Legends (Labels & Gradient)
- Advanced Label Positioning
- Real-time data support
- Advanced Tooltips
- Data point Event Handlers
- Works with ngUpgrade

## Install
To use ngx-charts in your project install it via [npm](https://www.npmjs.com/package/@swimlane/ngx-charts):

```
npm i @swimlane/ngx-charts --save
```

## Credits
`ngx-charts` is a [Swimlane](http://swimlane.com) open-source project; we believe in giving back to the open-source community by sharing some of the projects we build for our application. Swimlane is an automated cyber security operations and incident response platform that enables cyber security teams to leverage threat intelligence, speed up incident response and automate security operations.
