# PyData - London 2016
---

This repo contains the presentation *Python flying at 40,000 feet* by Raffaele Rainone and Marko Vasiljevski.

The first part of the presentation is available [here][slides].

The second part relies on the jupyter notebook in this repo. You can either look at the notebook or generate the slides. Running the following generates the file `pydata_presentation.slides.html`.

    $ jupyter nbconver pydata_presentation.ipynb --to slides

To directly convert the notebook into slides and open in browser run

    $ jupyter nbconver pydata_presentation.ipynb --to slides --post serve

(Notice that the `reveal.js` folder is taken from [here][revealjs] and it is needed to overcome the fact that jupyter sildes have locked scrolling. A more elegant method is for sure available: when I discover it, I'll update this repo.)

PS. All this machinery works on Ubuntu and MacOS, if you have compatibility issue drop me a line.