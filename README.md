# Paraphrases do not explain word analogies

Implementation of the Python code used for the EACL 2021 short paper: "Paraphrases do not explain word analogies".

The model preparation Jupyter file is to recreate the different models used and should be run first.

The main Jupyter file is used to load the different space models and data to do the various experiments detailled in the paper; mainly:
Linearity of the link between PMI and word2vec embeddings, error vectors norms, closeness rank of the paraphrase error.


## Getting Started

### Prerequisites

Python with classic libraries is enough; as well as Gensim version 4.0.0beta.

These experiences require a lot of memory to be computed.

### Installing

Run the "Models preparation" notebook first to pre-compute the models and matrices needed.

###

Run the "Main experiences" notebook to recreate the different experiences of the article.

## Authors

* Louis Fournier

## License

This project is licensed under the MIT License (?) - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* None of the libraries are models used are ours. We thank the original authors of these libraries and models.