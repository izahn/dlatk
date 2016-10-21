# Differential Language Analysis ToolKit

DLATK is an end to end text analysis package written in Python 3 and developed by the World Well-Being Project at the University of Pennsylvania. It contains:

- feature extraction
- part-of-speech tagging
- correlation
- prediction and classification
- mediation 
- clustering
- wordcloud visualization
- [Mallet](http://mallet.cs.umass.edu/) interface for creating LDA topics
- [Stanford Parser](http://nlp.stanford.edu/software/lex-parser.shtml) interface
- [CMU's TweetNLP](http://www.cs.cmu.edu/~ark/TweetNLP/) interface
- [pandas](http://pandas.pydata.org/) dataframe output

## Installation

DLATK is available via conda, pip or github.

```sh
conda install -c wwbp dlatk
```

```sh
pip install dlatk
```

```sh
python setup.py install
```

## Dependencies
- [mysqlclient](https://github.com/PyMySQL/mysqlclient-python)
- [NumPy](http://www.numpy.org)
- [scikit-learn](http://www.scikit-learn.org/)
- [SciPy](http://www.scipy.org/)
- [statsmodels](http://www.statsmodels.org/)

See the [full installation instructions](http://dlatk.wwbp.org/install.html#dependencies)
for recommended and optional dependencies.

## Documentation

The documentation for the latest release is at [dlatk.wwbp.org](dlatk.wwbp.org).

## License

Licensed under a [GNU Lesser General Public License v3 (LGPLv3)](https://www.gnu.org/licenses/lgpl-3.0.en.html)

## Background

Developed by the [World Well-Being Project](http://www.wwbp.org) based out of the University of Pennsylvania [Positive Psychology Center](http://www.ppc.sas.upenn.edu/).