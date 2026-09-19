# MSDS 453: Natural Language Processing

Northwestern University, School of Professional Studies.

Course materials for MSDS 453. Open any notebook in Google Colab and run it top to
bottom; everything it needs is downloaded at runtime, so there is nothing to install
and nothing to configure.

## Notebooks

| Notebook | What it covers |
|---|---|
| `MSDS453_Discussion_01` | Preparing and submitting your ten movie reviews for the class corpus |
| `MSDS453_Assignment_01` | First vectorized representation: CountVectorizer, TF-IDF, Word2Vec, Doc2Vec, ELMo |
| `MSDS453_Assignment_02` | Classification and clustering: LSA, LDA, BERTopic, KMeans, SVM, logistic regression, naive Bayes, random forest, BERT |
| `MSDS453_Assignment_03` | Ontology, knowledge graphs, and recurrent models for genre classification |

Each notebook prints its version and the quarter when you run it, for example
`Notebook Version: 29.1 | Fall 2026`. Quote that line if you report a problem.

## The class corpus

`MSDS453_ClassCorpus/class_corpus.csv` holds 200 movie reviews: 20 movies across four
genres (Action, Comedy, Horror, Sci-Fi), half positive and half negative. It is built
from the reviews the class submits in Discussion 01.

The assignment notebooks download it automatically. You do not need to fetch it
yourself. The file path stays the same every quarter while its contents change, so a
notebook never needs editing between terms.

When a notebook loads it, it prints what it got:

```
Corpus: class_corpus.csv | 200 documents | 20 movies
```

If you want to experiment on your own data, point `CORPUS_URL` at a local file; the
comment beside the loading cell in Assignment 01 shows how.

## Running locally instead of on Colab

The notebooks run on Python 3.12 and select libraries available on Colab. Running
outside Colab works but is unsupported; a few cells use `!pip install`, which assumes
a Colab-style environment.

## Attribution

Built on course materials from `barrycforever/MSDS_453_NLP`, used under the MIT
License and retained here under the same terms.

Maintained by Kartik Shridhar.
