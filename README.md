corpus2question
===============

This repository presents `corpus2question`, a method for summarizing and exploring datasets based on latent questions on documents. It also contains the reference implementation for the paper [Can questions summarize a corpus? Using question generation for characterizing COVID-19 research.](http://#).


## The method

`corpus2question` relies on the question generation network used in [doc2query](https://github.com/castorini/docTTTTTquery) and frequency aggregations. Check [our tutorial](./tutorial.ipynb) for a small example.

![Illustration of the corpus2question method, using question generation followed by aggregations.](./images/qg_pipeline.pdf)


# #Results over the CORD-19 dataset

The generated questions over the CORD-19 dataset are available at this link in the CSV format. The reference implementation for the paper is available at [this notebook](./paper reference.ipynb).
