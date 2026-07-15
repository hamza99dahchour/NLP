# NLP — Labs & Assignments

Ensemble de notebooks réalisés dans le cadre d'un cours de **Natural Language Processing (NLP)**, couvrant les fondamentaux du traitement automatique du langage : manipulation de texte, prétraitement, représentations classiques (BoW, TF-IDF), embeddings (Word2Vec, GloVe, BERT), et tâches NLP de base (POS tagging, NER, similarité).

## Contenu

| Fichier | Sujet |
|---|---|
| `lab1_manipulate_text_data_Hamza_Dahchour.ipynb` | Manipulation de chaînes de caractères en Python et premières expressions régulières |
| `lab2_text_preprocessing_pipeline_Hamza_Dahchour.ipynb` | Pipeline de prétraitement de texte : tokenisation, stemming, lemmatisation, suppression des stop words |
| `Hamza_DAHCHOUR_lab3_Part1_TextVisualization_Classical.ipynb` | Visualisation de texte (word clouds, bar charts), représentations classiques (Bag of Words, TF-IDF), N-grams, prédicteur de mot suivant — sur le dataset 20 Newsgroups |
| `hamza_dahchour_lab3_part2_wordembeddings_(1).py` | Embeddings de mots et de phrases : Word2Vec (CBOW / Skip-gram), GloVe pré-entraîné, embeddings BERT, comparaison des approches |
| `Hamza_DAHCHOUR_lab4_Part1_CoreNLP_Tasks.ipynb` | Tâches NLP fondamentales : POS tagging, Named Entity Recognition (NER), calcul de similarité entre mots/documents — appliquées à un dataset de descriptions de produits Nike |
| `HAMZA_DAHCHOUR_Assignment1_Part1_Regex.ipynb` | Extraction de dates par expressions régulières (plusieurs formats de dates) |
| `HAMZA_DAHCHOUR_Assignment1_Part2_NLTK.ipynb` | Prétraitement et analyse de texte avec NLTK (diversité lexicale, fréquence de tokens, etc.) |

## Stack technique

- **Python** : NLTK, gensim, scikit-learn, spaCy / CoreNLP (selon les labs)
- **Deep Learning / Embeddings** : Word2Vec, GloVe, BERT (via `transformers` et `sentence-transformers`)
- **Visualisation** : Matplotlib, WordCloud
- **Environnement** : Jupyter Notebook / Google Colab

## Utilisation

Chaque notebook est autonome et peut s'ouvrir directement dans **Google Colab** via le badge présent en haut de chaque fichier, ou en local :

```bash
pip install nltk gensim scikit-learn matplotlib wordcloud transformers sentence-transformers torch datasets
jupyter notebook
```

Certains notebooks téléchargent des ressources NLTK (`punkt`, `stopwords`, `wordnet`) ou des datasets (20 Newsgroups, descriptions produits Nike) directement depuis leur première cellule.

## Contexte

Ces notebooks correspondent à des labs et assignments réalisés dans le cadre d'un cours de NLP (exercices guidés avec objectifs pédagogiques précisés en en-tête de chaque notebook). Ils sont partagés ici à titre de portfolio technique.
