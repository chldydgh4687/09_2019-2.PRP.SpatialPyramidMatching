# Develop branch
---
# Subscription
---
## ~20191201
- ~~HOG + SPM = 0.33~~
- ~~HOG + SPM + SVC = 0.49~~

- HOG + LinearSVC = 0.33
- HOG + SPM + LinearSVC = 0.49

## 20191202
- **GridSearch Optimalization( to find best parameter ) = 0.5 (0.5 release)**

- try ~ 10 I changed kernel. results are

poly : 0.48522  
sigmoid : 0.08687  
precomputed : not fit  
linear : 0.50709  
rbf : 0.50059  
  
## 20191203

- By using gaussian filter, accuracy down. and I dump out it.

## 20191204

- I inspect kernel problem. I used linear kernel.
- so, I clean up code again.
- (0_depth) 0.33 >> 0.419 

## 20191205

- **HOG + SPM + SVC(SPM kernel) = 0.52_release**
- not PCA, LDA

## 20191207

- **Feature_Step_size == SPM step_size = 8 = 0.53_release**

## 20191213

- **SPM메커니즘에 들어가는 데이터를 (images >> feature)  로 교체 = 0.57_release**

## 20191214

- **StandardScaler 적용 (+0.02) - 0.59 release**
- RobustScaler 적용 (+0.00)

- **codebook size 변경 (+0.02) - 0.61 release**
