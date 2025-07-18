# HM Marp Theme

This is a minimalistic [Marp](https://marp.app/) theme in the style of [HM Hochschule München University of Applied Sciences](https://www.hm.edu).

*This theme is not officially endorsed by HM.*

## Usage

### Get CSS

- When using [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode), add the following URL to the "Marp: Themes" extension settings:

```
https://raw.githubusercontent.com/DavidMStraub/hm-marp/refs/heads/main/hm.css
```
- When using Marp CLI, simply download the `hm.css` file and use it with the `--theme` option

Note: you do not have to download any image file, as the HM logo is embedded in the CSS.

### Specify theme in Markdown

Simply add `theme: hm` to the YAML frontmatter of your Markdown file.