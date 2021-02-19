# Code for Tensorized Random Projection
---
Beheshteh T. Rakhshan, Guillaume Rabusseau

Proceedings of the 23rd International Conference on Artificial Intelligence and Statistics (AISTATS) 2020. 

Requirement:
- Install scilit-tensor-py3 [1] and ttpy [2] for using sktensor (CP decomposition) and Tensor Train decomposition tool-boxes, respectively.

About the code: 
- Implementation of our "CP random projection" and "TT random projection" are found in CP_random_projection and TT_random_projection classes.
- Implementation of classical random projections for comparison with our maps are found in Gaussian_random_projection and Sparse_Gaussian_random_projection classes.

Synthetic data generation:
- Generate random high-dimensional vectors in TT/CP decompositions through random_TT_vector and random_CP_vector functions.

To generate 3 plots in Figure 1 in the paper, run:
- Set ORDER_SIZE to "small", "medium" or "high" to switch between the cases.
- Set INPUT_FORMAT to "TT" or "CP" as an input tensor.
- Set the INPUT_TENSOR_RANK, in our experiment is 10. 







