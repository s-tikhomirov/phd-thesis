# Security and Privacy of Blockchain Protocols and Applications

The PhD thesis by [Sergei Tikhomirov](https://s-tikhomirov.github.io/about/) prepared in 2016 – 2020 at the [University of Luxembourg](https://wwwen.uni.lu/) under the supervision of [Professor Alex Biryukov](https://www.cryptolux.org/index.php/Alex_Biryukov) and defended on 17 September 2020. The thesis consists of three parts:

1. Part 1: Network privacy in Bitcoin and privacy-focused cryptocurrencies
1. Part 2: Privacy of the Lightning Network
1. Part 3: Security of Ethereum smart contracts

See `tikhomirov-thesis.pdf` for the final version in PDF (identical to [the file in the official repository](http://hdl.handle.net/10993/44424)). See `tikhomirov-phd-defense-slides.pdf` for the presentation (see also: [animated version in Google slides](https://docs.google.com/presentation/d/1olqh-w25ONJcn069Zedm0_n-4A8jm-zJXdUd7DCGNaY/edit?usp=sharing), [video of the defense](https://youtu.be/Rf5r8hyZJnQ)).


# Build

1. Clone the repository (download and unpack is also OK):
```
git clone git@github.com:s-tikhomirov/phd-thesis.git
```
1. Open `main.tex` in TeXstudio
1. Press F5
1. See the result as `main.pdf`

To replace the title page with the official title page from the University of Luxembourg (generated from an official `.docx` template), run:

`./replace-title-page.sh`

See the result as `tikhomirov-thesis.pdf`.


# Toolset

The following software was used while preparing this thesis:

* Ubuntu 18.04.5 LTS
* Sublime Text 3.2.2
* TeXstudio 2.12.6 ([with `texlive-full`](https://tex.stackexchange.com/a/312867/142924))
* JabRef 5.1--2020-03-18--99183e1


# Acknowledgments

In addition to the people I thank in the dedicated "Acknowledgments" section, I thank all the [TeX StackExchange](https://tex.stackexchange.com/) contributors who helped me to solve so many [weird TeX problems](https://tex.stackexchange.com/q/537928/142924).
That would take me forever to fix on my own.
Why don't we write theses in Markdown?..

For the soundtrack for my writing process, I thank [Silk Music](https://www.youtube.com/watch?v=WsDyRAPFBC8) and [Shingo Nakamura](https://www.youtube.com/watch?v=WYp9Eo9T3BA), [ChilledCow](https://www.youtube.com/watch?v=5qap5aO4i9A) (yes, the famous "[study girl](https://knowyourmeme.com/memes/study-girl)"), and Alexander Nuzhdin's [FM Café](https://fmcafe.online/).
