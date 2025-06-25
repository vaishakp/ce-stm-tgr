# Analysis planned





## Features and sensitivities
![image](https://github.com/user-attachments/assets/4f85ef7a-4b40-416e-961f-6917682e68ac)






## Proposed analysis

| Science Objective | Epoch/ Regime             | Test name       | Tool    | Fisher implementation status  |  Bayesian implementation status | Point of Contact        | References              | Notes                                       |   
| ------------------|---------------------------|-----------------|---------|-------------------------------|---------------------------------|-------------------------|-------------------------|---------------------------------------------|
|          1        | High frequency/ Ringdown  | PARSPEC         | GWFast  |                               |                                 |  Luca                   | 1910.12893, 2311.14803, |                                             |
|          1        | High frequency/ Ringdown  | PARSPEC         | GWBench |  Not implemented              |                                 |                         |                         |                                             |
|          1        | Low frequency/ Inspiral   |                 |         |                               |                                 |                         |                         |                                             |
|          1        | Bucket / Inspiral         | FTI             | GWBench |                               |                                 | Arnab                   |                         |                                             |
|          1        | Bucket / Ringdown         | pSEOB           | GWBench |                               |                                 | Arnab                   |                         |                                             |
|          3        | High frequency/ Ringdown  | spectroscopy    | pyring  |  NA                           |                                 |  Vaishak                |                         |                                             |
|          1        | IMR                       | consistency     |         |                               |                                 |                         |                         | Reuse inspiral only, ringdown only analysis |


### Comments
1. VP: ensure the Fisher tests can be validated against a Monte-Carlo sampling. i.e. check availability of corresponding implementation with sampling.
2. VP: Is PARSPEC RD test implemented in frequency doamin? Check for caveats.
3. VP: Ringdown tests not expensive. Can run samplers.
4. 
