# TL_USS_Prediction

This repository contains the Python implementation of the instance-based transfer learning (IBTL) methods used in the the paper:

**"Instance-Based Transfer Learning for Cross-Regional Prediction of Undrained Shear Strength of Soils."**

Raied Ahmed Nishat, Fahmida Rahman, Nur Md. Robiul Hoque, and Shriful Islam

Shahjalal University of Science and Technology, Sylhet 3114, Bangladesh


---

## Files

- **iw_krr_tl_uss.py**  
  Implements **Instance Weighted Kernel Ridge Regression (IW-KRR)** for transfer learning. This method re-weights source domain samples to better match the target domain distribution.  
  Source: https://github.com/Ribosome25/Traditional_Transfer_Learning/blob/master/IW_KRR.py 
  Implementation by Ruibo Zhang, Texas Tech University

- **tradaboost_r2_tl_uss.py**  
  Implements the **TrAdaBoost.R2** algorithm, a boosting-based instance transfer learning method that iteratively down-weights poorly fitting source samples while improving prediction in the target domain.  
  Source code from: https://github.com/Bin-Cao/TrAdaboost/blob/main/TrAdaBoost_R2/TrAdaBoost_R2.py
  Implementation by Bin Cao, Hong Kong University of Science and Technology


- **two_stage_tradaboost_r2_tl_uss.py**  
  Implements a **Two-Stage TrAdaBoost.R2**, extending the TrAdaBoost.R2 by applying an additional filtering/weighting step to further refine instance transfer.  
  Source code from: https://github.com/jay15summer/Two-stage-TrAdaboost.R2/blob/master/TwoStageTrAdaBoostR2.py 
  Implementation by Jie Ren, Florida State University

