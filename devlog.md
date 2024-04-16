# DevLog

## Info
- using Flair for NER
  - [official tutorial of flair](https://huggingface.co/flair/ner-english)
  - [a medium post of using flair for NER](https://medium.com/thecyphy/training-custom-ner-model-using-flair-df1f9ea9c762)



## Encountered
- error while importing flair: "ImportError: cannot import name 'triu' from 'scipy.linalg'"
  - these two github issue explain the issue:
    - [ImportError: cannot import name 'triu' from 'scipy.linalg'](https://github.com/flairNLP/flair/issues/3441)
    - [Gensim broken with SciPy 1.13.0](https://github.com/piskvorky/gensim/issues/3525)
  - workaround: scipy version should be inferior to 1.11.0 (included)


