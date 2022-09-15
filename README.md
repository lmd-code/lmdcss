# LMD CSS

A *mildly opinionated* default CSS file created for my own projects. This is not a CSS reset/normalise (although some normalisation is applied, particularly for forms) or framework - it's just my preferred starting point rather than an end result.

## Usage

1. Download the unminified CSS file to your project's CSS assets.
2. Customise the CSS variables to suit ([see customisable variables](#customisable-variables)).
3. Then either:
    - Link as separate stylesheet (minification recommended).\
    `<link href="lmdcss.css" rel="stylesheet">`
    - Or, paste to the top of your own stylesheet.

## Customisable Variables

The defaults are my own preferences.

```css
--lmdcss-font-serif: Cambria, Times, "Times New Roman", serif;
--lmdcss-font-sans-serif: Segoe, 'Segoe UI', 'Helvetica Neue', 'Arial Nova', Helvetica, Arial, sans-serif; 
--lmdcss-font-monospace: Consolas, monaco, 'Courier New', monospace;
--lmdcss-font-size: 16px;
--lmdcss-font-weight: 400;
--lmdcss-margins: 1rem 0;
--lmdcss-borders: 1px solid #a0a0a0;
--lmdcss-focus-outline: 2px dotted #202020;
--lmdcss-button: #d0d0d0;
--lmdcss-button-hover: #e0e0e0;
--lmdcss-button-active: #b0b0b0;
--lmdcss-text-dark: #000000;
--lmdcss-text-medium: #606060;
--lmdcss-text-light: #ffffff;
--lmdcss-bg-dark: #404040;
--lmdcss-bg-medium: #e3e3e3;
--lmdcss-bg-light: #ffffff;
```

## Demo

In the demo none of the defaults have been changed (some extra inline styles have been added).

<https://lmd-code.github.io/lmdcss/>
