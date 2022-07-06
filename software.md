---
title: ""
permalink: "/software/"
layout: page
---
 

<!-- [[Github]](https://github.com/Bluefog-Lib/bluefog) -->

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; <img src="https://user-images.githubusercontent.com/65107588/82258821-62d66b80-990f-11ea-9393-bf5456af67e6.png" alt="logo" align="center" width="450"/>

## BlueFog: A Decentralized Framework for Optimization and Deep Learning 

Decentralized optimization algorithms are low-communication-overhead alternatives to traditional distributed algorithms using a center to conduct global average. However, the lack of an easy-to-use and efficient software package has kept most decentralized algorithms merely on paper. BlueFog is the first python library for straightforward, high-performance implementations of diverse decentralized algorithms. 

Performance
-----------

Below are the charts representing the performance of BlueFog that was done on ResNet50 benchmark. Each machine has 8 V100 GPUs (64GB memory) with NVLink-enabled and the inter-connected communication speed is 25Gbps. This is the same hardware setup you can get on AWS clusters. We test the scaling efficiency with a batch size of 64 for a computationally intensive scenario, and a batch size of 32 for a communicationally intensive scenario.

<img src="https://user-images.githubusercontent.com/16711681/98315290-bce5ee80-1f8c-11eb-931f-297a99d958ed.png" alt="Benchmark 1" align="left" width="350"/>
<img src="https://user-images.githubusercontent.com/16711681/98315305-c2433900-1f8c-11eb-91b8-1b17f31dce68.png" alt="Benchmark 2" align="left" width="350"/>

<br><br><br><br><br><br><br><br><br><br><br><br>


In the figures, the black box represents the ideal linear scaling. It is observed that Bluefog can achieve over 95% scaling efficiency while [Horovod](https://github.com/horovod/horovod) reaches around 66% sacling efficiency with batch size 64 on 128 GPUs. For the communicationally intensive scenario with batch size 32, the scaling efficiency gap between Bluefog and Horovod becomes even larger. To 
understand more details about the BlueFog benchmark, checkout the [performance page](https://bluefog-lib.github.io/bluefog/performance.html).

<!-- It is open source at \url{https://github.com/Bluefog-Lib}. BlueFog was invited to give keynote lectures in the US East Coast Optimization Meeting 2021 and China Symposium on Machine Learning 2020.  -->
