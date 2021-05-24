---
title: "Nilearn 0.7.1 release"
collection: news
language: "Python"
permalink: /news/nilearn-0-7-1
date: 2021-03-10
---

We just released [nilearn 0.7.1](https://pypi.org/project/nilearn/)! You can get it through pip: `$ pip install nilearn`.

This new release fixes some bugs and adds a bunch of new functionalities, among which:

- New atlas fetcher to download *Dictionaries of Functional Modes*, or “DiFuMo”, that can serve as atlases to extract functional signals with different dimensionalities.

- *Decoder* and *DecoderRegressor* are now implemented with random predictions to estimate a chance level.

- Plotting functions are now implemented with new display mode Mosaic. That implies plotting 3D map
  in multiple columns and rows in a single axes.

