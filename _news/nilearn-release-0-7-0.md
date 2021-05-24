---
title: "Nilearn 0.7.0 release"
collection: news
language: "Python"
permalink: /news/nilearn-0-7-0
date: 2020-11-12
---

We just released [nilearn 0.7.0](https://pypi.org/project/nilearn/)! You can get it through pip: `$ pip install nilearn`.

This new release fixes some bugs and adds a bunch of new functionalities, among which:

- Nilearn now includes the functionality of Nistats. This module is experimental, hence subject to change in any future release.

- New `Decoder` objects implement a model selection scheme that averages the best models within a cross validation loop.

- New `FREM` objects extend the `Decoder` object with one fast clustering step at the beginning and aggregates a high number of estimators trained on various splits of the training set.

- New plotting functions:

    - `plot_event` to visualize events file.
    - `plot_roi` can now plot ROIs in contours with view_type argument.
    - `plot_carpet` generates a "carpet plot" (also known as a "Power plot" or a "grayplot").
    - `plot_img_on_surf` generates multiple views of `plot_surf_stat_map` in a single figure.
    - `plot_markers` shows network nodes (markers) on a glass brain template.
    - `plot_surf_contours` plots the contours of regions of interest on the surface.

