# data-exploration-corenlp-fr-models

## Purpose

This repo repackages the CoreNLP french models with an added
NER model from [KB Labs](http://lab.kb.nl/dataset/europeana-newspapers-ner#access).


## Packaging

```bash
mvn package install
```


## Pushing to mirror

```bash
mcli mirror ~/.m2/repository/nekonyuu/corenlp-fr-models artifacts/snapshots/maven/nekonyuu/corenlp-fr-models
```
