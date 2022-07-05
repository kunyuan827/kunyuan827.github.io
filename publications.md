---
title: ""
permalink: "/publications/"
layout: page
---

The supscript <sup>E</sup> indicates **Equal contribution**, while supscript <sup>C</sup> indicates **Corresponding author**.

### Preprints

- [Heavy-Tail phenomenon in decentralized SGD](https://arxiv.org/abs/2205.06689) <br>
  M. Gurbuzbalaban, Y. Hu, U. Simsekli, K. Yuan, and L. Zhu &emsp; (Authors are listed alphabetically)

- [Bluefog: Make decentralized algorithms practical for optimization and deep learning](https://arxiv.org/abs/2111.04287) <br>
  B. Ying, K. Yuan, H. Hu, Y. Chen, and W. Yin 
  
- [Removing data heterogeneity influence enhances network topology dependence of decentralized SGD](https://arxiv.org/abs/2105.08023) <br>
  K. Yuan, S. A. Alghunaim, and X. Huang 
  
- [Communicate then adapt: An effective decentralized adaptive method for deep training](https://openreview.net/forum?id=m716e-0clj&referrer=%5Bthe%20profile%20of%20Wotao%20Yin%5D(%2Fprofile%3Fid%3D~Wotao_Yin1)) <br>
  B. Ying<sup>E</sup>, K. Yuan<sup>E</sup>, Y. Chen<sup>E</sup>, H. Hu<sup>E</sup>, Y. Zhang, P. Pan, and W. Yin
  
- [Decentralized composite optimization with compression](https://arxiv.org/abs/2108.04448) <br>
  Y. Li, X. Liu, J. Tang, M. Yan, and K. Yuan &emsp; (Authors are listed alphabetically)
  
- [ODE analysis of stochastic gradient methods with optimism and anchoring for minimax problems](https://arxiv.org/abs/1905.10899) <br>
  E. Ryu, K. Yuan, and W. Yin


### 2022 

- [A unified and refined convergence analysis for non-convex decentralized learning](https://arxiv.org/abs/2110.09993) <br>
  S. A. Alghunaim and K. Yuan &emsp; *IEEE Transactions on Signal Processing*
  
- [A Byzantine-resilient dual subgradient method for vertical federated learning](https://ieeexplore.ieee.org/abstract/document/9747270/) <br>
  K. Yuan, Z. Wu, and Q. Ling &emsp; *ICASSP 2022*
  
- [CHEX: Channel exploration for CNN model compression](https://openaccess.thecvf.com/content/CVPR2022/papers/Hou_CHEX_CHannel_EXploration_for_CNN_Model_Compression_CVPR_2022_paper.pdf) <br>
  Z. Hou, M. Qin, F. Sun, X. Ma, K. Yuan, Y. Xu, Y.-K. Chen, R. Jin, Y. Xie, and S.-Y. Kung &emsp; *CVPR 2022*
  
- [Effective model sparsification by scheduled Grow-and-Prune methods](https://openaccess.thecvf.com/content/CVPR2022/papers/Hou_CHEX_CHannel_EXploration_for_CNN_Model_Compression_CVPR_2022_paper.pdf) <br>
  X. Ma, M. Qin, F. Sun, Z. Hou, K. Yuan, Y. Xu, Y. Wang, Y.-K. Chen, R. Jin, and Y. Xie &emsp; *ICLR 2022*

### 2021

- [Exponential graph is provably efficient for decentralized deep training](https://arxiv.org/abs/2110.13363) <br>
  B. Ying<sup>E</sup>, K. Yuan<sup>E</sup>, Y. Chen<sup>E</sup>, H. Hu, P. Pan, and W. Yin &emsp; *NeurIPS 2021*
  
- [Improved analysis and rates for variance reduction under without-replacement sampling orders](https://proceedings.neurips.cc/paper/2021/file/1a3650aedfdd3a21444047ed2d89458f-Paper.pdf) <br>
  X. Huang<sup>E</sup>, K. Yuan<sup>EC</sup>, X. Mao, and W. Yin &emsp; *NeurIPS 2021*

- [DecentLaM: Decentralized momentum SGD for large-batch deep training](https://openaccess.thecvf.com/content/ICCV2021/papers/Yuan_DecentLaM_Decentralized_Momentum_SGD_for_Large-Batch_Deep_Training_ICCV_2021_paper.pdf) <br>
  K. Yuan<sup>EC</sup>, Y. Chen<sup>E</sup>, X. Huang<sup>E</sup>, Y. Zhang, P. Pan, Y. Xu, and W. Yin  &emsp; *ICCV 2021*
  
- [Accelerating gossip SGD with periodic global averaging](http://proceedings.mlr.press/v139/chen21y/chen21y.pdf) <br>
  Y. Chen<sup>E</sup>, K. Yuan<sup>EC</sup>, Y. Zhang, P. Pan, Y. Xu, and W. Yin &emsp; *ICML 2021*

<!-- ## Features

 - supports dark mode on macOS Mojave
 - optional sidebar
 - MathJax support
 - no external ressources
 - included archive page
 - supports pagination
 - feed generation
 - responsive
 - syntax highlighting
 - supports comments via [disqus](https://disqus.com/) or [isso](http://posativ.org/isso/)

## Based on

- [Hyde](https://github.com/poole/hyde)
- [Minima](https://github.com/jekyll/minima)
- [Lagrange](https://github.com/LeNPaul/Lagrange)
- [Font Awesome](http://fontawesome.io/)
- [KaTeX](https://katex.org/)
- [Pygments](https://github.com/richleland/pygments-css)

## Installation (jekyll-remote-theme method)

You can use this theme with the `jekyll-remote-theme` plugin. Just create an empty repo, copy over the `index.html` file and add this to your `_config.yml`:

```yaml
remote_theme: niklasbuschmann/contrast@v2.11

plugins:
  - jekyll-remote-theme
```

Note: to enable icons you also need to copy over the `_data` folder.

## Config

Your `_config.yml` could for example look like this:

```yaml
title: "Blog Title"
author: "Blog Author"
description: "My personal blog about ... something"
permalink: /:title/
lang: "en"
excerpt_separator: "\n\n\n"
date_format: "%B %d, %Y"

# Layout

show_excerpts: true        # show article excerpts on the home page
show_frame: true           # adds a gray frame to the site
show_sidebar: false        # show a sidebar instead of the usual header

# Menu

navigation:                # accepts {file, title, url, icon, sidebaricon}
  - {file: "index.html"}
  - {file: "README.md"}

external:                  # shows a footer with social links - for available icons see fontawesome.com/icons
  - {title: Mail, icon: envelope, url: "mailto:niklasbuschmann@users.noreply.github.com"}
  - {title: Github, icon: github, url: "https://github.com/niklasbuschmann/contrast"}
  - {title: Subscribe, icon: rss, url: "/feed.xml"}

comments:
#  disqus_shortname: ""    # see https://disqus.com/
#  isso_domain: ""         # see https://posativ.org/isso/

plugins:
 - jekyll-feed

```

## MathJax

Contrast comes preinstalled with a leightweight alternative to MathJax called [KaTeX](https://katex.org/). To display equations in a post simply set `mathjax: true` in the article's front matter.

## License

[public domain](http://unlicense.org/)

## Screenshots

![screenshot](https://user-images.githubusercontent.com/4943215/109431850-cd711780-7a08-11eb-8601-2763f2ee6bb4.png)

![screenshot](https://user-images.githubusercontent.com/4943215/109431832-b6cac080-7a08-11eb-9c5e-a058680c23a1.png)

![screenshot](https://user-images.githubusercontent.com/4943215/73125194-5f0b8b80-3fa4-11ea-805c-8387187503ad.png) -->
