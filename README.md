# React Google Charts

<img align="right" alt="Logo" src="website/static/img/logo.png">

A thin, typed, React wrapper for [Google Charts](https://developers.google.com/chart/interactive/docs/reference).

[![version](https://img.shields.io/npm/v/react-google-charts.svg)](https://www.npmjs.com/package/react-google-charts)
[![downloads](https://img.shields.io/npm/dm/react-google-charts.svg)](https://www.npmjs.com/package/react-google-charts)
[![license](https://shields.io/badge/license-MIT-green)](http://opensource.org/licenses/MIT)
[![bundle size](https://img.shields.io/bundlephobia/minzip/react-google-charts.svg)](https://bundlephobia.com/result?p=react-google-charts)

<br />
<a href="#quickstart">Quickstart</a>
<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
<a href="#docs">Docs</a>
<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
<a href="#contributing">Contributing</a>
<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
<a href="https://stackoverflow.com/questions/tagged/react-google-charts">Stack Overflow</a>
<br />
<hr />

## Quickstart

Install this library with your favorite package manager:

```bash
yarn add react-google-charts
```

or

```bash
npm install --save react-google-charts
```

Then, import and use it:

```jsx
import { Chart } from "react-google-charts";

<Chart
  chartType="ScatterChart"
  data={[["Age", "Weight"], [4, 5.5], [8, 12]]}
  width="100%"
  height="400px"
  legendToggle
/>
```

# Docs

- [Quick Walkthrough](https://react-google-charts-docs.netlify.app/docs/quick-walkthrough)
- [Components](https://react-google-charts-docs.netlify.app/components)
- [Examples](https://react-google-charts-docs.netlify.app/examples)

## Contributing

Contributions are very welcome. Check out [CONTRIBUTING.md](CONTRIBUTING.md)

## Run the Storybook

```bash
git clone https://www.github.com/rakannimer/react-google-charts
cd react-google-charts
yarn
yarn start:storybook
```
