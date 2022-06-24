# Default CSS

A mildly opinionated default stylesheet created for my own projects. This is not a CSS reset/normalise (although some normalisation is applied, particularly for forms) or framework - it's just my preferred starting point rather than an end result.

## Usage

1. Download the unminified CSS file to your project's CSS assets.
2. Customise the CSS variables to suit ([see customisable variables](#customisable-variables)).
3. Then either:
    - Link as separate stylesheet (minification recommended).\
    `<link href="lmdcode-default.css" rel="stylesheet">`
    - Or, paste to the top of your own stylesheet.

## Customisable Variables

The defaults are my own preferences.

```css
--defaultcss-font-serif: Cambria, Times, "Times New Roman", serif;
--defaultcss-font-sans-serif: Segoe, 'Segoe UI', 'Helvetica Neue', 'Arial Nova', Helvetica, Arial, sans-serif; 
--defaultcss-font-monospace: Consolas, monaco, 'Courier New', monospace;
--defaultcss-font-size: 16px;
--defaultcss-font-weight: 400;
--defaultcss-margins: 1rem 0;
--defaultcss-borders: 1px solid #a0a0a0;
--defaultcss-focus-outline: 2px dotted #202020;
--defaultcss-button: #d0d0d0;
--defaultcss-button-hover: #e0e0e0;
--defaultcss-button-active: #b0b0b0;
--defaultcss-text-dark: #000000;
--defaultcss-text-medium: #606060;
--defaultcss-text-light: #ffffff;
--defaultcss-bg-dark: #404040;
--defaultcss-bg-medium: #e3e3e3;
--defaultcss-bg-light: #ffffff;
```

## Demo

In the demo none of the defaults have been changed (some extra inline styles have been added).

<https://lmd-code.github.io/lmdcode-default-css/>
