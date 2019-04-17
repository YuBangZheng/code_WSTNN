# code_WSTNN
matlab code
******************************************************************************
  Tensor N-tubal rank and its convex relaxation for low-rank tensor recovery
******************************************************************************

         Copyright:  Yu-Bang Zheng, Ting-Zhu Huang, Xi-Le Zhao,
                    Tai-Xiang Jiang, Teng-Yu Ji, and Tian-Hui Ma
                    
 Note: since this paper is under review, we have not made the password available online.

 1). Get Started

 Run the following Demo to compare various methods.

     [1] Demo_LRTC
     [2] Demo_TRPCA
  

 2). Details

 More detail can be found in [1]

    [1] Y.-B. Zheng, T.-Z. Huang*, X.-L. Zhao, T.-X. Jiang, T.-Y. Ji, and T.-H. Ma,
        Tensor N-tubal rank and its convex relaxation for low-rank tensor recover.


 The compared low-rank tensor completion methods listed as follows:

     1. HaLRTC    [2]    Tucker decomposition based method
     2. LRTC-TV-I [3]    Tucker decomposition based method
     3. BCPF      [4]    CP decomposition based method     
     4. logDet    [5]    t-SVD based method
     5. TNN       [6]    t-SVD based method
     6. PSTNN     [7]    t-SVD based method
     7. t-TNN     [8]    t-SVD based method
     8. WSTNN     [1]    t-SVD based method


 The compared tensor robust principal component analysis methods listed as follows:

     1. SNN       [9]    Tucker decomposition based method
     2. TNN      [10]    Tucker decomposition based method
     3. WSTNN     [1]    t-SVD based method 


 3). Citations

     [1] Y.-B. Zheng, T.-Z. Huang*, X.-L. Zhao, T.-X. Jiang, T.-Y. Ji, and T.-H. Ma,
         Tensor N-tubal rank and its convex relaxation for low-rank tensor recovery.

     [2] J. Liu, P. Musialski, P. Wonka, and J. Ye,
         Tensor completion for estimating missing values in visual data.

     [3] Q. Zhao, L. Zhang, and A. Cichocki,
         Bayesian CP factorization of incomplete tensors with automatic rank determination.

     [4] X. Li, Y. Ye, and X. Xu,
         Low-rank tensor completion with total variation for visual data inpainting.

     [5] T.-Y. Ji, T.-Z. Huang, X.-L. Zhao, T.-H. Ma, and L.-J. Deng,
         A non-convex tensor rank approximation for tensor completion.

     [6] Z. Zhang, G. Ely, S. Aeron, N. Hao, and M. Kilmer,
         Novel methods for multilinear data completion and de-noising based on tensor-SVD.

     [7] T.-X. Jiang, T.-Z. Huang, X.-L. Zhao, and L.-J. Deng,
         A novel nonconvex approach to recover the low-tubal-rank tensor data: when t-SVD meets PSSV.

     [8] W. Hu, D. Tao, W. Zhang, Y. Xie, and Y. Yang,
         The twist tensor nuclear norm for video completion.

     [9] D. Goldfarb and Z. T. Qin,
         Robust low-rank tensor recovery: Models and algorithms.
        
    [10] C. Lu, J. Feng, Y. Chen, W. Liu, Z. Lin, and S. Yan,
         Tensor robust principal component analysis: Exact recovery of corrupted low-rank tensors via convex optimization.

  4). Acknowledgments

     We would like to express our thanks to Dr. J. Liu, Dr. Q. Zhao, Dr. X. Li, Dr. Z. Zhang, Dr. W. Hu, 
     Dr. D. Goldfarb, and Dr. C. Lu for providing the compared methods.
