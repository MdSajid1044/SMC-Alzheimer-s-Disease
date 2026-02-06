CODES & DATASETS: Decoding Cognitive Health Using Machine Learning: A Comprehensive Evaluation for Diagnosis of Significant Memory Concern
----------------------------------------------------------------------
If you intend to use this work (dataset, code, results or any other material related to our paper: Decoding Cognitive Health Using Machine Learning: A
Comprehensive Evaluation for Diagnosis of Significant Memory Concern), kindly cite us as follows:

Reference: M. Sajid, Rahul Sharma, Iman Beheshti, and M. Tanveer “Decoding Cognitive Health Using Machine Learning: A Comprehensive Evaluation for Diagnosis of Significant Memory Concern” WIREs Data Mining and Knowledge Discovery (2024).

## BibTex
----------
```
@article{sajid2024decoding,
  title={Decoding cognitive health using machine learning: A comprehensive evaluation for diagnosis of significant memory concern},
  author={Sajid, M and Sharma, Rahul and Beheshti, Iman and Tanveer, Muhammad and Alzheimer's Disease Neuroimaging Initiative},
  journal={Wiley Interdisciplinary Reviews: Data Mining and Knowledge Discovery},
  volume={14},
  number={5},
  pages={e1546},
  year={2024},
  publisher={Wiley Online Library}
}
```


![widm1546-toc-0001-m](https://github.com/user-attachments/assets/06e02558-f0a5-4754-9f48-8b15224a8da3)

Introduction of SMC: Memory is a fundamental cognitive function essential for daily activities and deeply intertwined with our identities. As the global population ages, there is growing concern about age-related cognitive decline, particularly significant memory concern (SMC). SMC, or subjective cognitive decline (SCD), is a self-perceived decline in cognitive abilities without objective evidence of impairment. It is a common complaint among older individuals and may reflect an internal recognition of functional loss that has been compensated for. Recent research suggests that SCD may be an early indicator of more severe cognitive decline, including mild cognitive impairment (MCI) or dementia (Rabin et al., 2017). In other words, SMC refers to subjective complaints of memory impairment that are evident to individuals or their close associates but may not meet the criteria for clinical diagnosis of MCI or dementia (Jessen et al., 2020). As Alzheimer's disease (AD) pathology develops in the brain over several years before the beginning of MCI, those with SMCs may experience a distinct type of memory impairment that is distinct from the normal aging process, even before the onset of MCI (Gauthier et al., 2006). In addition, during the earliest stages of AD, increased neuronal activity, possibly driven by SMCs, may lead to normal performance on cognitive tests. Evidence indicates that indicators of SMC can be beneficial for forecasting cognitive deterioration in the elderly (Risacher et al., 2015).


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
## Authors
----------
M. Sajid: Department of Mathematics, Indian Institute of Technology Indore, India (phd2101241003@iiti.ac.in)

Rahul Sharma: Department of Mathematics, Indian Institute of Technology Indore, India (sharmarahul.26dec@gmail.com)

Iman Beheshti: Department of Human Anatomy and Cell Science, Rady Faculty of Health Sciences, Max Rady College of Medicine, University of Manitoba, Winnipeg, MB, Canada & 
Neuroscience Research Program, Kleysen Institute for Advanced Medicine, Health Sciences Centre, Winnipeg, MB R3E 0J9, Canada (beheshtiiman@gmail.com)

M. Tanveer: Department of Mathematics, Indian Institute of Technology Indore, India (mtanveer@iiti.ac.in)

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
## Experimental Software
------------------------
The experimental procedures are executed on a computing system possessing MATLAB R2023a software, Intel(R) Xeon(R) Platinum 8260 CPU @ 2.30GHz, 2301 Mhz, 24 Core(s), 48 Logical Processor(s) with 256 GB RAM on a Windows-10 operating platform.

## Classification Models
------------------------

Randomized Neural Networks (RNNs):
1. Random Vector Functional Link (RVFL) Neural Network
2. Extreme Learning Machine (ELM)
3. Minimum Class Variance Extreme Learning Machine (MCVELM)
4. Minimum Variance Extreme Learning Machine (MVELM)
5. Intuitionistic Fuzzy Random Vector Functional Link (IFRVFL)
6. Total Variance Minimization based Random Vector Functional Link Network (Total-Var-RVFL)
7. Intraclass Variance Minimization based Random Vector Functional Link Network (Class-Var-RVFL)
8. Graph Embedded Extreme Learning Machine
9. Deep Random Vector Functional Link (dRVFL)
10. Ensemble Deep Random Vector Functional Link (edRVFL)
11. Broad Learning System (BLS
12. Neuro Fuzzy Broad Learning System (NF-BLS)

Hyperplane-based Classifiers (HbCs):
1. Support Vector Machine (SVM)
2. Twin Support Vector Machine (TSVM)
3. Intuitionistic Fuzzy Twin Support Vector Machine (IFTSVM)
4. Least Square Support Vector Machine (LSSVM)
5. Least Square Twin Support Vector Machine (LSTSVM)
6. Linex Support Vector Machine (Linex-SVM)
7. Pinball Support Vector Machine (Pin-SVM)
8. Pinball General Twin Support Vector Machine (Pin-GTSVM):

## Datasets
-----------
The Significant Memory Concern (SMC) datasets and their details are available in the dataset repository.

## Running the codes  
--------------------
As a demo of the detailed experimental setup, we have included the code for the RVFL (RNN Model) and pin-GTSVM (HbC) models.
The final results can be inferred from `Model_main.m`, where `Model` refers to the specific model. 

## Hyperparameters
------------------
The hyperparameter settings are reported in Tables 2 and 3 of the paper, and the best hyperparameters are reported in Tables 6 and 10.

## Note
------- 
1. The codes have been cleaned for better readability. For the detailed experimental setup, please follow the paper. 
We have re-run and checked the codes only in a few datasets, so if you find any bugs or issues, please write to M. Sajid (phd2101241003@iiti.ac.in).
2. Some parts of the code have been taken from the original papers of their respective models. If you have any conceptual queries, kindly refer to 
The original paper of the model.

06-Feb-2026

