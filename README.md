# ENGEP
R package supporting the paper **"ENGEP: An ensemble learning tool for spatially
unmeasured genes expression prediction"**. 

ENGEP combins multiple prediction results from different reference datasets and prediction methods using a weighted average ensemble strategy to predict expression levels of spatially unmeasured genes. ENGEP mainly includes two steps: (i) generating multiple base results using k-nearest-neighbor (k-NN) regression. Different reference datasets, similarity measures, and numbers of neighbors (k) are used for this step. (ii) Combining these base results into a consensus result using a weighted average ensemble strategy. In this step, weights are assigned to different reference datasets to take into account their predictive power. 
![image](https://github.com/st-yang97/ENGEP/blob/master/docs/Figure1.jpg)

## Installation

 ``` buildoutcfg
 install.packages("devtools")
 devtools::install_github("Zhangxf-ccnu/ENGEP")
 ```

