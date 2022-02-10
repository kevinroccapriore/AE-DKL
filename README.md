# AE-DKL
Autonomous experimentation via deep kernel learning (DKL)
The following notebook and data demonstrates the use of DKL in scanning transmission electron microscopy (STEM), by effectively utilizing multidimensional signals learning structure-property relationships in the system under study.
Here, the full structural signal from the HAADF-STEM image is combined with the analytical signal from electron energy loss spectroscopy (EELS).
Using DKL, this generates a structure-property relationship between local image patches (in HAADF) and the EEL signal from the center of that image patch.

Finally, physics is embedded into this active learning process by scalarizing the EEL signal by the method of choice. For example, a 1D spectrum can be reduced to a single value by 1) using energy of peak maximum or 2) calculating peak ratios, as are demonstrated in the notebook. More complex scalarizers and mathematical operations may be used with the EEL signal to incorporate the desired physics of interest, for instance, take FFT of signal.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kevinroccapriore/AE-DKL/blob/main/AE_STEM_DKL_BO.ipynb)

The following bade is a link to the data itself

<a href="https://zenodo.org/badge/latestdoi/393487561"><img src="https://zenodo.org/badge/393487561.svg" alt="DOI"></a>





