# Pattern Recognition Project SPM  
PatternRecognition 191008 ~ 191214  

---

<br/>

# 0.59_release

<br/>

- 0.57 (spm.ver) >> 0.59
- 2_depth(SPM) + HOG + SPM(kernel)
- StandardScaler(feature) + Histogram 적용 (+0.02)
- RobustScaler는 변화가 없음.

<br/>

## PARAMETER

<br/>

- background : O (0.59)

- step_size = 8 , SPM_step_size = 8 
- img_size = 256  
  
- kmeans : minibatchkmeans  
- codebook : 200  
  
- spm depth : 2  
- scaler : StandardScaler()

- kernel : 'precomputed' = spm_kernel  
- svm : svc

- GridSearch_best_parameter : {'C': 0.005, 'gamma': 1e-07}
---
