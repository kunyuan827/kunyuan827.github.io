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
- **Homework 3**: To be announced <br>
- Reading: <br>
    - Yurii Nesterov, *Introductory lectures on convex optimization: A basic course*, Springer Science & Business Media, 2003 [Sec. 2.1.2, 2.1.4, and 2.2] <br>
    - Vien V. Mai and Mikael Johansson, *[Anderson Acceleration of Proximal Gradient Methods](https://arxiv.org/abs/1910.08590)*, International Conference on Machine Learning (ICML), 2020
