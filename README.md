# crm_ultr
Official code repository for the SIGIR 2023 paper "Safe Deployment for Counterfactual Learning to Rank with Exposure-Based Risk Minimization". 

## Update

I have released the source code for the CIKM 2024 paper on safe doubly robust method for trust-bias at https://github.com/shashankg7/cikm-safeultr/tree/master. 
It's a generalization of the SIGIR work, which extends the safety paradigm from position bias and the IPS to trust bias and doubly-robust estimator.  
The code can be adjusted to work for the position bias and IPS setting (for ex by setting the beta parameter to zero and by setting the regression model's output to zero). 

## Paper
If you use our code in your research, please remember to cite our work:

```BibTeX
    @inproceedings{gupta-2024-practical,
      author = {Gupta, Shashank and Oosterhuis, Harrie and de Rijke, Maarten},
      booktitle = {CIKM 2024: 33rd ACM International Conference on Information and Knowledge Management},
      date-added = {2024-07-16 08:06:13 -0400},
      date-modified = {2024-07-16 08:08:20 -0400},
      month = {October},
      publisher = {ACM},
      title = {Practical and Robust Safety Guarantees for Advanced Counterfactual Learning to Rank},
      year = {2024}}

    @inproceedings{gupta-2023-safe,
      author = {Gupta, Shashank and Oosterhuis, Harrie and de Rijke, Maarten},
      booktitle = {SIGIR 2023: 46th international ACM SIGIR Conference on Research and Development in Information Retrieval},
      date-added = {2023-04-05 14:39:36 +0100},
      date-modified = {2023-07-20 06:44:36 +0200},
      month = {July},
      pages = {249--258},
      publisher = {ACM},
      title = {Safe Deployment for Counterfactual Learning to Rank with Exposure-Based Risk Minimization},
      year = {2023}},
    }
```
