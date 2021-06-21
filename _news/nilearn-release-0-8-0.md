---
title: "Nilearn 0.8.0 release"
collection: news
language: "Python"
permalink: /news/nilearn-0-8-0
date: 2021-06-17
---

We just released [nilearn 0.8.0](https://pypi.org/project/nilearn/)! You can get it through pip: `$ pip install nilearn`.

### Highlights

This new release fixes some bugs and adds a bunch of new functionalities, among which:

- `nilearn.input_data.NiftiLabelsMasker` can now generate HTML reports in the same way as `nilearn.input_data.NiftiMasker`.

- `nilearn.signal.clean` accepts new parameter `sample_mask`. shape: `(number of scans - number of volumes removed, )`.

- All inherent classes of `nilearn.input_data.BaseMasker` can use parameter `sample_mask` for sub-sample masking.

- Fetcher `nilearn.datasets.fetch_surf_fsaverage` now accepts fsaverage3, fsaverage4 and fsaverage6 as values for parameter mesh, so that all resolutions of fsaverage from 3 to 7 are now available.

- Fetcher `nilearn.datasets.fetch_surf_fsaverage` now provides attributes `{area, curv, sphere, thick}_{left, right}` for all fsaverage resolutions.

- `nilearn.glm.first_level.run_glm` now allows auto regressive noise models of order greater than one.

### Warning

- Python 3.5 is no longer supported. We recommend upgrading to Python 3.8.

- Support for Nibabel `2.x` is deprecated and will be removed in the `0.9` release. Users with a version of Nibabel < `3.0` will be warned at their first Nilearn import.

- Minimum supported versions of packages have been bumped up:

- Numpy – v1.16
- SciPy – v1.2
- Scikit-learn – v0.21
- Nibabel – v2.5
- Pandas – v0.24


