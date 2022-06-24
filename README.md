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
--lmdcode-font-serif: Cambria, Times, "Times New Roman", serif;
--lmdcode-font-sans-serif: Segoe, 'Segoe UI', 'Helvetica Neue', 'Arial Nova', Helvetica, Arial, sans-serif; 
--lmdcode-font-monospace: Consolas, monaco, 'Courier New', monospace;
--lmdcode-font-size: 16px;
--lmdcode-font-weight: 400;
--lmdcode-margins: 1rem 0;
--lmdcode-borders: 1px solid #a0a0a0;
--lmdcode-focus-outline: 2px dotted #202020;
--lmdcode-button: #d0d0d0;
--lmdcode-button-hover: #e0e0e0;
--lmdcode-button-active: #b0b0b0;
--lmdcode-text-dark: #000000;
--lmdcode-text-medium: #606060;
--lmdcode-text-light: #ffffff;
--lmdcode-bg-dark: #404040;
--lmdcode-bg-medium: #e3e3e3;
--lmdcode-bg-light: #ffffff;
```

## Demo

In the demo none of the defaults have been changed (some extra inline styles have been added).

<https://lmd-code.github.io/lmdcode-default-css/>
