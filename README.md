# axe-reporter-html

[![Build](https://github.com/Widen/axe-reporter-html/actions/workflows/build.yml/badge.svg)](https://github.com/Widen/axe-reporter-html/actions/workflows/build.yml)
[![npm version](https://img.shields.io/npm/v/axe-reporter-html)](https://www.npmjs.com/package/axe-reporter-html)
[![changesets](https://img.shields.io/badge/maintained%20with-changesets-blue)](https://github.com/atlassian/changesets)

Creates an HTML report from Axe results listing violations, passes, incomplete
and incompatible results.

## Installation

### npm

```bash
npm install axe-reporter-html
```

### Yarn

```bash
yarn add axe-reporter-html
```

## Usage

This package exports a single function that you can use to create an HTML report
from an `AxeResults` object.

```javascript
import createHTMLReport from 'axe-reporter-html'

const html = await createHTMLReport(results)
```
