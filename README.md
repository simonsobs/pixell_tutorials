# pixell_tutorials
These notebooks have been developed by the Simons Observatory collaboration to demonstrate how one can use the [`pixell`](https://github.com/simonsobs/pixell) repository to perform analyses on rectangular (CAR) maps.

Each notebook has been written to work in Google colab and can be accessed either by clicking the colab button in the notebook file above, or using the links below. In case the notebook is too large to render in your browser, simply access colab by changing `github` in the notebook url to `githubtocolab` and refresh. Note: this will open a frozen, read-only version. It will still run, but if you want to edit or save your work, you will need to first save a copy of the colab notebook in your personal Google drive. If you want to adapt these notebooks to run on your laptop or on a cluster, you can also clone the repository! However, you may need to manage the notebook dependencies manually.

## Notebooks:

We recommend working through notebooks in the following order:

- [Map manipulation](https://github.com/simonsobs/pixell_tutorials/blob/master/pixell_map_manipulation.ipynb): The basics of loading, plotting, and operating on recatngular (CAR) maps with `pixell`

- [Fourier-space operations](https://github.com/simonsobs/pixell_tutorials/blob/master/pixell_fourier_space_operations.ipynb): Two-dimensional Fourier transforms with `pixell`

- [Spherical harmonics](https://github.com/simonsobs/pixell_tutorials/blob/master/pixell_spherical_harmonics.ipynb): Spherical harmonic transforms with `pixell`

- [Reprojection and resampling](https://github.com/simonsobs/pixell_tutorials/blob/master/pixell_reprojection_and_resampling.ipynb): Transforming maps to and from HEALPix to CAR, and between different geometries within `pixell`

- [Matched filtering](https://github.com/simonsobs/pixell_tutorials/blob/master/pixell_matched_filtering.ipynb): Demonstrating `pixell` utilities for identifying compact objects in maps

- [Simulations](https://github.com/simonsobs/pixell_tutorials/blob/master/pixell_simulations.ipynb): Demonstrating `pixell` utilities for simulating maps, including Gaussian fields, lensing, and compact objects
