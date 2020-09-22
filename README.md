corpus2question
===============

This repository presents `corpus2question`, a method for summarizing and exploring datasets based on latent questions on documents. It also contains the reference implementation for the paper [Can questions summarize a corpus? Using question generation for characterizing COVID-19 research](https://arxiv.org/abs/2009.09290).


## The method

[![Open All Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1V9ToJMpecZKQEKBIWDTbBVmkzdQYgcYQ)

`corpus2question` relies on the question generation network used in [doc2query](https://github.com/castorini/docTTTTTquery) and frequency aggregations. Check [our tutorial](./tutorial.ipynb) for a small example.


## Results over the CORD-19 dataset

All raw generated questions over the CORD-19 dataset are available at [this link](https://drive.google.com/file/d/12LNJAC2KaDKVcwuPHbVjyd3NVHU1KnLV/view?usp=sharing) in the CSV format. You can also find the aggregated top 10k at [this link](./results/top_10k.csv). The reference implementation for the paper is available at [this notebook](./paper%20reference.ipynb).

## Citing this work

If you use `corpus2question` on your academic work, or use the generated questions over the CORD-19 dataset, please cite us with:

```
@misc{surita2020questions,
    title={Can questions summarize a corpus? Using question generation for characterizing COVID-19 research},
    author={Gabriela Surita and Rodrigo Nogueira and Roberto Lotufo},
    year={2020},
    eprint={2009.09290},
    archivePrefix={arXiv},
    primaryClass={cs.IR}
}
```
