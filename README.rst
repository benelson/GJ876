GJ876
========

This is a repository for posterior samples of the Gliese 876 planetary system. Methodological and science details can be found at [this arXiv link](http://arxiv.org/abs/1504.07995).


How to read these files
-----------------------

The two files listed above contain posterior samples directly from the RV observations (raw) and by imposing a 10 million year stability criterion (stable). Each line is a posterior sample containing 68 values. They read as follows.


MCMC information::

    Column 1: Markov chain generation
    Column 2: Markov chain index
    Column 3: Chi squared with jitter penalty term


Orbital Parameter information. Each planet has 9 parameters::

    Columns 4, 13, 22, 31: Orbital period in [days] for planets "d", "c", "b", and "e" respectively.
    Columns 5, 14, 23, 32: RV half amplitude in [m/s] for planets "d", "c", "b", and "e" respectively.
    Columns 6, 15, 24, 33: mass in [solar masses] for planets "d", "c", "b", and "e" respectively.
    Columns 7, 16, 25, 34: semi-major axis in [AU] for planets "d", "c", "b", and "e" respectively.
    Columns 8, 17, 26, 35: eccentricity for planets "d", "c", "b", and "e" respectively.
    Columns 9, 18, 27, 36: inclination in [degrees] for planets "d", "c", "b", and "e" respectively.
    Columns 10, 19, 28, 37: argument of pericenter in [degrees] for planets "d", "c", "b", and "e" respectively.
    Columns 11, 20, 29, 38: longitude of ascending node in [degrees] for planets "d", "c", "b", and "e" respectively.
    Columns 12, 21, 30, 39: mean anomaly at the epoch of the first Lick observation in [degrees] for planets "d", "c", "b", and "e" respectively.


Instrumental parameter information::

    Columns 40, 41: Carnegie HIRES RV offsets
    Column 42: California HIRES RV offset
    Column 43: ELODIE RV offset
    Column 44: CORALIE RV offset
    Column 45: HARPS RV offset

    Column 46: Carnegie HIRES RV jitter
    Column 47: California HIRES RV jitter
    Column 48: ELODIE RV jitter
    Column 49: CORALIE RV jitter
    Column 50: HARPS RV jitter


Supplementary information::

    Column 51: Chi squared without jitter
    Column 52: Run length (number of subsequent states in the Markov chain without an Metropolis-Hastings acceptance)
    Column 53: Chi squared with jitter (no penalty term)
    Column 54: Stellar mass in [solar masses]


Attribution
-----------

I will list a BibTeX entry once it gets listed.