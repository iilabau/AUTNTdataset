# AUTNTdataset

Aliah University Text Non-Text (AUTNT) dataset contains component level multi-script text as well as non-text images. There are three-fold utilities of this dataset: (i) component level image classification, (ii) script identification, and (iii) character recognition. Ground truth data are also prepared and included in respective directory. Component images are chosen from diverse sources and conditions to ensure unconstrained working environment and applicabilty in practical scenario. 

### Dataset Summary
Total number of component images: 10771.
Text component images: 7890.
Non-text component images: 2881.
Dataset is divided into two category based on source images viz. complex documnet level text components and Scene level text components along with non-text components.
Dataset is divided into 5:1 ratio for training and test set. In the training set, 6314 text and 2305 non-text components along with ground truths are present.
In the test set, 1576 text and 576 non-text components along with ground truths are present.

Among all text components of the training set, 3264 components are taken from complex document images and the rest 3050 components are taken from natural indoor/outdoor sources. Dataset contains multi-script text components viz. Latin, Devanagari and Bengali. Components are scale invariant and multi oriented in nature.  Component images are having near-homogenous as well as complex background with uneven illumination effects.

  1.Text Components

        (i) Document type
                  Script:
                        -Latin : Training set- 1258, Test set - 314, total - 1572
                        -Bengali: Training set- 1002, Test set - 251, Total -1253 
                        -Devanagari: Training set - 1004, Test set - 250, Total - 1254  
                        
       (ii) Scene type
                  Script:
                        -Latin : Training set- 1759, Test set - 439, total - 2198
                        -Bengali: Training set- 1011, Test set - 251, Total -1262 
                        -Devanagari: Training set - 280, Test set - 71, Total - 351  
                              
  2. Non-text Components
       
       Scene/Document type:
             Training set - 2305, Test set - 576, Total - 2881



### Relevant Paper(s)
The following paper may be cited while referring to this dataset.
> T. Khan, A. F. Mollah, “AUTNT - A component level dataset for text non-text classification and benchmarking with novel script invariant feature descriptors and D-CNN”, Multimedia Tools and Applications, vol. 78, no. 22, pp. 32159–32186, 2019.


### Benchmark Results on Text Non-Text Classification
**Text (Document-type) Non-Text Classification**
| Method | Precision | Recall | F-Score | Accuracy | RMSE |
| :--- | :---: | :---: | :---: | :---: | :---: |
| Khan et al. [1] | 0.990 | 0.973 |  0.981 | 97.84 | - |

**Text (Scene-type) Non-Text Classification**
| Method | Precision | Recall | F-Score | Accuracy | RMSE |
| :--- | :---: | :---: | :---: | :---: | :---: |
| Khan et al. [1] | 0.981 |  0.931 | 0.955 | 95.14 | - |

**Text (Document and Scene-type Combined) Non-Text Classification**
| Method | Precision | Recall | F-Score | Accuracy | RMSE |
| :--- | :---: | :---: | :---: | :---: | :---: |
| Khan et al. [1] | 0.987 | 0.961 | 0.974 | 96.28 | - |


### Benchmark Results on Script Identification
**Script Identification (Document-type Components)**
| Method | Precision | Recall | F-Score | Accuracy | RMSE |
| :--- | :---: | :---: | :---: | :---: | :---: |
| Khan et al. [2] | 0.9239 | 0.9157 | 0.9170 | 92.02 | - |

**Script Identification (Scene-type Components)**
| Method | Precision | Recall | F-Score | Accuracy | RMSE |
| :--- | :---: | :---: | :---: | :---: | :---: |
| Khan et al. [2] | 0.8139 | 0.7940 | 0.8038 | 89.49 | - |

**Script Identification (Document and Scene-type Combined)**
| Method | Precision | Recall | F-Score | Accuracy | RMSE |
| :--- | :---: | :---: | :---: | :---: | :---: |
| Khan et al. [2] | 0.9149 | 0.9193 | 0.9169 | 92.51 | - |

**References**
1. T. Khan and A. F. Mollah, “AUTNT - A component level dataset for text non-text classification and benchmarking with novel script invariant feature descriptors and D-CNN”, Multimedia Tools and Applications, vol. 78, no. 22, pp. 32159–32186, 2019.
2. T. Khan and A. F. Mollah, “Component level script classification benchmark with CNN on AUTNT dataset”, In: Bhattacharjee D., Kole D.K., Dey N., Basu S., Plewczynski D. (Eds.) Proceedings of International Conference on Frontiers in Computing and Systems, Springer Nature, AISC, vol. 1255, pp. 225-234, Nov 24, 2020, ISBN: 978-981-15-7833-5.

### Contributors
Tauseef Khan, Senuior Research Fellow, Department of Computer Science and Engineering, Aliah University, IIA/27 NewTown, Kolkata 700160, India

Rahamatulla, PGMCA Student, Department of Computer Science and Engineering, Aliah University, IIA/27 NewTown, Kolkata 700160, India

Munsi Md Iftabudin, PGMCA Student, Department of Computer Science and Engineering, Aliah University, IIA/27 NewTown, Kolkata 700160, India.

Mst. Fatema Rahman, B.Tech Student, Department of Computer Science and Engineering, Aliah University, IIA/27 NewTown, Kolkata 700160, India.

Sk. Shamim, PGMCA Student, Department of Computer Science and Engineering, Aliah University, IIA/27 NewTown, Kolkata 700160, India.

Dr. Ayatullah Faruk Mollah, Assistant Professor, Department of Computer Science and Engineering, Aliah University, IIA/27 NewTown, Kolkata 700160, India



### Contact Info
Email: tauseef.hit2013@gmail.com (Tauseef Khan)

Alternate Email: iilab.cse@gmail.com (Lab)
