---
title: ""
permalink: "/software/"
layout: page
---
 

<!-- [[Github]](https://github.com/Bluefog-Lib/bluefog) -->

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<img src="https://user-images.githubusercontent.com/65107588/82258821-62d66b80-990f-11ea-9393-bf5456af67e6.png" alt="logo" align="center" width="450"/>

## BlueFog: A Decentralized Framework for Optimization and Deep Learning 


Decentralized optimization algorithms are low-communication-overhead alternatives to traditional distributed algorithms using a center to conduct global average. However, the lack of an easy-to-use and efficient software package has kept most decentralized algorithms merely on paper. BlueFog is the first python library for straightforward, high-performance implementations of diverse decentralized algorithms. 

Performance
-----------

Below are the charts representing the performance of BlueFog that was done on ResNet50 benchmark. Each machine has 8 V100 GPUs (64GB memory) with NVLink-enabled and the inter-connected communication speed is 25Gbps. This is the same hardware setup you can get on AWS clusters. We test the scaling efficiency with a batch size of 64 for a computationally intensive scenario, and a batch size of 32 for a communicationally intensive scenario.

<img src="https://user-images.githubusercontent.com/16711681/98315290-bce5ee80-1f8c-11eb-931f-297a99d958ed.png" alt="Benchmark 1" align="left" width="380"/> 
<img src="https://user-images.githubusercontent.com/16711681/98315305-c2433900-1f8c-11eb-91b8-1b17f31dce68.png" alt="Benchmark 2" align="left" width="380"/>

<br><br><br><br><br><br><br><br><br><br>


In the figures, the black box represents the ideal linear scaling. It is observed that Bluefog can achieve over 95% scaling efficiency while [Horovod](https://github.com/horovod/horovod) (a state-of-the-art distributed deep learning training framework built by Uber AI team) reaches around 66% sacling efficiency with batch size 64 on 128 GPUs. For the communicationally intensive scenario with batch size 32, the scaling efficiency gap between Bluefog and Horovod becomes even larger. To 
understand more details about the BlueFog benchmark, checkout the [performance page](https://bluefog-lib.github.io/bluefog/performance.html).

## Code

BlueFog is an open-source library located at [Github](https://github.com/Bluefog-Lib/bluefog). Jupyter notebook tutorials are availabe at [here](https://github.com/Bluefog-Lib/bluefog-tutorial).

## Papers

The implemented algorithms and system design in BlueFog can be found in the following papers:

- [Bluefog: Make decentralized algorithms practical for optimization and deep learning](https://arxiv.org/abs/2111.04287) <br>
  B. Ying, K. Yuan, H. Hu, Y. Chen, and W. Yin 
  
- [Communicate then adapt: An effective decentralized adaptive method for deep training](https://openreview.net/forum?id=m716e-0clj&referrer=%5Bthe%20profile%20of%20Wotao%20Yin%5D(%2Fprofile%3Fid%3D~Wotao_Yin1)) <br>
  B. Ying<sup>E</sup>, K. Yuan<sup>E</sup>, Y. Chen<sup>E</sup>, H. Hu<sup>E</sup>, Y. Zhang, P. Pan, and W. Yin
  
- [Exponential graph is provably efficient for decentralized deep training](https://arxiv.org/abs/2110.13363) <br>
  B. Ying<sup>E</sup>, K. Yuan<sup>E</sup>, Y. Chen<sup>E</sup>, H. Hu, P. Pan, and W. Yin &emsp; *NeurIPS 2021*
  
- [DecentLaM: Decentralized momentum SGD for large-batch deep training](https://openaccess.thecvf.com/content/ICCV2021/papers/Yuan_DecentLaM_Decentralized_Momentum_SGD_for_Large-Batch_Deep_Training_ICCV_2021_paper.pdf) <br>
  K. Yuan<sup>EC</sup>, Y. Chen<sup>E</sup>, X. Huang<sup>E</sup>, Y. Zhang, P. Pan, Y. Xu, and W. Yin  &emsp; *ICCV 2021*
  
- [On the influence of bias-correction on distributed stochastic optimization](https://ieeexplore.ieee.org/abstract/document/9139399)  <br>
  K. Yuan, S. A. Alghunaim, B. Ying, and A. H. Sayed &emsp; *IEEE Transactions on Signal Processing*
  
## Talks

- [Faster Learning over Networks and BlueFog](http://www.lamda.nju.edu.cn/conf/mla20/slides/YinWoTao.pdf) <br> 
  BlueFog Team, *China Symposium on Machine Learning and Applications (MLA)*, 2020
  
- [Parallel, Distributed, and Decentralized optimization methods](https://math.gmu.edu/~hantil/ECOM/2021/schedule.html) <br>
   Wotao Yin, *East Coast Optimization Meeting (ECOM)*, 2021 
   
- [Distributed Stochastic Optimization](https://www.bilibili.com/video/BV1mQ4y1Y7Pe) <br>
   Kun Yuan, *ZJU-CSE Summer School*, 2021 

<!-- It is open source at \url{https://github.com/Bluefog-Lib}. BlueFog was invited to give keynote lectures in the US East Coast Optimization Meeting 2021 and China Symposium on Machine Learning 2020.  -->
