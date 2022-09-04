# MOD CSS

A *Mildly Opinionated Default Cascading Stylesheet* created for my own projects. This is not a CSS reset/normalise (although some normalisation is applied, particularly for forms) or framework - it's just my preferred starting point rather than an end result.

## Usage

1. Download the unminified CSS file to your project's CSS assets.
2. Customise the CSS variables to suit ([see customisable variables](#customisable-variables)).
3. Then either:
    - Link as separate stylesheet (minification recommended).\
    `<link href="modcss.css" rel="stylesheet">`
    - Or, paste to the top of your own stylesheet.

## Customisable Variables

The defaults are my own preferences.

```css
--modcss-font-serif: Cambria, Times, "Times New Roman", serif;
--modcss-font-sans-serif: Segoe, 'Segoe UI', 'Helvetica Neue', 'Arial Nova', Helvetica, Arial, sans-serif; 
--modcss-font-monospace: Consolas, monaco, 'Courier New', monospace;
--modcss-font-size: 16px;
--modcss-font-weight: 400;
--modcss-margins: 1rem 0;
--modcss-borders: 1px solid #a0a0a0;
--modcss-focus-outline: 2px dotted #202020;
--modcss-button: #d0d0d0;
--modcss-button-hover: #e0e0e0;
--modcss-button-active: #b0b0b0;
--modcss-text-dark: #000000;
--modcss-text-medium: #606060;
--modcss-text-light: #ffffff;
--modcss-bg-dark: #404040;
--modcss-bg-medium: #e3e3e3;
--modcss-bg-light: #ffffff;
```

## Demo

In the demo none of the defaults have been changed (some extra inline styles have been added).

<https://lmd-code.github.io/modcss/>
