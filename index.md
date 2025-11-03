# Chenguang Duan

I am a postdoctoral researcher in the Institut für Geometrie und Praktische Mathematik at RWTH Aachen University, working with Prof. Dr. [Markus Bachmayr](https://www.igpm.rwth-aachen.de/team/bachmayr) and Prof. Dr. [Wolfgang Dahmen](https://www.igpm.rwth-aachen.de/team/former/dahmen). Prior to RWTH Aachen, I obtained my Ph.D. from the School of Mathematics and Statistics, Wuhan University, where I was advised by Prof. [Jerry Zhijian Yang](https://imai.whu.edu.cn/info/1031/2141.htm). Throughout my research, I also work closely with Prof. [Yuling Jiao](https://jszy.whu.edu.cn/jiaoyuling/en/lwcg/1349484/list/index.htm). I earned my Bachelor's degree in Mathematics from Wuhan University as well. 

<br>

My research interests lie at the intersection of computational mathematics, statistics, and machine learning, with a particular emphasis on scientific machine learning, generative models, and learning theory.

<br>

Here is my [Google Scholar](https://scholar.google.com/citations?user=RpmGgyMAAAAJ) page.

Address: Room 105, Templergraben 55, 52062 Aachen, Germany

Email: [cgduan.math@gmail.com](cgduan.math@gmail.com) (Preferred), [duan@igpm.rwth-aachen.de](duan@igpm.rwth-aachen.de)

ORCID: [0009-0009-0815-6281](https://orcid.org/0009-0009-0815-6281)

<br>

## Research interests
---

* Scientific machine learning

* Generative models and sampling
  
* Inverse problems

* Statistical learning and deep learning theory
  
<br>

## Research
---

[Google Scholar](https://scholar.google.com/citations?user=RpmGgyMAAAAJ) (All of my publications have authors listed in alphabetical order)

<br>

**Ongoing Work**

[Nonlinear Assimilation via Score-based Sequential Langevin Sampling](docs/Nonlinear_Assimilation_via_Score-based_Sequential_Langevin_Sampling.pdf)
  
Zhao Ding, Chenguang Duan, Yuling Jiao, Jerry Zhijian Yang, Cheng Yuan, and Pingwen Zhang

[[arXiv]](https://arxiv.org/abs/2411.13443v2) [[PDF]](docs/Nonlinear_Assimilation_via_Score-based_Sequential_Langevin_Sampling.pdf) [[code]](https://github.com/burning489/SSLS) [[slides]](docs/Nonlinear_Assimilation_via_Score-based_Sequential_Langevin_Sampling_slides.pdf)

<details>
<summary> Abstract </summary>
<div class="collapsible-content">
This paper presents score-based sequential Langevin sampling (SSLS), a novel approach to nonlinear data assimilation within a recursive Bayesian filtering framework. The proposed method decomposes the assimilation process into alternating prediction and update steps, leveraging dynamic models for state prediction while incorporating observational data through score-based Langevin Monte Carlo during updates. To address challenges in posterior sampling, we introduce an annealing strategy within the update mechanism. We provide theoretical guarantees for SSLS convergence in total variation (TV) distance under certain conditions, providing insights into error behavior with respect to key hyper-parameters. Our numerical experiments across challenging scenarios -- including high-dimensional systems, strong nonlinearity, and sparse observations -- demonstrate the robust performance of the proposed method. Furthermore, SSLS effectively quantifies the uncertainty associated with the estimated states, making it particularly valuable for the error calibration.
</div>
</details> 

<details>
<summary> Bibtex </summary>
<pre><code>
@misc{ding2025nonlinear,
      title={Nonlinear Assimilation via Score-based Sequential {S}angevin Sampling}, 
      author={Zhao Ding and Chenguang Duan and Yuling Jiao and Jerry Zhijian Yang and Cheng Yuan and Pingwen Zhang},
      year={2025},
      note={arXiv:2411.13443},
}
</code></pre>
</details> 

<br>

[Characteristic Learning for Provable One Step Generation](docs/Characteristic_Learning.pdf)
 
Zhao Ding, Chenguang Duan, Yuling Jiao, Ruoxuan Li, Jerry Zhijian Yang, and Pingwen Zhang

[[arXiv]](https://arxiv.org/abs/2405.05512v5) [[PDF]](docs/Characteristic_Learning.pdf) [[code]](https://github.com/burning489/CharacteristicGenerator)

<details>
<summary> Abstract </summary>
<div class="collapsible-content">
We propose the characteristic generator, a novel one-step generative model that combines the efficiency of sampling in Generative Adversarial Networks (GANs) with the stable performance of flow-based models. Our model is driven by characteristics, along which the probability density transport can be described by ordinary differential equations (ODEs). Specifically, we first estimate the underlying velocity field and use the Euler method to solve the probability flow ODE, generating discrete approximations of the characteristics. A deep neural network is then trained to fit these characteristics, creating a one-step map that pushes a simple Gaussian distribution to the target distribution. In the theoretical aspect, we provide a comprehensive analysis of the errors arising from velocity matching, Euler discretization, and characteristic fitting to establish a non-asymptotic convergence rate in the 2-Wasserstein distance under mild data assumptions. Crucially, we demonstrate that under a standard manifold assumption, this convergence rate depends only on the intrinsic dimension of data rather than the much larger ambient dimension, proving our model's ability to mitigate the curse of dimensionality. To our knowledge, this is the first rigorous convergence analysis for a flow-based one-step generative model. Experiments on both synthetic and real-world datasets demonstrate that the characteristic generator achieves high-quality and high-resolution sample generation with the efficiency of just a single neural network evaluation.
</div>
</details> 

<details>
<summary> Bibtex </summary>
<pre><code>
@misc{ding2025characteristiclearningprovablestep,
      title={Characteristic Learning for Provable One Step Generation}, 
      author={Zhao Ding and Chenguang Duan and Yuling Jiao and Ruoxuan Li and Jerry Zhijian Yang and Pingwen Zhang},
      year={2025},
      note={arXiv:2405.05512},
}
</code></pre>
</details> 

<br>

**Selected Publications**

[Semi-Supervised Deep Sobolev Regression: Estimation and Variable Selection by ReQU Neural Network](docs/Semi_Supervised_Deep_Sobolev_Regression.pdf) 

Zhao Ding, Chenguang Duan, Yuling Jiao, and Jerry Zhijian Yang

*IEEE Transactions on Information Theory* (2025)

\* Awarded the 18th East Asia Section of SIAM (EASIAM) Student Paper Prize, Second Prize

[[Journal]](https://ieeexplore.ieee.org/document/10858754) [[arXiv]](https://arxiv.org/abs/2401.04535v2) [[PDF]](docs/Semi_Supervised_Deep_Sobolev_Regression.pdf) [[slides]](docs/Semi_Supervised_Deep_Sobolev_Regression_slides.pdf)

<br>

[Recovering the Source Term in Elliptic Equation via Deep Learning: Method and Convergence Analysis](docs/Inverse_Source_PINNs.pdf)

Chenguang Duan, Yuling Jiao, Jerry Zhijian Yang, and Pingwen Zhang

*East Asian Journal on Applied Mathematics* (2024)

[[Journal]](https://journal.global-sci.org/intro/article_detail/eajam/23157.html) [[PDF]](docs/Inverse_Source_PINNs.pdf)

<br>

[Current Density Impedance Imaging with PINNs](docs/CDII_PINNs.pdf)

Chenguang Duan, Junjun Huang, Yuling Jiao, Xiliang Lu, and Jerry Zhijian Yang

*Journal of Computational and Applied Mathematics* (2024)

[[Journal]](https://www.sciencedirect.com/science/article/pii/S0377042724003698) [[arXiv]](https://arxiv.org/abs/2306.13881) [[PDF]](docs/CDII_PINNs.pdf)

<br>

[Deep Ritz Methods for Laplace Equations with Dirichlet Boundary Condition](docs/Deep_Ritz_Dirichlet.pdf)

Chenguang Duan, Yuling Jiao, Yanming Lai, Xiliang Lu, Qimeng Quan, and Jerry Zhijian Yang

*CSIAM Transactions on Applied Mathematics* (2022)

[[Journal]](https://journal.global-sci.org/intro/article_detail/csiam-am/21155.html) [[arXiv]](https://arxiv.org/abs/2111.02009) [[PDF]](docs/Deep_Ritz_Dirichlet.pdf) 

<br>

[Convergence Rate Analysis for Deep Ritz Method](docs/Deep_Ritz.pdf)

Chenguang Duan, Yuling Jiao, Yanming Lai, Dingwei Li, Xiliang Lu, and Jerry Zhijian Yang

*Communications in Computational Physics* (2022).

[[Journal]](https://journal.global-sci.org/intro/article_detail/cicp/20375.html) [[arXiv]](https://arxiv.org/abs/2103.13330) [[PDF]](docs/Deep_Ritz.pdf)






<body>
<script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=ffffff&w=150&t=n&d=H9CnWG9M-zXOpBTdhYeqHGEuPRWYE5zH19GabgSMt_M&co=ffffff&cmo=ffffff&cmn=ffffff&ct=ffffff'></script>
</body>



