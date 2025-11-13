# Chenguang Duan

I am a postdoctoral researcher in the Institut für Geometrie und Praktische Mathematik at RWTH Aachen University, working with Prof. Dr. [Markus Bachmayr](https://www.igpm.rwth-aachen.de/team/bachmayr) and Prof. Dr. [Wolfgang Dahmen](https://www.igpm.rwth-aachen.de/team/former/dahmen). 

<br>

Previously, I obtained my Ph.D. from the School of Mathematics and Statistics at Wuhan University, where I was advised by Prof. [Jerry Zhijian Yang](https://imai.whu.edu.cn/info/1031/2141.htm) and Prof. [Yuling Jiao](https://jszy.whu.edu.cn/jiaoyuling/en/lwcg/1349484/list/index.htm). I earned a Bachelor's degree in Mathematics from Wuhan University as well.

<br>

My research interests lie at the intersection of computational mathematics, statistics, and machine learning, with a particular focus on scientific machine learning, generative models, and learning theory.

<br>

I welcome opportunities for collaboration and discussion. Please feel free to reach out if you share an interest in these topics.

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
  
with Zhao Ding, Yuling Jiao, Jerry Zhijian Yang, Cheng Yuan, and Pingwen Zhang

[[arXiv]](https://arxiv.org/abs/2411.13443) [[PDF]](docs/Nonlinear_Assimilation_via_Score-based_Sequential_Langevin_Sampling.pdf) [[code]](https://github.com/burning489/SSLS) [[slides]](docs/Nonlinear_Assimilation_via_Score-based_Sequential_Langevin_Sampling_slides.pdf)

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
 
with Zhao Ding, Yuling Jiao, Ruoxuan Li, Jerry Zhijian Yang, and Pingwen Zhang

[[arXiv]](https://arxiv.org/abs/2405.05512) [[PDF]](docs/Characteristic_Learning_for_Provable_One_Step_Generation.pdf) [[code]](https://github.com/burning489/CharacteristicGenerator) [[slides]](docs/Characteristic_Learning_for_Provable_One_Step_Generation_slides.pdf)

<details>
<summary> Abstract </summary>
<div class="collapsible-content">
We propose the characteristic generator, a novel one-step generative model that combines the efficiency of sampling in Generative Adversarial Networks (GANs) with the stable performance of flow-based models. Our model is driven by characteristics, along which the probability density transport can be described by ordinary differential equations (ODEs). Specifically, we first estimate the underlying velocity field and use the Euler method to solve the probability flow ODE, generating discrete approximations of the characteristics. A deep neural network is then trained to fit these characteristics, creating a one-step map that pushes a simple Gaussian distribution to the target distribution. In the theoretical aspect, we provide a comprehensive analysis of the errors arising from velocity matching, Euler discretization, and characteristic fitting to establish a non-asymptotic convergence rate in the 2-Wasserstein distance under mild data assumptions. Crucially, we demonstrate that under a standard manifold assumption, this convergence rate depends only on the intrinsic dimension of data rather than the much larger ambient dimension, proving our model's ability to mitigate the curse of dimensionality. To our knowledge, this is the first rigorous convergence analysis for a flow-based one-step generative model. Experiments on both synthetic and real-world datasets demonstrate that the characteristic generator achieves high-quality and high-resolution sample generation with the efficiency of just a single neural network evaluation.
</div>
</details> 

<details>
<summary> Bibtex </summary>
<pre><code>
@misc{ding2025characteristic,
title={Characteristic Learning for Provable One Step Generation}, 
author={Zhao Ding and Chenguang Duan and Yuling Jiao and Ruoxuan Li and Jerry Zhijian Yang and Pingwen Zhang},
year={2025},
note={arXiv:2405.05512},
}
</code></pre>
</details> 

<br>

**Selected Publications**

[Semi-Supervised Deep Sobolev Regression: Estimation and Variable Selection by ReQU Neural Network](docs/Semi_Supervised_Deep_Sobolev_Regression_Estimation_and_Variable_Selection_by_ReQU_Neural_Network.pdf) 

with Zhao Ding, Yuling Jiao, and Jerry Zhijian Yang

*IEEE Transactions on Information Theory* (2025)

\* Awarded the 18th East Asia Section of SIAM (EASIAM) Student Paper Prize, Second Prize

[[Journal]](https://ieeexplore.ieee.org/document/10858754) [[arXiv]](https://arxiv.org/abs/2401.04535) [[PDF]](docs/Semi_Supervised_Deep_Sobolev_Regression_Estimation_and_Variable_Selection_by_ReQU_Neural_Network.pdf) [[slides]](docs/Semi_Supervised_Deep_Sobolev_Regression_Estimation_and_Variable_Selection_by_ReQU_Neural_Network_slides.pdf)

<details>
<summary> Abstract </summary>
<div class="collapsible-content">
We propose SDORE, a semi-supervised deep Sobolev regressor, for the nonparametric estimation of the underlying regression function and its gradient. SDORE employs deep ReQU neural networks to minimize the empirical risk with gradient norm regularization, allowing the approximation of the regularization term by unlabeled data. Our study includes a thorough analysis of the convergence rates of SDORE in $L^{2}$-norm, achieving the minimax optimality. Further, we establish a convergence rate for the associated plug-in gradient estimator, even in the presence of significant domain shift. These theoretical findings offer valuable insights for selecting regularization parameters and determining the size of the neural network, while showcasing the provable advantage of leveraging unlabeled data in semi-supervised learning. To the best of our knowledge, SDORE is the first provable neural network-based approach that simultaneously estimates the regression function and its gradient, with diverse applications such as nonparametric variable selection. The effectiveness of SDORE is validated through an extensive range of numerical simulations.
</div>
</details> 

<details>
<summary> Bibtex </summary>
<pre><code>
@article{ding2025semi,
author={Ding, Zhao and Duan, Chenguang and Jiao, Yuling and Yang, Jerry Zhijian},
journal={IEEE Transactions on Information Theory}, 
title={Semi-Supervised Deep {S}obolev Regression: {E}stimation and Variable Selection by {ReQU} Neural Network}, 
year={2025},
volume={71},
number={4},
pages={2955--2981},
}
</code></pre>
</details> 

<br>

[Recovering the Source Term in Elliptic Equation via Deep Learning: Method and Convergence Analysis](docs/Recovering_the_Source_Term_in_Elliptic_Equation_via_Deep_Learning_Method_and_Convergence_Analysis.pdf)

with Yuling Jiao, Jerry Zhijian Yang, and Pingwen Zhang

*East Asian Journal on Applied Mathematics* (2024)

[[Journal]](https://journal.global-sci.org/intro/article_detail/eajam/23157.html) [[PDF]](docs/Recovering_the_Source_Term_in_Elliptic_Equation_via_Deep_Learning_Method_and_Convergence_Analysis.pdf)

<details>
<summary> Abstract </summary>
<div class="collapsible-content">
In this paper, we present a deep learning approach to tackle elliptic inverse source problems. Our method combines Tikhonov regularization with physics-informed neural networks, utilizing separate neural networks to approximate the source term and solution. Firstly, we construct a population loss and derive stability estimates. Furthermore, we conduct a convergence analysis of the empirical risk minimization estimator. This analysis yields a prior rule for selecting regularization parameters, determining the number of observations, and choosing the size of neural networks. Finally, we validate our proposed method through numerical experiments. These experiments also demonstrate the remarkable robustness of our approach against data noise, even at high levels of up to 50%.
</div>
</details> 

<details>
<summary> Bibtex </summary>
<pre><code>
@article{duan2024recovering, 
author = {Duan, Chenguang and Jiao, Yuling and Yang, Jerry Zhijian and Zhang, Pingwen}, 
title = {Recovering the Source Term in Elliptic Equation via Deep Learning: {M}ethod and Convergence Analysis}, 
journal = {East Asian Journal on Applied Mathematics}, 
year = {2024}, 
volume = {14}, 
number = {3}, 
pages = {460--489}, 
}
</code></pre>
</details> 

<br>

[Current Density Impedance Imaging with PINNs](docs/Current_Density_Impedance_Imaging_with_PINNs.pdf)

with Junjun Huang, Yuling Jiao, Xiliang Lu, and Jerry Zhijian Yang

*Journal of Computational and Applied Mathematics* (2024)

[[Journal]](https://www.sciencedirect.com/science/article/pii/S0377042724003698) [[arXiv]](https://arxiv.org/abs/2306.13881) [[PDF]](docs/Current_Density_Impedance_Imaging_with_PINNs.pdf)

<details>
<summary> Abstract </summary>
<div class="collapsible-content">
In this paper, we introduce CDII-PINNs, a computationally efficient method for solving CDII using PINNs in the framework of Tikhonov regularization. This method constructs a physics-informed loss function by merging the regularized least-squares output functional with an underlying differential equation, which describes the relationship between the conductivity and voltage. A pair of neural networks representing the conductivity and voltage, respectively, are coupled by this loss function. Then, minimizing the loss function provides a reconstruction. A rigorous theoretical guarantee is provided. We give an error analysis for CDII-PINNs and establish a convergence rate, based on prior selected neural network parameters in terms of the number of samples. The numerical simulations demonstrate that CDII-PINNs are efficient, accurate and robust to noise levels ranging from 1% to 20%.
</div>
</details> 

<details>
<summary> Bibtex </summary>
<pre><code>
@article{duan2024Current,
title = {Current density impedance imaging with {PINNs}},
journal = {Journal of Computational and Applied Mathematics},
volume = {452},
pages = {116120},
year = {2024},
author = {Chenguang Duan and Junjun Huang and Yuling Jiao and Xiliang Lu and Jerry Zhijian Yang},
}
</code></pre>
</details> 

<br>

[Deep Ritz Methods for Laplace Equations with Dirichlet Boundary Condition](docs/Deep_Ritz_Methods_for_Laplace_Equations_with_Dirichlet_Boundary_Condition.pdf)

with Yuling Jiao, Yanming Lai, Xiliang Lu, Qimeng Quan, and Jerry Zhijian Yang

*CSIAM Transactions on Applied Mathematics* (2022)

[[Journal]](https://journal.global-sci.org/intro/article_detail/csiam-am/21155.html) [[arXiv]](https://arxiv.org/abs/2111.02009) [[PDF]](docs/Deep_Ritz_Methods_for_Laplace_Equations_with_Dirichlet_Boundary_Condition.pdf) 

<details>
<summary> Abstract </summary>
<div class="collapsible-content">
Deep Ritz methods (DRM) have been proven numerically to be efficient in solving partial differential equations. In this paper, we present a convergence rate in $H^{1}$ norm for deep Ritz methods for Laplace equations with Dirichlet boundary condition, where the error depends on the depth and width in the deep neural networks and the number of samples explicitly. Further we can properly choose the depth and width in the deep neural networks in terms of the number of training samples. The main idea of the proof is to decompose the total error of DRM into three parts, that is approximation error, statistical error and the error caused by the boundary penalty. We bound the approximation error in $H^{1}$-norm with ReLU$^{2}$ networks and control the statistical error via Rademacher complexity. In particular, we derive the bound on the Rademacher complexity of the non-Lipschitz composition of gradient norm with ReLU$^{2}$ network, which is of immense independent interest. We also analyze the error inducing by the boundary penalty method and give a prior rule for tuning the penalty parameter.
</div>
</details> 

<details>
<summary> Bibtex </summary>
<pre><code>
@article{duan2022deep,
author = {Duan, Chenguang and Jiao, Yuling and Lai, Yanming and Lu, Xiliang and Quan, Qimeng and Yang, Jerry Zhijian}, 
title = {Deep {Ritz} Methods for {Laplace} Equations with {Dirichlet} Boundary Condition}, 
journal = {CSIAM Transactions on Applied Mathematics}, 
year = {2022}, 
volume = {3}, 
number = {4}, 
pages = {761--791},
}
</code></pre>
</details> 

<br>

[Convergence Rate Analysis for Deep Ritz Method](docs/Convergence_Rate_Analysis_for_Deep_Ritz_Method.pdf)

with Yuling Jiao, Yanming Lai, Dingwei Li, Xiliang Lu, and Jerry Zhijian Yang

*Communications in Computational Physics* (2022).

[[Journal]](https://journal.global-sci.org/intro/article_detail/cicp/20375.html) [[arXiv]](https://arxiv.org/abs/2103.13330) [[PDF]](docs/Convergence_Rate_Analysis_for_Deep_Ritz_Method.pdf)

<details>
<summary> Abstract </summary>
<div class="collapsible-content">
Using deep neural networks to solve PDEs has attracted a lot of attentions recently. However, why the deep learning method works is falling far behind its empirical success. In this paper, we provide a rigorous numerical analysis on deep Ritz method (DRM) for second order elliptic equations with Neumann boundary conditions. We establish the first nonasymptotic convergence rate in $H^{1}$ norm for DRM using deep networks with ReLU$^2$ activation functions. In addition to providing a theoretical justification of DRM, our study also shed light on how to set the hyperparameter of depth and width to achieve the desired convergence rate in terms of number of training samples. Technically, we derive bound on the approximation error of deep ReLU$^2$ network in $C^{1}$ norm and bound on the Rademacher complexity of the non-Lipschitz composition of gradient norm and ReLU$^2$ network, both of which are of independent interest.
</div>
</details> 

<details>
<summary> Bibtex </summary>
<pre><code>
@article{duan2022convergence, 
author = {Duan, Chenguang and Jiao, Yuling and Lai, Yanming and Li, Dingwei and Lu, Xiliang and Yang, Jerry Zhijian}, 
title = {Convergence Rate Analysis for Deep {Ritz} Method}, 
journal = {Communications in Computational Physics}, 
year = {2022}, 
volume = {31}, 
number = {4}, 
pages = {1020--1048},
}
</code></pre>
</details> 


<body>
<script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=ffffff&w=150&t=n&d=H9CnWG9M-zXOpBTdhYeqHGEuPRWYE5zH19GabgSMt_M&co=ffffff&cmo=ffffff&cmn=ffffff&ct=ffffff'></script>
</body>



