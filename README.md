# Crowdsourcing Data for Product Search Explanation Evaluation

This repository provides the data created by the crowdsourcing experiment for product search explanation evaluation in <a href="https://arxiv.org/pdf/2108.05317.pdf">*Model-agnostic vs. Model-intrinsic Interpretability for Explainable Product Search*</a>

The experiment conducted pairwise comparisons between the search explanation provided by <a href="https://arxiv.org/abs/1909.07212">Vanilla DREM</a> and <a href="https://arxiv.org/pdf/2108.05317.pdf">DREM-HGN</a>.

## Data Structure

* explanation\_sample.csv: the product search explanations provided by DREM and DREM-HGN.

* AMT\_result.csv: the annotation results from AMT workers (0: bad, 1:good).

## Experimental Setup

The settings used for AMTurk workers are:
* HIT Approval Rate (%) for all Requesters' HITs greater than 80
* Number of HITs Approved greater than 1000
* Location is US

## Data Preparation

Our crowdsourcing dataset is sampled from the retrieval experiment dataset of Electronics, which can be found in the <a href="http://jmcauley.ucsd.edu/data/amazon/links.html">*Amazon Review Datasets*</a>. 

The source code for creating the explanations and crowdsourcing UI can be found in <a href="https://github.com/utahIRlab/drem-evaluation">here</a>.
For more detailed information, please refer to the paper.

## Citation

If you use these data in your research, please cite with the following BibTex entry.

```
@misc{ai2021modelagnostic,
      title={Model-agnostic vs. Model-intrinsic Interpretability for Explainable Product Search}, 
      author={Qingyao Ai and Lakshmi Narayanan Ramasamy},
      year={2021},
      eprint={2108.05317},
      archivePrefix={arXiv},
      primaryClass={cs.IR}
}
```

