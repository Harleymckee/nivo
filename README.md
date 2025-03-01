<a href="https://nivo.rocks"><img alt="nivo" src="https://raw.githubusercontent.com/plouc/nivo/master/nivo.png" width="216" height="68"/></a>

[![Backers on Open Collective](https://opencollective.com/nivo/backers/badge.svg?style=flat-square)](#backers)
[![Sponsors on Open Collective](https://opencollective.com/nivo/sponsors/badge.svg?style=flat-square)](#sponsors)
[![License][license-image]][license-url]
[![GitHub Actions][actions-image]][actions-url]
[![NPM version][npm-image]][npm-url]
[![nivo channel on discord](https://img.shields.io/badge/discord-nivo-61dafb.svg?style=flat-square)](https://discord.gg/n7Ft74f)

**nivo** provides supercharged React components to easily build dataviz apps,
it's built on top of d3.

Several libraries already exist for React d3 integration,
but just a few provide server side rendering ability and fully declarative charts.

## Installation

In order to use nivo, you have to install the `@nivo/core` package and then choose
some of the scoped `@nivo` packages according to the charts you wish to use:

```
yarn add @nivo/core @nivo/bar
```

## Features

-   Highly customizable
-   Motion/transitions, powered by [react-motion](https://github.com/chenglou/react-motion)
-   [Component playground](http://nivo.rocks)
-   [Exhaustive documentation](http://nivo.rocks)
-   Isomorphic rendering
-   [SVG charts](http://nivo.rocks/components?filter=svg)
-   [HTML charts](http://nivo.rocks/components?filter=html)
-   [Canvas charts](http://nivo.rocks/components?filter=canvas)
-   [server side rendering API](https://github.com/plouc/nivo-api)
-   [SVG patterns](http://nivo.rocks/guides/patterns)
-   [Gradients](http://nivo.rocks/guides/gradients)
-   [responsive charts](http://nivo.rocks/components?q=responsive)

## Discussion

Join the [nivo discord community](https://discord.gg/n7Ft74f).

## Packages & components

**nivo** is comprised of several packages/components, for a full list,
please use the [components explorer](http://nivo.rocks/components).

## [HTTP API](https://github.com/plouc/nivo-api)

Components available through the HTTP rendering API.

-   [Bar](https://nivo-api.herokuapp.com/samples/bar.svg)
-   [CirclePacking](https://nivo-api.herokuapp.com/samples/circle-packing.svg)
-   [Chord](https://nivo-api.herokuapp.com/samples/chord.svg)
-   [HeatMap](https://nivo-api.herokuapp.com/samples/heatmap.svg)
-   [Line](https://nivo-api.herokuapp.com/samples/line.svg)
-   [Pie](https://nivo-api.herokuapp.com/samples/pie.svg)
-   [Radar](https://nivo-api.herokuapp.com/samples/radar.svg)
-   [Sankey](https://nivo-api.herokuapp.com/samples/sankey.svg)
-   [Sunburst](https://nivo-api.herokuapp.com/samples/sunburst.svg)
-   [TreeMap](https://nivo-api.herokuapp.com/samples/treemap.svg)

## Guides

-   [colors](http://nivo.rocks/guides/colors)
-   [legends](http://nivo.rocks/guides/legends)
-   [gradients](http://nivo.rocks/guides/gradients)
-   [patterns](http://nivo.rocks/guides/patterns)

## Backers

Donations are welcome to help improving **nivo** [[Become a backer](https://opencollective.com/nivo#backer)]

<a href="https://opencollective.com/nivo#backers" target="_blank"><img src="https://opencollective.com/nivo/backers.svg?width=890"></a>

## Open Collective Sponsors

Support this project by becoming a sponsor,
your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/nivo#sponsor)]

## Credits

-   [d3](https://d3js.org/)
-   [react](https://facebook.github.io/react/)
-   …

[license-image]: https://img.shields.io/github/license/plouc/nivo.svg?style=flat-square
[license-url]: https://github.com/plouc/nivo/blob/master/LICENSE.md
[npm-image]: https://img.shields.io/npm/v/@nivo/core.svg?style=flat-square
[npm-url]: https://www.npmjs.com/~nivo
[actions-image]: https://img.shields.io/github/workflow/status/plouc/nivo/CI.svg?style=flat-square
[actions-url]: https://github.com/plouc/nivo/actions
[prettier-image]: https://img.shields.io/badge/styled_with-prettier-ff69b4.svg?style=flat-square
[prettier-url]: https://github.com/prettier/prettier
