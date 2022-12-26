# Latex Template for University

LaTeX Template made by myself for my course summaries, my practical work reports or my project files reports (including electrical implementation diagrams, C or  Natural language or over programming language like ST (industry automation) etc...)

> The general shape of the rendering is done with the **KOMA-SCRIPT class scrartcl** (European version of standart class "Article" especially to adapt the layout to A4 format and over benefits)

# Table of Contents

- [Latex Template for University](#latex-template-for-university)
- [Table of Contents](#table-of-contents)
- [Preview](#preview)
- [Want to reproduce ?](#want-to-reproduce-)
- [Installation guide of LaTeX for begginers](#installation-guide-of-latex-for-begginers)
  - [TeXLive](#texlive)
  - [Development environment](#development-environment)
- [Installation guide of the Template](#installation-guide-of-the-template)
- [How to configure VSCode to code in LaTeX](#how-to-configure-vscode-to-code-in-latex)
  - [1. download VSCode](#1-download-vscode)
  - [2. Install extensions](#2-install-extensions)
- [Packages included in the Template](#packages-included-in-the-template)
- [Custom environements](#custom-environements)
- [Credits](#credits)
- [License](#license)

# Preview

| Custom Title Page | Simple Page Presentation |
| :---------------: | :----------------------: |
| :---------------: | :----------------------: |
| [![A custom title page](docs/previewFirstPage.png)](examples/simple-example/simpleExample.pdf) | [![A basic example page](docs/previewBlock.png)](examples/simple-example/simpleExample.pdf) |


# Want to reproduce ?

**You are totally free to clone this repository to adapt at your own purpose !**

*Differents "How-To" will follow in the next sections depending on whether you are a new or experienced LaTeX user.*

# Installation guide of LaTeX for begginers

## TeXLive

- For Linux Users :
> You can install TeXLive by running ```sudo apt install texlive-full``` under Linux environement *(Be carreful, the total installation is about 5GB, you can make a partial installation and download packages needed later)*

- For others Systems :
> You can install it directly on the official website "http://www.tug.org/texlive/acquire-netinstall.html" by following the procedure.

## Development environment

:warning: **I recommend that you first find out about the different IDEs BEFORE choosing**

You can use differents IDE for Latex :

- You can use [TeXStudio](https://www.texstudio.org/). TeXstudio is an integrated writing environment made for creating LaTeX documents.
> TeXStudio is a ready-to-use editor for LaTeX that makes it easy to get started.

- You can use [Vim](https://www.vim.org/). Vim is a highly configurable text editor.
> Vim is difficult to use for begginner and not recommended for the uninitiated 
> 
> **but you can read [this guide](https://medium.com/rahasak/vim-as-my-latex-editor-f0c5d60c66fa)**

- You can use [Visual Studio Code](https://code.visualstudio.com/). Visual Studio Code is an extensible code editor developed by Microsoft.
> **This is the solution I am developing in the ["How-to configure VSCode for LaTeX"](#how-to-configure-vscode-to-code-in-latex)**

- And finally : Feel free to choose you own workflow, you can find many guides to take notes and other with LaTeX on the internet.
# Installation guide of the Template

![Git Clone](docs/carbonInstallation.png)

Then you can build the template directly without errors!

But you still have to personalise the data :

1. Add a ```./assets/logo.png``` for you own logo and repositionning correctly it at the line ```17``` by changing the values of ```hshift=``` and ```vshift=```
> ![backgroundsetup ligne 17](docs/logoCarbon.png)

2. Changing ```\firstName```, ```\lastName```, ```\university``` commands values and adapt ```\groupNumber``` to your own situation
> ![Personal informations ligne 4](docs/personalDataCarbon.png)

3. Make the rest of the features your own with the ["Custom Template environments"](#custom-template-environements) and ["Packages included in the Template"](#packages-included-in-the-template) sections !

# How to configure VSCode to code in LaTeX

For my setup I use VS Code and Vim to write my documents in LaTeX.

But I also use differents extensions to facilitate some actions like graph drawing with [Draw.io](https://app.diagrams.net/)
## 1. download VSCode

> Download VSCode [here.](https://code.visualstudio.com/)

## 2. Install extensions

You need to install these extensions:

1. [Latex Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
2. [LaTeX utilities](https://marketplace.visualstudio.com/items?itemName=tecosaur.latex-utilities)

You can install these extensions as well:

1. [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments): greatly simplifies the reading of comments
2. [Draw.io](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio): allows you to edit image files ```.drawio.png```
3. [Deepl for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=soerenuhrbach.vscode-deepl): to easily translate bits of text
4. [Edit csv](https://marketplace.visualstudio.com/items?itemName=janisdd.vscode-edit-csv): to easy manipulate CSV files
5. [Vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim): Vim extension for VSCode, Vim is at first complicated to use but very powerful especially for note taking

# Packages included in the Template

| Package                                           | Description                                                                                                                                  |
| ------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| [pdfpages](https://ctan.org/pkg/pdfpages)         | Allows you to include PDFs in your document                                                                                                  |
| [csvsimple](https://ctan.org/pkg/csvsimple)       | Allows you to include CSV files in a table or put the information contained in a variable in your document                                   |
| [tikz](https://www.ctan.org/pkg/pgf)              | Allows you to create vector graphics                                                                                                         |
| [pgfplots](https://www.ctan.org/pkg/pgfplots)     | based on Tikz, allows to create scientific/technical graphs in a simple way                                                                  |
| [circuitikz](https://www.ctan.org/pkg/circuitikz) | based on Tikz, for the composition of electrical circuit diagrams                                                                            |
| [multicol](https://www.ctan.org/pkg/multicol)     | Allows you to create several columns                                                                                                         |
| [setspace](https://www.ctan.org/pkg/setspace)     | Allows you to define the spacing between lines in a document                                                                                 |
| [amsmath](https://www.ctan.org/pkg/amsmath)       | To improve the information structure and print output of your document                                                                       |
| [listings](https://www.ctan.org/pkg/listings)     | Allows you to include code snippets with syntax highlighting                                                                                 |
| [pifont](https://www.ctan.org/pkg/pifont)         | Allows you to add certain symbols (listed [here](https://borntocode.fr/wp-content/uploads/2015/04/Latex-listes-pifont.png)) to your document |
| [enumitem](https://www.ctan.org/pkg/enumitem)     | Allows the user to control the layout of the three basic list environments: enumerate, itemize and description                                |
| [tcolorbox](https://www.ctan.org/pkg/tcolorbox)   | Provides an environment for coloured and framed text areas with a header line                                                                |
| [siunitx](https://www.ctan.org/pkg/siunitx)       | A comprehensive (SI) units                                                                                                                   |

# Custom environements

| Environement                  | Code                                                                                           | Result |
|-------------------------------|------------------------------------------------------------------------------------------------|--------|
| Simple colorbox w/ title      | ```latex<br>\begin{colorbox}{Title}{yellow}<br>   Text in box<br>\end{colorbox}<br><br>```     |        |
| simple colorbox without title | ```latex<br>\begin{colorbox}{}{red}<br>   Text in box<br>\end{colorbox}<br><br>```             |        |
| definition colorblock         | ```latex<br>\begin{definition}{Title}<br>  Text in definition<br>\end{definition}<br><br>```   |        |
| definition* colorblock        | ```latex<br>\begin{definition*}{Title}<br>  Text in definition<br>\end{definition*}<br><br>``` |        |
| exemple colorbox              | ```latex<br>\begin{exemple}{Title}<br>  Text in example<br>\end{exemple}<br><br>```            |        |
| exemple* colorbox             | ```latex<br>\begin{exemple*}<br>  Text in example<br>\end{exemple*}<br><br>```                 |        |
| attention colorbox            | ```latex<br>\begin{attention}{Title}<br>   Text in warning box<br>\end{attention}<br><br>```   |        |
| vertAlign environement        | ```latex<br>\begin{vertAlign}<br>   Text in vertAlign<br>\end{vertAlign}<br><br>```            |        |
# Credits

# License