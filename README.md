# LMD CSS

A *mildly opinionated* default CSS file created for my own projects. This is not a CSS reset/normalise (although some normalisation is applied, particularly for forms) or framework - it's just my preferred starting point rather than an end result.

## Usage

1. Download the latest release and unpack it to your project's CSS assets.
2. Then either:
    - Link to the minified version:\
    `<link href="lmdcss.min.css" rel="stylesheet">`
    - Or, using the unminified version, customise the CSS variables to suit ([see customisable variables](#customisable-variables)) before:
        - Minifying it and using as above.
        - Using the unminified version directly.
        - Pasting it to the top of your own stylesheet.

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
--lmdcss-mark-bg: #ffff44;
--lmdcss-mark-text: #000000;
```

## Demo

In the demo none of the defaults have been changed (styles have been added for layout/presentation).

<https://lmd-code.github.io/lmdcss/docs/>
