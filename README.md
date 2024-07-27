# crm_ultr
Official code repository for the SIGIR 2023 paper "Safe Deployment for Counterfactual Learning to Rank with Exposure-Based Risk Minimization". 

## Update

I have released the source code for the CIKM 2024 paper on safe doubly robust method for trust-bias at https://github.com/shashankg7/cikm-safeultr/tree/master. 
It's a generalization of the SIGIR work, which only considered position bias and IPS method. In the CIKM paper, we conisder the doubly-robust estimator and trust bias.  
The code can be adjusted to work for the position bias and IPS setting (for ex by setting the beta parameter to zero and by setting the regression model output to zero). 
