Robust multi-label feature selection with shared label enhancement (2022)

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
