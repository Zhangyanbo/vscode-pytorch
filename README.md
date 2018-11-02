# PyTorch Code Snippets for VSCode

[![VSMarketplace](https://vsmarketplacebadge.apphb.com/version-short/SBSnippets.pytorch-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=SBSnippets.pytorch-snippets)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/SBSnippets.pytorch-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=SBSnippets.pytorch-snippets)
[![Rating](https://vsmarketplacebadge.apphb.com/rating-short/SBSnippets.pytorch-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=SBSnippets.pytorch-snippets)
[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg)](LICENSE.md)
[![GitHub](https://img.shields.io/badge/github-v0.1.0-blue.svg)](https://github.com/SvenBecker/vscode-pytorch/releases)

This project aims to provide a faster workflow when using the [PyTorch](https://github.com/pytorch/pytorch) or [fastai](https://github.com/fastai/fastai) library in [Visual Studio Code](https://code.visualstudio.com/).
This extension provides code snippets for often used coding blocks as well as code example provided by the libraries for common deep learning tasks.

## Table of Content

* [Getting Started](#usage)
* [Installation](#installation)
* [Changelog](#changelog)
* [Contributing](#contributing)
* [Future Plans](#plans)
* [Contact](#contact)
* [Credits](#credits)

## <a name="usage" > </a> Getting Started

If this extension is installed and activated you might notice by start typing `pytorch` or `fastai` in your python file a dropdown
list appears. Entries starting with `pytorch:` or `fastai:` represent code snippets refering to those libraries offered by this extension.
Snippets appear in the same way as code completion by using `Ctrl+Space`. I defined variables inside the code snippets so you can jump from one
variable to another by pressing `Tab`. Examples on how to use this extension are shown below.

### PyTorch Preview

![PyTorch Preview](images/preview.gif)

### Fastai Preview (not ready yet)

![Fastai Preview](images/preview.gif)

## <a name="installation" > </a> Installation

The installation process is very straightforward. The most recommend way is shown below.

1. Launch Visual Studio Code
2. From the command palette `Ctrl-Shift-P` (Windows, Linux) or `Cmd-Shift-P` (MacOS)
3. Select Install Extension
4. Type `PyTorch Snippets`
5. Choose extension
6. Restart Visual Studio Code

This will give you the most recent version you can find on the [VS Marketplace](https://marketplace.visualstudio.com/vscode).
Alternativly you can also clone this repository and move it manually into your VSCode extension folder which will give you
the most recent version on GitHub.

```sh
git clone https://github.com/SvenBecker/vscode-pytorch.git
mv vscode-pytorch /path/to/your/VSCodeExtensionFolder/
```

On Windows for example you can normally find the extension folder at `C:\Users\YourName\.vscode\extensions`. On MacOs and Linux it should be
located at `~/.vscode/extensions`.

> The second method will give you the overall most recent version because I won't update the VS Marketplace version as often
> as the GitHub version but the VS Marketplace version will be the more stable one.

## <a name="changelog" > </a> Changelog

There are not any changes yet but in case of any major changes I will post the most recent ones here.
All of the past as well as the upcoming changes can further be viewed at [Changelog](CHANGELOG.md).

## <a name="contributing" > </a> Contributing

If you want to contribute, what I would highly appreciate since this project is currently in a very early stage
and there is still so much to do, please take a look at [Contributing](CONTRIBUTING.md).

## <a name="plans" > </a> Future Plans

I would like to extend snippet options to additional packages which are related to PyTorch.
This might include [Ignite](https://github.com/pytorch/ignite) or [Pyro](https://github.com/uber/pyro).

Furthermore, but not in this project, I would like to offer VS Code snippets for visualization in Python, like for
example Matplotlib or Seaborn. If anyone is interested in this kind of project and/or want to offer some help please
[contact](#contact) me.

## <a name="contact" > </a> Contact

Suggestions for improvements will be highly appreciated.
You can write me an email (address is provided on my [profile](https://github.com/SvenBecker)) or you can
contact me on Twitter [@SBX9209](https://twitter.com/SBX9209).

## <a name="credits" > </a> Credits

* [PyTorch](https://pytorch.org/): A huge thanks to the PyTorch team for building such an awesome, easy to use deep learning framework and for offering a numerous amount of code examples.
* [Fastai](https://www.fast.ai/): Also a huge thanks to Jeremy Howard and the whole fast.ai team for creating this great deep learning library and also for offering wonderful, very practical orientated free lectures giving insight to deep learning to a wide range of people including ml/dl beginners as well as advanced practitioners.
* [VSCode](https://code.visualstudio.com/): My personal favorite text editor and I'm grateful for all the options they are offering, like a huge amount of language support, extensions, integrated terminal, debugger etc..