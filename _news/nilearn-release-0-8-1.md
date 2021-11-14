---
title: "Nilearn 0.8.1 release"
collection: news
language: "Python"
permalink: /news/nilearn-0-8-1
date: 2021-09-16
---

We just released [nilearn 0.8.1](https://pypi.org/project/nilearn/)! You can get it through pip: `$ pip install nilearn`.

### Highlights

This new release fixes some bugs and adds a bunch of new functionalities, among which:

- New atlas fetcher ``nilearn.datasets.fetch_atlas_juelich`` to download Juelich atlas from FSL.

- New grey and white-matter template and mask loading functions: ``nilearn.datasets.load_mni152_gm_template``, ``nilearn.datasets.load_mni152_wm_template``, ``nilearn.datasets.load_mni152_gm_mask``, and ``nilearn.datasets.load_mni152_wm_mask``.

- Nilearn development process has been reworked. It now provides insights on nilearn organization as a project as well as more explicit Contribution Guidelines.

- ``nilearn.image.binarize_img`` binarizes images into 0 and 1.

