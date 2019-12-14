# Pattern Recognition Project SPM  
PatternRecognition 191008 ~ 191214  

---

<br/>

### **This release is not useful, because original version have some problem like wrong kernel**

<br/>

# 0.5_release

<br/>

- 0.33 >> 0.5 (adding SPM.ver before origin 0_depth reconstruction )
- 2_depth(SPM) + HOG + not SPM(kernel)

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

- GridSearch_best_parameter : {'svc__C': 1, 'svc__gamma': 0.005}
---