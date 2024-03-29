# Natural Language Processing Toolkit

## Setup

You need Python 3.6+, and the packages mentioned in `requirements.txt`. You can install them using:

```bash
pip install -r requirements.txt
```

## Data

Data files for exercises are included under `data/`, but some of the NLP libraries require additional data for performing tasks like 
PoS tagging, lemmatization, etc. Specifically, `nltk` will throw an error if the required data is not installed. You can use the 
following Python statement to open the NLTK downloader and select the desired package(s) to install:

```python
nltk.download()
```

You can also download all available NLTK data packages, which includes a number of sample corpora as well, but that may take a while 
(10+GB).

## Run

To run any script file, use:

```bash
python <script.py>
```

To open a notebook, use:

```bash
jupyter notebook <notebook.ipynb>
```
