# Pattern Recognition Project SPM  
PatternRecognition 191008 ~ 191214  

---

<br/>

# 0.61_release

<br/>

- 0.59 (spm.ver) >> 0.61
- 2_depth(SPM) + HOG + SPM(kernel)
- codebook 200 >> 800 조정

<br/>

## PARAMETER

<br/>

- background : O (0.61)

- step_size = 8 , SPM_step_size = 8 
- img_size = 256  
  
- kmeans : minibatchkmeans  
- codebook : 800
  
- spm depth : 2  
- scaler : StandardScaler()

- kernel : 'precomputed' = spm_kernel  
- svm : svc

- GridSearch_best_parameter : {'C': 0.005, 'gamma': 1e-07}
---
