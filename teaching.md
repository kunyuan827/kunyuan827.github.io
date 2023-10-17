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
- Slides: Zeroth-order gradient descent; Finite difference; Linear interpolation; Sphere smoothing [[Slides_GH]](https://github.com/kunyuan827/kunyuan827.github.io/raw/master/resources/Lec5_ZO_GD.pdf) [[Slides_BD]](https://pan.baidu.com/s/14ZaQoEpS7ou9laIK9vg_qA?pwd=yk3b)  <br>
- Reading: <br>
    - Yujie Tang, *[Introduction to Zeroth-Order Optimization](https://tyj518.github.io/files/lecture_notes_zo.pdf)*, 2022
    - Ahmad Ajalloeian and Sebastian U. Stich, *[On the Convergence of SGD with Biased Gradients](https://arxiv.org/abs/2008.00051)*, 2021
    - Sijia Liu et. al., *[A Primer on Zeroth-Order Optimization in Signal Processing and Machine Learning](https://arxiv.org/abs/2006.06224)*, 2020
    - Sadhika Malladi et. al., *[Fine-Tuning Language Models with Just Forward Passes](https://arxiv.org/abs/2305.17333)*,2023
