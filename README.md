[Robust multi-label feature selection with shared label enhancement (2022)](https://link.springer.com/article/10.1007/s10115-022-01747-9)

Authors = Yonghao Li, Juncheng Hu, and Wanfu Gao,

Journal = Knowledge and Information Systems.

Abstract
Feature selection has attracted considerable attention due to the wide application of multilabel learning. However, previous methods do not fully consider the relationship between
feature sets and label sets but devote attention to either of them. Furthermore, conventional
multi-label learning utilizes logical labels to estimate relevance between feature sets and
label sets so that the importance of corresponding labels cannot be well reflected. Additionally, numerous irrelevant and redundant labels degrade the classification performance of
models. To this end, we propose a multi-label feature selection method named Robust multilabel Feature Selection with shared Label Enhanced (RLEFS). First, we obtain a robust
label enhancement term by reconstructing labels from logical labels to numerical labels and
imposing l2,1-norm onto the label enhancement term. Second, RLEFS utilizes the robust
label enhancement term to share the similar latent semantic structure between feature matrix
and label matrix. Third, local structure is considered to ensure the consistency of label information during the feature selection process. Finally, we integrate the above terms into one
joint learning framework, and then, a simple but effective optimization method with provable
convergence is proposed to solve RLEFS. Experimental results demonstrate the classification
superiority of RLEFS in comparison with seven state-of-the-art methods.

If you find this implementation helpful in your work, please consider citing both the original paper and our related research on multi-label feature selection:

## Original Paper:

```
@article{li2022robust,
  title={Robust multi-label feature selection with shared label enhancement},
  author={Li, Yonghao and Hu, Juncheng and Gao, Wanfu},
  journal={Knowledge and Information Systems},
  volume={64},
  number={12},
  pages={3343--3372},
  year={2022},
  publisher={Springer}
}
```
## Our Paper:
```
@article{faraji2024multi,
  title={Multi-label feature selection with global and local label correlation},
  author={Faraji, Mohammad and Seyedi, Seyed Amjad and Tab, Fardin Akhlaghian and Mahmoodi, Reza},
  journal={Expert Systems with Applications},
  volume={246},
  pages={123198},
  year={2024},
  publisher={Elsevier}
}
```
