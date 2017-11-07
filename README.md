# Saliency-Detection-via-Absorbing-Markov-Chain-with-Learnt-Transition-Probability
Saliency Detection via Absorbing Markov Chain with Learnt Transition Probability (Include Code and Maps)


The code is for paper "Saliency Detection via Absorbing Markov Chain with Learnt Transition Probability" by Lihe Zhang, Jianwu Ai, Bowen Jiang, Huchuan Lu and Xiukui Li.
To appear in IEEE TRANSACTIONS ON IMAGE PROCESSING 2017 
written by Jianwu Ai. Email: aijianwu@mail.dlut.edu.cn


If you use this code please cite our TIP2017 and ICCV2013 paper:

@article{zhanglh_2017_TIP>
author = {Lihe Zhang and Jianwu Ai and Bowen Jiang and Huchuan Lu and Xiukui Li}
title = {Saliency Detection via Absorbing Markov Chain with Learnt Transition Probability}
journal= {IEEE Trans. Image Process.}
volume={},
number={},
pages={},
year = {},
}

@InProceedings{Jiangbw_ICCV13,  
title={Saliency Detection via Absorbing Markov Chain},  
author={B.W. Jiang and L.H. Zhang and H.C. Lu and C. Yang and M.-H. Yang},  
booktitle={Proc. IEEE Int. Conf. Comput. Vis.},  
pages={1665--1672},  
year={2013},
}


------------------------------------------------------------------------
The code is tested on Windows 7 with MATLAB R2014a.
------------------------------------------------------------------------

Installation:
>compile Normalized Cuts code in the directory 'Ncuts_9/'


Usage:
>put test images into the directory '\image'
>put their boundary maps into the directory '\boundary-map'
>put their deep features into the directory '\FCN-feature'
>run 'Saliency_AMC_AE.m'


Note:
1.Boundary maps are generated by [1].
2.Deep features are generated by the pre-trained FCN-32S network [2]. We use the features of layer6 and layer32 in this work.


[1]C. L. Zitnick and P. Dollár, Edge boxes: Locating object proposals from edges, in ECCV, 2014.
[2]J. Long, E. Shelhamer, and T. Darrell, Fully convolutional networks for semantic segmentation, in CVPR, 2015.

--------------------------------------------------------------------------------------------------------------------------------
Source code and saliency maps for the MSRA, ECSSD, PASCAL, HKU-IS, SOD and SED datasets can also be downloaded from https://www.researchgate.net/ or https://github.com/.
--------------------------------------------------------------------------------------------------------------------------------

Note: The running time reported in our paper does not include the time of the computational cost of extracting deep features. 

If you have any problem, please contact zhanglihe@dlut.edu.cn.






