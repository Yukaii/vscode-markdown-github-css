# GitHub flavored Markdown light theme for vscode

A light theme overwrite whether you're using VSCode dark/light theme.

Using BigstickCarpet's gist, which is based on [GitHub Markdown Repo][markdown-css]

## Usage

Add the following lines to your `settings.json`.

```js
{
  ... // other settings
  "markdown.styles": [
    "https://cdn.rawgit.com/Yukaii/vscode-markdown-github-css/master/github.css",
    "https://cdn.rawgit.com/BigstickCarpet/5d31c053d0b1d52389eb2723f7550907/raw/88e4538c0fc46e39a97f332b43546f92762a6bb6/github-markdown.css"
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
