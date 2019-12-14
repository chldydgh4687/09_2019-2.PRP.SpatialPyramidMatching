# Pattern Recognition Project SPM  
PatternRecognition 191008 ~ 191214  

---

<br/>

# 0.57_release

<br/>

- 0.52 (spm.ver) >> 0.57
- 2_depth(SPM) + HOG + SPM(kernel)
- histogram에 들어가는 그림데이터를 feature 데이터로 수정.
- 처음 feature step_size 와 spm step_size 동일하게 맞춤.

<br/>

## PARAMETER

<br/>

- background : X

- step_size = 8 , SPM_step_size = 8 
- img_size = 256  
  
- kmeans : minibatchkmeans  
- codebook : 200  
  
- spm depth : 2  
  
- kernel : 'precomputed' = spm_kernel  
- svm : svc

- GridSearch_best_parameter : {'C': 0.005, 'gamma': 1e-06}
---
