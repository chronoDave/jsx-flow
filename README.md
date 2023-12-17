<div align="center">
  <span style="font-size: 3rem" aria-hidden="true">🌊</span>

  <h1>jsx-flow</h1>
  <p><b>jsx-flow</b> is a simple <a href="https://en.wikipedia.org/wiki/JSX_(JavaScript)">JSX</a> templating language.</p>
</div>

<div align="center">
  <a href="/LICENSE">
    <img alt="License GPLv3" src="https://img.shields.io/badge/license-GPLv3-blue.svg" />
  </a>
  <a href="https://www.npmjs.com/package/jsx-flow">
    <img alt="NPM" src="https://img.shields.io/npm/v/jsx-flow?label=npm">
  </a>
  <a href="https://bundlephobia.com/result?p=jsx-flow@latest">
    <img alt="Bundle size" src="https://img.shields.io/bundlephobia/minzip/leaf-db@latest.svg">
  </a>
</div>

## Getting Started

### Installation

```sh
npm i jsx-flow
```

### Example

Using **jsx-flow** should feel familiar for those used to writing JSX:

```TSX
const Template = props => (
  <html lang="en">
    <body>{props.children}</body>
  </html>
);

const Page = () => (
  <Template>
    <h1>Title</h1>
  </Template>
)
```
