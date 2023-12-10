---
title: ""
permalink: "/teaching/"
layout: page
---

## PKU Class 2023 Fall: Optimizaiton for Deep Learning

Instructor: **Kun Yuan** (kunyuan@pku.edu.cn) <br>

Teaching assistants: 
- **Yutong He** (yutonghe@pku.edu.cn) <br>
- **Jinghua Huang** (jinghua@stu.pku.edu.cn) <br>
- **Pengfei Wu** (pengfeiwu1999@stu.pku.edu.cn) <br> 
- **Hao Yuan** (pkuyuanhao@pku.edu.cn) <br>

Office hour: 2pm - 3pm Thursday, 静园六院220

## References
Martin Jaggi and Nicolas Flammarion, *[Optimization for Machine Learning](https://github.com/epfml/OptML_course)*, EPFL Class CS-439 <br>
Chris De Sa, *[Advanced Machine Learning Systems](https://www.cs.cornell.edu/courses/cs6787/2021fa/)*, Cornell CS6787

## Projects

[[Projects_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/DLOPT_projects.pdf) [[Projects_BD]](https://pan.baidu.com/s/1oLsf-GGrEgO1j8A1iLriJA?pwd=vru7) <br>

<mark> Presentation materials are due by 11:59 AM on December 26, 2023. </mark> 

<mark> Project codes and reports are due by 11:59 PM on January 14, 2023. </mark> 

## Materials

**Remark**: All materials can be retrieved from two sources: GitHub and Baidu Wangpan. <br>

### Lecture 1: Introduction <br>
- Warm up: Preliminary [[Notes_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/notes_ch0.pdf) [[Notes_BD]](https://pan.baidu.com/s/1CRjewPuz9m11FzzG0AIU3g?pwd=35ic) <br>
- Part   I: Overview on fundamental algorithms for optimization [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec1_introduction_01.pdf) [[Slides_BD]](https://pan.baidu.com/s/1mqNOB_8094OETo7nsI3QCw?pwd=jbu6)  <br> 
- Part  II: Overview on fundamental algorithms for training deep neural network [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec1_introduction_02.pdf)  [[Slides_BD]](https://pan.baidu.com/s/1N8yWWyx2z6NhKGiqg5fVZQ?pwd=pzw9) <br> 
- Part III: Overview on advanced algorithms for training deep neural network [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec1_introduction_03.pdf) [[Slides_BD]](https://pan.baidu.com/s/140bkncOmR7CHoodw7zBAcQ?pwd=b8ei) <br> 
- Part  IV: Overview on distributed algorithms for training deep neural network [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec1_introduction_04.pdf) [[Slides_BD]](https://pan.baidu.com/s/1okoQ-xbnrjY_ej97IDHFOQ?pwd=tt9m)<br>
- **Homework 1**: Review the preliminary notes.  

### Lecture 2: Gradient descent <br>

- Notes: Gradient descent [[Notes_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/notes_ch1.pdf) [[Notes_BD]](https://pan.baidu.com/s/1FlAAZwhMAkoScx4LDURrPg?pwd=sbwk) <br>
- Slides: Gradient descent [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec2_gradient_descent.pdf) [[Slides_BD]](https://pan.baidu.com/s/1QgNjBzOeqJFq5QFVFLBIgw?pwd=ec6j)  <br>
- **Homework 2**: [[Homework_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/hw1.pdf) [[Homework_BD]](https://pan.baidu.com/s/1nEhmFrNYgvQssAY_jsBzXQ?pwd=4h9y)  <br> 
- Reading: <br>
    - Stephen Boyd and Lieven Vandenberghe, *Convex Optimization*, Cambridge university press, 2004. [Ch. 2 and 3] <br>
    - Yurii Nesterov, *Introductory lectures on convex optimization: A basic course*, Springer Science & Business Media, 2003 [Sec. 2.1.1, 2.1.3, and 2.1.5] <br>
    - Aston Zhang, Zack C. Lipton, Mu Li, and Alex J. Smola, *[Dive into Deep Learning](https://d2l.ai/index.html)*, [Sec. 5.3]

### Lecture 3: Accelerated gradient descent <br>

- Notes: Accelerated gradient descent [[Notes_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/notes_ch3.pdf)[[Notes_BD]](https://pan.baidu.com/s/1hxAKGKpiaRTGyKCRymrU5A?pwd=nery) <br>
- Part  I: Polyak momentum; Nesterov momentum; Anderson acceleration; Lower bound [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec3_1_acc_GD.pdf) [[Slides_BD]](https://pan.baidu.com/s/1sefTbKt7AEMZmEfNRNvMXA?pwd=gc27)  <br>
- Part II: Preconditoned GD [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec3_2_precond_GD.pdf) [[Slides_BD]](https://pan.baidu.com/s/1ackF2-iU2yFiP-ixhXa6wg?pwd=nc77)  <br>
- **Homework 3**: [[Homework_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/hw3.pdf) [[Homework_BD]](https://pan.baidu.com/s/1tqYdqBcTfdgKAWuPJMYDPQ?pwd=7ds9)  <br> 
- Reading: <br>
    - Yurii Nesterov, *Introductory lectures on convex optimization: A basic course*, Springer Science & Business Media, 2003 [Sec. 2.1.2, 2.1.4, and 2.2] <br>
    - Vien V. Mai and Mikael Johansson, *[Anderson Acceleration of Proximal Gradient Methods](https://arxiv.org/abs/1910.08590)*, International Conference on Machine Learning (ICML), 2020

### Lecture 4: Projected gradient descent and Proximal gradient descent <br>

- Notes: Projected gradient descent [[Notes_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/notes_ch4_1.pdf)[[Notes_BD]](https://pan.baidu.com/s/1z5pxGqRZLlfnCq6LbM2PPg?pwd=ut8r); Proximal gradient descent [[Notes_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/notes_ch4_2.pdf)[[Notes_BD]](https://pan.baidu.com/s/1AlgaCL9IBnQroGWO4TFInw?pwd=wkn3) <br>
- Part  I: Projection; Constrained minimization; Projected gradient descent [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec4_1_Projected_GD.pdf) [[Slides_BD]](https://pan.baidu.com/s/1_z-KtyxBjP_5H05fneNKqw?pwd=9p7u)  <br>
- Part II: Regularizers; Proximity operator; Proximal gradient descent [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec4_2_Prox_GD.pdf) [[Slides_BD]](https://pan.baidu.com/s/14YWUlhm9ZhDMdUWQ9Cbl9g?pwd=k9pd)  <br>
- **Homework 4**: [[Homework_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/hw4.pdf) [[Homework_BD]](https://pan.baidu.com/s/1qtKFoyB-qvZzBAhJxprP7w?pwd=b6r9)  <br>

### Lecture 5: Zeroth-order optimization <br>

- Notes: Zeroth-order optimization [[Notes_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/notes_ch5.pdf)[[Notes_BD]](https://pan.baidu.com/s/1HmcdYHP_VuYsojv_dJuWXw?pwd=c59t)
- Notes: ZO-GD with sphere smoothing [[Notes_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/notes_ch5_1.pdf)[[Notes_BD]](https://pan.baidu.com/s/1eS5hkqeDHW3otQ2HLHHsUA?pwd=g1rf)
- Slides: Zeroth-order gradient descent; Finite difference; Linear interpolation; Sphere smoothing [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec5_ZO_GD.pdf) [[Slides_BD]](https://pan.baidu.com/s/14ZaQoEpS7ou9laIK9vg_qA?pwd=yk3b)  <br>
- **Homework 5**: [[Homework_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/hw5.pdf) [[Homework_BD]](https://pan.baidu.com/s/19I-EpqvqtQpqxiUJD_bWCQ?pwd=nqwu)  <br>
- Reading: <br>
    - Yujie Tang, *[Introduction to Zeroth-Order Optimization](https://tyj518.github.io/files/lecture_notes_zo.pdf)*, 2022
    - Ahmad Ajalloeian and Sebastian U. Stich, *[On the Convergence of SGD with Biased Gradients](https://arxiv.org/abs/2008.00051)*, 2021
    - Sijia Liu et. al., *[A Primer on Zeroth-Order Optimization in Signal Processing and Machine Learning](https://arxiv.org/abs/2006.06224)*, 2020
    - Sadhika Malladi et. al., *[Fine-Tuning Language Models with Just Forward Passes](https://arxiv.org/abs/2305.17333)*,2023

### Lecture 6: Stochastic gradient descent <br>

- Notes: Stochastic gradient descent [[Notes_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/notes_ch6.pdf)[[Notes_BD]](https://pan.baidu.com/s/1PVrSZAMJhOnkpUbqnXYhPA?pwd=ubss)
- Part I: Stochastic optimization; Stochastic gradient descent; Mini-batch SGD [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec6_1_SGD.pdf) [[Slides_BD]](https://pan.baidu.com/s/1Xvc0ov5IvdVNsOffPX1m6Q?pwd=ivpm)  <br>
- Part II: Introduction to convolutional neural network [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec6_2_CNN.pdf) [[Slides_BD]](https://pan.baidu.com/s/1d_ouKEHfLyBuM9kGcgynIQ?pwd=ccd2)  <br>
- **Homework 6**: [[Homework_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/hw6.pdf) [[Homework_BD]](https://pan.baidu.com/s/1y7gSopjEB4c1_vB7vd5FLg?pwd=zn2z)  <br>
- Reading: <br>
    - Rong Ge et al., *[Escaping from saddle points—online stochastic gradient for tensor decomposition](http://proceedings.mlr.press/v40/Ge15.pdf)*, Conference on learning theory, 2015
    - Chi Jin et al., *[How to escape saddle points efficiently](https://proceedings.mlr.press/v70/jin17a.html)*, International conference on machine learning, 2017.
    - *[Student Notes: Convolutional Neural Networks (CNN) Introduction](https://indoml.com/2018/03/07/student-notes-convolutional-neural-networks-cnn-introduction/)*
    - Andrew Ng, *[Convolutional Neural Networks](https://www.bilibili.com/video/BV1BF411w7xQ/?spm_id_from=333.337.search-card.all.click)*
 
### Lecture 7: Stochastic gradient descent: sampling strategy and stability <br>

- Notes: Sampling and Stability [[Notes_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/notes_ch7.pdf)[[Notes_BD]](https://pan.baidu.com/s/1WUkqEOV4pOIQoruFn2MjCw?pwd=8rku)
- Part I: SGD with finite sample size; importance sampling; random reshuffling [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec7_1_sampling.pdf)  [[Slides_BD]](https://pan.baidu.com/s/1IxV1awpa-BYnMT_ww1r8uQ?pwd=a9ni) <br>
- Part II: GD stability; SGD stability; Sharpness-aware minimization [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec7_2_stability.pdf)  [[Slides_BD]](https://pan.baidu.com/s/1HYncozXFxVeGLGKkSShvhw?pwd=6at9)<br>
- **Homework 7**: [[Homework_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/hw7.pdf) [[Homework_BD]](https://pan.baidu.com/s/18lj6tEy2Ps7m_gsFnJrOMg?pwd=2huk)  <br>
- Reading: <br>
    - Kun Yuan et al., *[Stochastic gradient descent with finite samples sizes](https://ieeexplore.ieee.org/document/7738878)*, IEEE Workshop on Machine Learning for Signal Processing, 2016
    - Peilin Zhao and Tong Zhang, *[Stochastic Optimization with Importance Sampling for Regularized Loss Minimization](https://proceedings.mlr.press/v37/zhaoa15.html)*, ICML, 2015.
    - Bicheng Ying et al., *[Stochastic Learning under Random Reshuffling with Constant Step-sizes](https://arxiv.org/abs/1803.07964)*, IEEE Transactions on Signal Processing, 2018
    - Lei Wu et al., *[How SGD selects the global minima in over-parameterized learning: A dynamical stability perspective](https://papers.nips.cc/paper_files/paper/2018/hash/6651526b6fb8f29a00507de6a49ce30f-Abstract.html)*, NeurIPS 2018
    - Lei Wu et al., *[The alignment property of sgd noise and how it helps select flat minima: A stability analysis](https://arxiv.org/abs/2207.02628)*, NeurIPS 2022
    - Pierre Foret et al., *[Sharpness-Aware Minimization for Efficiently Improving Generalization](https://arxiv.org/abs/2010.01412)*, ICML, 2020

### Lecture 8: Momentum and Adaptive SGD <br>

- Notes I: Momentum SGD [[Notes_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/notes_ch8_1.pdf)[[Notes_BD]](https://pan.baidu.com/s/1EEV-n-UoDN_0PVSsBvUOSg?pwd=gaxf) <br>
- Notes II: Adaptive SGD [[Notes_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/notes_ch8_2.pdf)[[Notes_BD]](https://pan.baidu.com/s/1eFHbWuFRaaibWJ9wNOly_g?pwd=799k) <br>
- Part I: Momentum SGD; SGD with Nesterov momentum; lower bound in stochastic optimization [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec8_1_mSGD.pdf)  [[Slides_BD]](https://pan.baidu.com/s/1FJVoDRMLU6iZa76Bf87e0g?pwd=feex) <br>
- Part II: Preconditioned SGD; AdaGrad; RMSProp; Adam; AdamW [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec8_2_Adaptive_SGD.pdf)  [[Slides_BD]](https://pan.baidu.com/s/1DRdv77mSLZTN-ifFn5GuGA?pwd=cvke)<br>
- **Homework**: No homework  <br>
- Reading: <br>
   - Ilya Sutskever et al., *[On the importance of initialization and momentum in deep learning](http://proceedings.mlr.press/v28/sutskever13.html)*, ICML, 2013
   - Kun Yuan et al., *[On the influence of momentum acceleration on online learning](https://jmlr.org/papers/v17/16-157.html)*, JMLR, 2016
   - John Duchi et al., *[Adaptive subgradient methods for online learning and stochastic optimization](https://www.jmlr.org/papers/volume12/duchi11a/duchi11a.pdf)*, JMLR, 2011
   - Diederik P. Kingma et al., *[Adam: A Method for Stochastic Optimization](https://arxiv.org/abs/1412.6980)*, 2014
   - Zhishuai Guo et al., *[A novel convergence analysis for algorithms of the adam family](https://arxiv.org/abs/2112.03459)*, 2021
   - Ilya Loshchilov et al., *[Decoupled Weight Decay Regularization](https://openreview.net/forum?id=Bkg6RiCqY7)*, ICLR, 2019

### Lecture 9: Variance reduction <br>

- Notes I: Variance reduction[[Notes_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/notes_ch9.pdf)[[Notes_BD]](https://pan.baidu.com/s/1EEV-n-UoDN_0PVSsBvUOSg?pwd=gaxf) <br>
- Part I: SAGA; SVRG [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec9_1_VR.pdf)  [[Slides_BD]](https://pan.baidu.com/s/1XZ33pflapuqZS5LrplcRzA?pwd=jr5i) <br>
- Part II: Recurrent Neural Network [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec9_2_RNN.pdf)  [[Slides_BD]](https://pan.baidu.com/s/1TNGnpDqF3SwlHE1ccb4T-w?pwd=exdw)<br>
- Part III: Attention [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec9_3_attention.pdf)  [[Slides_BD]](https://pan.baidu.com/s/1ZfNHKd710sDqcI8OArsUBg?pwd=gs3q)<br>
- **Homework**: No homework  <br>
- Reading: <br>
   - Rie Johnson et al., *[Accelerating stochastic gradient descent using predictive variance reduction](https://proceedings.neurips.cc/paper_files/paper/2013/file/ac1dd209cbcc5e5d1c6e28598e8cbbe8-Paper.pdf)*, NeurIPS 2013
   - Aaron Defazio et al., *[SAGA: A Fast Incremental Gradient Method With Support for Non-Strongly Convex Composite Objectives](https://proceedings.neurips.cc/paper_files/paper/2014/hash/ede7e2b6d13a41ddf9f4bdef84fdc737-Abstract.html)*, NeurIPS 2014
   - [Introduction to recurrent neural network](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-recurrent-neural-networks)
   - [Dive into deep learning: RNN](https://d2l.ai/chapter_recurrent-neural-networks/index.html)
   - [Dive into deep learning: Attention](https://d2l.ai/chapter_attention-mechanisms-and-transformers/index.html)

### Lecture 10-1: Adversarial learning <br>
- Adversarial attacks; FGSM; PGD; Adversarial learning [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec10_1_adversarial_learning.pdf)  [[Slides_BD]](https://pan.baidu.com/s/14dUPmJnW1Ckg83djgTffog?pwd=4jm1) <br>
- Reading: <br>
   - Ian J. Goodfellow et al., *[Explaining and harnessing adversarial examples](https://arxiv.org/abs/1412.6572)*, 2014.
   - Aleksander Madry et al., *[Towards Deep Learning Models Resistant to Adversarial Attacks](https://openreview.net/pdf?id=rJzIBfZAb)*, ICLR 2018.
   - Ali Shafahi et al., *[Adversarial training for free!](https://proceedings.neurips.cc/paper_files/paper/2019/hash/7503cfacd12053d309b6bed5c89de212-Abstract.html)*, NeurIPS 2019.
   - Eric Wong et al., *[Fast is better than free: Revisiting adversarial training](https://arxiv.org/abs/2001.03994)*, ICLR 2019.

### Lecture 10-2: Gradient clipping <br>
- Gradient exploding; Gradient clipping; L0-L1 smoothness [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec10_2_Grad_clip.pdf)  [[Slides_BD]](https://pan.baidu.com/s/1P61f-jlDLVABGaNjdqy_rw?pwd=8pff) <br>
- **Homework 8**: [[Homework_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/hw8.pdf) [[Homework_BD]](https://pan.baidu.com/s/1b31wjwbZDXBCqX0v4I2UVw?pwd=4vfh)  <br>
- Reading: <br>
   - Jingzhao Zhang et al., *[Why gradient clipping accelerates training: A theoretical justification for adaptivity](https://arxiv.org/abs/1905.11881)*, ICLR 2019.
   - Bohang Zhang et al., *[Improved analysis of clipping algorithms for non-convex optimization](https://proceedings.neurips.cc/paper_files/paper/2020/hash/b282d1735283e8eea45bce393cefe265-Abstract.html)*, NeurIPS 2020.
   - Anastasia Koloskova et al., *[Revisiting Gradient Clipping: Stochastic bias and tight convergence guarantees](https://arxiv.org/abs/2305.01588)*, ICML 2023.


### Lecture 11: Mixed-Precision Training <br>
- FP32; FP16; Mixed-precision training; 8 bit Adam optimizer; SGD with mixed precision [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec11_mixed_precision.pdf)[[Slides_BD]](https://pan.baidu.com/s/1y7M1Wi4EeFcBNW3w_wJiFA?pwd=yh5x) <br>
- Transformer [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Transformer.pdf)[[Slides_BD]](https://pan.baidu.com/s/1nBquf_qLoVjgUkQ0_bcQVw?pwd=wdsi) <br>
- **Homework 9**: [[Homework_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/hw9.pdf) [[Homework_BD]](https://pan.baidu.com/s/1c6NVvqO83JHmyNDQ7hkW5w?pwd=9djs)  <br>
- Reading: <br>
   - Paulius Micikevicius et al., *[Mixed Precision Training](https://arxiv.org/abs/1710.03740)*, ICLR 2018.
   - Tim Dettmers et al., *[8-bit Optimizers via Block-wise Quantization](https://arxiv.org/abs/2110.02861)*, ICLR 2022.
   - Dan Alistarh et.al., *[QSGD: Communication-Efficient SGD via Gradient Quantization and Encoding](https://arxiv.org/abs/1610.02132)*, NeurIPS 2017.
   - *[Transformer模型详解](https://zhuanlan.zhihu.com/p/338817680)*.

### Lecture 12: Meta Learning <br>
- Part I: Introduction to Meta Learning (We will use the great [Slides](https://speech.ee.ntu.edu.tw/~hylee/ml/ml2021-course-data/meta_v3.pdf) from Prof. Hung-Yi Lee) <br>
- Part II: Learning to Initilize; MAML; Reptile [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec12_1_MAML.pdf)[[Slides_BD]](https://pan.baidu.com/s/1oJ50zAMo4bK5Q7GFkcckCw?pwd=r76z) <br>
- Part III: Learning to Optimize [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec12_2_learning_to_learn.pdf)[[Slides_BD]](https://pan.baidu.com/s/1Z6NWa2mFUKeZhaK-Y8B9sQ?pwd=npft) <br>
