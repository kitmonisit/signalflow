# signalflow

A TikZ library by Karlheinz Ochs used to draw signal flow diagrams as seen in
[Example: Signal flow building
blocks](http://www.texample.net/tikz/examples/signal-flow-building-blocks/)

This repository is an attempt to fix problems with `\matrix` as illustrated
here: [signalflowdiagram does not draw anything with
`\matrix`](https://tex.stackexchange.com/q/462786/791).

## Installation

This is not an official TikZ library and cannot be found using the official TeX
installation managers.

### macOS (MacTeX)

1. Copy the `signalflowlibrary` folder into `/usr/local/texlive/texmf-local/tex/latex`. The directory tree should look like this:

        /usr/local/texlive/texmf-local/tex/latex
        └── signalflowlibrary
            ├── macros.sty
            ├── signalflowdiagram.sty
            ├── tikzlibrarysignalflowarrows.code.tex
            ├── tikzlibrarysignalflowblocks.code.tex
            ├── tikzlibrarysignalflowdiagram.code.tex
            └── tikzlibrarysignalflowoperators.code.tex

2. Run:

        $ mktexlsr

## Example

To use the included example, run:

    $ latexmk -pdf example.tex

