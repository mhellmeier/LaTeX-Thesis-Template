LaTeX Thesis Template
=====================
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

A LaTeX thesis template, originally made for seminar, bachelor and master paper.

## Table of Contents

- [Background](#background)
- [Getting Started](#getting-started)
    - [Pre-Requirements](#pre-requirements)
    - [Installation](#installation)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [References](#references)
- [License](#license)
- [Contact](#contact)



## About the Project

I created this LaTeX thesis template during my studies. It is very much based on the guidelines from the [Chair of Information Management](https://www.uni-goettingen.de/en/57609.html) at the University of Göttingen. Please keep in mind that this is a **private** and **unofficial** template made by myself which isn't related or reviewed by the University of Göttingen. Thus, it can be used for different projects at different universities.

<p align="center">
    <img src="https://user-images.githubusercontent.com/1036284/113028869-13e29f00-918c-11eb-891c-984c441c8ba3.png" width="35%" />
    &nbsp; &nbsp; &nbsp; &nbsp;
    <img src="https://user-images.githubusercontent.com/1036284/113028918-1fce6100-918c-11eb-95e6-25026cbc9b1a.png" width="35%" />
</p>

## Getting Started

### Pre-Requirements

Make sure that you have installed TeX correctly. If you get some errors, check if you installed all packages / dependencies. It should also work with online editors like [Overleaf](overleaf.com).

It is highly recommend to use a reference management software to generate the `literature.bib` file automatically. I suggest using [Zotero](https://www.zotero.org/) in combination with [Better BibTeX](https://retorque.re/zotero-better-bibtex/).

### Installation

1. Clone the repository
```sh
git clone https://github.com/mhellmeier/LaTeX-Thesis-Template.git
cd LaTeX-Thesis-Template
```
2. Open the `thesis.tex` with the LaTeX editor of your choice
3. Compile it and get started!

Some additional hints:
* Examples are giving in the `*.tex` files
* The citation style is based on the [MISQ reference format](https://misq.org/manuscript-guidelines)
* Important files and folders:
  * `thesis.tex`: Main file
  * `front-page.tex`: First page of your thesis
  * `packages.tex`: Put all your `\usepackage` commands in here
  * `definitions.tex`: Location for custom preamble code
  * `acronyms.tex`: Collection of your acronyms / abbreviations
  * `literature.bib`: Collection of your literature (for BibLaTeX)
  * `images/`: Put all your figures in this directory


## Roadmap

All planned features, bugs and discussions can be found in the [issues tab](https://github.com/mhellmeier/LaTeX-Thesis-Template/issues).


## Contributing

Feel free to fork the project, work in your personal branch and create a pull request or you simply interact in the [issue section](https://github.com/mhellmeier/LaTeX-Thesis-Template/issues).

**This is an open-source project! Every contribution is greatly appreciated!**


## References

The template is inspired by others like [this one](https://www.uni-goettingen.de/en/544970.html). I found a lot of help at [TeX Stackexchange](https://tex.stackexchange.com/). Some adopted code snippets are linked to their original answers in a comment at the respective positions.


## License

Distributed under the MIT License. See `LICENSE` for more information.


## Contact

Malte Hellmeier - [![LinkedIn][linkedin-shield]][linkedin-url]

Project Link: [https://github.com/mhellmeier/LaTeX-Thesis-Template](https://github.com/mhellmeier/LaTeX-Thesis-Template)


[issues-shield]: https://img.shields.io/github/issues/mhellmeier/LaTeX-Thesis-Template.svg?style=flat-square
[issues-url]: https://github.com/mhellmeier/LaTeX-Thesis-Template/issues
[license-shield]: https://img.shields.io/github/license/mhellmeier/LaTeX-Thesis-Template.svg?style=flat-square
[license-url]: https://github.com/mhellmeier/LaTeX-Thesis-Template/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/malte-hellmeier-91a64a17b/