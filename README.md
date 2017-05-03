### Spacy
# Natural Language Processing

## Getting started
[virtualenv](https://virtualenv.pypa.io/en/stable/).

    virtualenv -p python3 venv
    source venv/bin/activate

[conda virtual environments](http://conda.pydata.org/docs/using/envs.html):

	conda create --name venv python=3
	source activate venv

Install all the required Python dependencies:

    pip install -r requirements.txt

Install the spaCy model you need to run:

    sputnik --name spacy --repository-url http://index.spacy.io install en==1.1.0

To run jupyter notebook run:

    jupyter notebook