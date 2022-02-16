# Modélisation thématique
Dans le notebook [`modelisation_thematique.ipynb`](modelisation_thematique.ipynb),
nous effectuons de la modélisation thématique de textex à l'aide de modules Python spécialisés.

## Logiciels prérequis
* [Java (JDK >= 16)](https://www.oracle.com/java/technologies/downloads/): Java SE Development Kit
* [Apache Ant (version >= 1.10.10)](https://ant.apache.org/bindownload.cgi): différents outils pour des applications Java
* [MALLET 2.0.8](https://mallet.cs.umass.edu/download.php): MAchine Learning for LanguagE Toolkit

## Modules Python requis
* `nltk`: le [Natural Language Toolkit](https://www.nltk.org/)
* `gensim/3.8.3`: décrit comme étant ["*the fastest library for training of vector embeddings*"](https://radimrehurek.com/gensim_3.8.3/)
* `spacy`: [Industrial-Strength Natural Language Processing](https://spacy.io/)
* `pyLDAvis/3.3.1`: [Python library for interactive topic model visualization](https://pypi.org/project/pyLDAvis/)

Pour les installer, ainsi que leurs dépendances, utilisez `pip` sur une ligne de commande:
```Bash
# Préfixez ces commande par un "!" si vous voulez installer à partir d'un notebook
pip install matplotlib numpy pandas click==7.1.2
pip install nltk gensim==3.8.3 spacy pyLDAvis==3.3.1
```

## Vocabulaire français requis pour spaCy
Pour installer une banque de vocabulaire en français:
```Bash
# Préfixez ces commande par un "!" si vous voulez installer à partir d'un notebook
python -m spacy download fr_core_web_sm
```
