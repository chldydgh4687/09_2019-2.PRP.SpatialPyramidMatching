# Pattern Recognition Project SPM  
PatternRecognition 191008 ~ 191214  

---

<br/>

# 0.52_release

<br/>

- 0.41 (0_depth) >> 0.52 (adding SPM.ver)
- 2_depth(SPM) + HOG + SPM(kernel)

<br/>

## PARAMETER

<br/>

- step_size = 16 , SPM_step_size = 8 
- img_size = 256  
  
- kmeans : minibatchkmeans  
- codebook : 200  
  
- spm depth : 2  
  
- kernel : 'precomputed' = spm_kernel  
- svm : svc

- GridSearch_best_parameter : {'C': 0.005, 'gamma': 1e-05}
---
