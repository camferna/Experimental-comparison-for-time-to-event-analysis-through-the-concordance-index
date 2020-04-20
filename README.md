# Experimental-comparison-for-time-to-event-analysis-through-the-concordance-index
Experimental comparison of semi-parametric, parametric and machine learning models for time-to-event analysis through the concordance index.

Paper: https://hal.archives-ouvertes.fr/hal-02507132 <br />
Arxiv: https://arxiv.org/pdf/2003.08820.pdf

Code requirements:

- Anaconda Python 3.7
- Additional packages: scikit-survival, pysurvival, lifelines
- cython compilation:

```
python setup_random_survival_forest_cython.py build_ext --inplace
```

This files were downloaded from George Chen's library: https://github.com/georgehc/npsurvival

## How to install pysurvival
This package contains C++ source code, pip needs a C++ compiler to install pysurvival.

The recommended C++ compiler is GCC. For more details on how to install it for Mac OS and Linux visit this website: https://square.github.io/pysurvival/installation.html

After you have installed GCC the easiest way to install pysurvival is using pip

```
pip install pysurvival
```

For installation on Window you can download the files directly from: https://github.com/bacalfa/pysurvival

First build the package

```
python setup.py build_ext --inplace
```

To install the package from the files in your computer

```
python setup.py install --user
```

