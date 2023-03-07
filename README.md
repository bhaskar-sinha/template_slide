# LaTeX Template for Academic Presentations

This repository contains a minimalist template to write academic presentations with LaTeX Beamer. 

## Template documentation

The template's documentation is available at https://pascalmichaillat.org/d1/.

## Template features

+ The font for text, roman math, and numbers is [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro).
+ The font for Greek and calligraphic math is [Euler](http://luc.devroye.org/fonts-26139.html).
+ No colors are used in the text (only black/gray) to reduce distraction. 
+ Colors are reserved for graphs and alerts.
+ Margins, spacing, and font size are set for comfortable reading.
+ There are no frills at the periphery of the slides.

## Repository content

+ `presentation.tex` –  LaTeX file containing the skeleton of the presentation.
+ `presentation.sty` –  LaTeX style file collecting all the formatting commands.
+ `figures.pdf` – PDF file with all the figures included in the presentation.
+ `presentation.pdf` – PDF file produced by compiling `presentation.tex` with pdfTeX.

## Template usage

+ Fill out `presentation.tex` with the content of your presentation. Compile the file with pdfTeX.
+ `presentation.sty` must be included in the same folder as `presentation.tex`. It can be modified to alter the presentation's format.
+ Replace the figures in `figures.pdf` with your own figures—one per page.
+ `presentation.pdf` is not required to use the template. It only illustrate the output of the template, and will be overridden once `presentation.tex` is compiled.
+ The template was developed with the MacTeX-2021 distribution but should hopefully also work with more recent distributions. 

## Related resources

+ [This LaTeX template](https://github.com/pmichaillat/latex-paper) produces academic papers following the same principles, and with a similar appearance, as this presentation template. 
+ [This LaTeX style file](https://github.com/pmichaillat/latex-math) contains commands to write mathematical expressions easily. It can be used in combination with this presentation template.

## License

The content of this repository is licensed under the terms of the MIT License.
