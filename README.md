# GitHub flavored Markdown light theme for vscode (DEPRECATED)

**In the July 2017 update of VSCode, the VSCode team released a style contribution point for markdown preview. Now there's a [VS Code Github Style extension](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles) from them, use it instead :D**

A light theme overwrite whether you're using VSCode dark/light theme.

Using BigstickCarpet's gist, which is based on [GitHub Markdown Repo][markdown-css]

## Usage

Add the following lines to your `settings.json`.

```js
{
  ... // other settings
  "markdown.styles": [
    "https://cdn.rawgit.com/BigstickCarpet/5d31c053d0b1d52389eb2723f7550907/raw/88e4538c0fc46e39a97f332b43546f92762a6bb6/github-markdown.css",
    "https://cdn.rawgit.com/Yukaii/vscode-markdown-github-css/master/github.css"
  ]
}
```

or download these two stylesheets and reference them locally:

1. [BigstickCarpe's github css](https://gist.github.com/BigstickCarpet/5d31c053d0b1d52389eb2723f7550907)
2. [`github.css`](https://cdn.rawgit.com/Yukaii/vscode-markdown-github-css/master/github.css)

Modify `settings.json` as follows:

```js
{
  ... // other settings
  "markdown.styles": [ 
    "file:///PATH/TO/BigstickCarpe's github.css",
    "file:///PATH/TO/github.css"
  ]
}
```

## Preview

> Markdown sample from [facebook/react][react]

![md1](http://i.imgur.com/hHbhwHJ.png)
![md2](http://i.imgur.com/1cHzwmM.png)

## Credits

* [BigstickCarpe's gists](https://gist.github.com/BigstickCarpet/5d31c053d0b1d52389eb2723f7550907)
* CSS in [original VSC repo](https://github.com/Microsoft/vscode/blob/master/src/vs/workbench/parts/extensions/electron-browser/media/markdown.css)

[markdown-css]: https://github.com/sindresorhus/github-markdown-css
[react]: https://github.com/facebook/react/blob/master/README.md
