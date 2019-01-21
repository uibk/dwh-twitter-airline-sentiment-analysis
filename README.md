# Case Example - Twitter U.S. Airline Sentiment Analysis
This case example was done within the scope of the seminar paper _"Social Media Analytics"_ for the 2018/2019 Data Warehouse Systems Seminar ([703615 SE/2 SE](https://lfuonline.uibk.ac.at/public/lfuonline_lv.details?lvnr_id_in=703615&sem_id_in=18W)) by [Univ.-Prof. Mag. Dr. Maier Ronald](https://www.uibk.ac.at/wipl/team/team/maier.html.en)

The case example was developed using [python](https://www.python.org/) and [jupyter](https://jupyter.org/) along with several python libraries that can be found in [`requirements.txt`](/requirements.txt) file. The main analysis can be found in the [`twitter-airline-sentiment-analysis.ipynb`](/twitter-airline-sentiment-analysis.ipynb) notebook.

**Update 21-01-2019**

The [`twitter-airline-sentiment-analysis-vader-comparison.ipynb`](/twitter-airline-sentiment-analysis-vader-comparison.ipynb) notebook was included to show a comparison of human verified sentiment classification to [VADER classification](http://comp.social.gatech.edu/papers/icwsm14.vader.hutto.pdf).

## Authors
- Johannes Ebster, [3bst0r](https://github.com/3bst0r)
- Daniel Egger, [dnlggr](https://github.com/dnlggr)
- Jannik Siebert, [janniks](https://github.com/janniks)

## Development

_Default python3 and pip are required to run this notebook._

Set up a `.venv` virtual environment
```
python3 -m venv .venv
```

Activate the `.venv` virtual environment
```
. .venv/bin/activate
```

Install the requirements defined in `requirements.txt`
```
pip install -r requirements.txt
```

Start jupyter and open `twitter-airline-sentiment-analysis.ipynb`
```
jupyter notebook
```

## Attributions
- [Twitter US Airline Sentiment](https://www.kaggle.com/crowdflower/twitter-airline-sentiment) - Analyze how travelers in February 2015 expressed their feelings on Twitter
- Based on an [article](https://medium.com/@martinpella/customers-tweets-classification-41cdca4e2de) from the data scientist [Martín Pellarolo](https://github.com/martinpella)
- [Crowdflower](http://www.crowdflower.com/data-for-everyone/)
