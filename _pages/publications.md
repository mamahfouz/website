---
layout: archive
permalink: /publications/
author_profile: true
---

Workshop Papers
======
**On the Importance of Opponent Modeling in Auction Markets**<br />
**Mahmoud Mahfouz**, Angelos Filos, Cyrine Chtourou, Joshua Lockhart, Samuel Assefa, <br />
Manuela Veloso, Danilo Mandic, Tucker Balch.<br /> 
*NeurIPS 2019 Workshop of Robust AI in Financial Services*.<br />
[[Paper]](https://arxiv.org/abs/1911.12816)
**Abstract**: The dynamics of financial markets are driven by the interactions between participants, as well as the trading mechanisms and regulatory frameworks that govern these interactions. Decision-makers would rather not ignore the impact of other participants on these dynamics and should employ tools and models that take this into account. To this end, we demonstrate the efficacy of applying opponent-modeling in a number of simulated market settings. While our simulations are simplified representations of actual market dynamics, they provide an idealized "playground" in which our techniques can be demonstrated and tested. We present this work with the aim that our techniques could be refined and, with some effort, scaled up to the full complexity of real-world market scenarios. We hope that the results presented encourage practitioners to adopt opponent-modeling methods and apply them online systems, in order to enable not only reactive but also proactive decisions to be made.


**Get Real: Metrics for Simulated Equity Market Realism**.<br /> 
Svitlana Vyetrenko, David Byrd, Nick Petosa, **Mahmoud Mahfouz**, Danial Dervovic, Tucker Balch.<br /> 
*NeurIPS 2019 Workshop of Robust AI in Financial Services*.<br />
[[Paper]](https://arxiv.org/abs/1912.04941)
**Abstract**: Machine learning (especially reinforcement learning) methods for trading are increasingly reliant on simulation for agent training and testing. Furthermore, simulation is important for validation of hand-coded trading strategies and for testing hypotheses about market structure. A challenge, however, concerns the robustness of policies validated in simulation because the simulations lack fidelity. In fact, researchers have shown that many market simulation approaches fail to reproduce statistics and stylized facts seen in real markets. As a step towards addressing this we surveyed the literature to collect a set of reference metrics and applied them to real market data and simulation output. Our paper provides a comprehensive catalog of these metrics including mathematical formulations where appropriate. Our results show that there are still significant discrepancies between simulated markets and real ones. However, this work serves as a benchmark against which we can measure future improvement.

**Generating Synthetic Data in Finance: Opportunities, Challenges and Pitfalls**.<br /> 
Samuel Assefa, Danial Dervovic, **Mahmoud Mahfouz**, Prashant Reddy, Tucker Balch, Manuela Veloso.<br /> 
*NeurIPS 2019 Workshop of Robust AI in Financial Services*.
**Abstract**: Financial services generate a huge volume of data that is extremely complex and varied. These datasets are often stored in silos within organisations for various reasons, including but not limited to, regulatory requirements and business needs. As a result, data sharing within different lines of business as well as outside of the organisation (e.g. to the research community) is severely limited. It is therefore critical to investigate methods for synthesising financial datasets that follow the same properties of the real data while respecting the need for privacy of the parties involved in a particular dataset. This introductory paper aims to highlight the growing need for effective synthetic data generation in the financial domain. We highlight three main areas of focus for the academic community: 1) Generating realistic synthetic datasets. 2) Measuring the similarities between real and generated datasets 3) Ensuring the generative process satisfies any privacy constraints. Although these challenges are also present in other domains, the extra regulatory and privacy requirements add another dimension of complexity and offer a unique opportunity to study the topic in financial services. Finally, we aim to develop a shared vocabulary and context for generating synthetic financial data using two types of financial datasets as examples.

**How to Evaluate Trading Strategies: Single Agent Market Replay or Multiple Agent Interactive Simulation?**.<br /> 
Tucker Balch, **Mahmoud Mahfouz**, Joshua Lockhart, Maria Hybinette, David Byrd.<br /> 
*ICML 2019 Workshop on AI in Finance: Applications and Infrastructure for Multi-Agent Learning*<br />
[[Paper]](https://arxiv.org/abs/1906.12010)
**Abstract**:We show how a multi-agent simulator can support two important but distinct methods for assessing a trading strategy: Market Replay and Interactive Agent-Based Simulation (IABS). Our solution is important because each method offers strengths and weaknesses that expose or conceal flaws in the subject strategy. A key weakness of Market Replay is that the simulated market does not substantially adapt to or respond to the presence of the experimental strategy. IABS methods provide an artificial market for the experimental strategy using a population of background trading agents. Because the background agents attend to market conditions and current price as part of their strategy, the overall market is responsive to the presence of the experimental strategy. Even so, IABS methods have their own weaknesses, primarily that it is unclear if the market environment they provide is realistic. We describe our approach in detail, and illustrate its use in an example application: The evaluation of market impact for various size orders.

Preprint
======
**Compression and Interpretability of Deep Neural Networks via Tucker Tensor Layer: From First Principles to Tensor Valued Back-Propagation**<br />
Giuseppe G. Calvi, Ahmad Moniri, **Mahmoud Mahfouz**, Qibin Zhao, Danilo P. Mandic.<br />
[[Paper]](https://arxiv.org/abs/1903.06133)
**Abstract**: This work aims to help resolve the two main stumbling blocks in the application of Deep Neural Networks (DNNs), that is, the exceedingly large number of trainable parameters and their physical interpretability. This is achieved through a tensor valued approach, based on the proposed Tucker Tensor Layer (TTL), as an alternative to the dense weight-matrices of DNNs. This allows us to treat the weight-matrices of general DNNs as a matrix unfolding of a higher order weight-tensor. By virtue of the compression properties of tensor decompositions, this enables us to introduce a novel and efficient framework for exploiting the multi-way nature of the weight-tensor in order to dramatically reduce the number of DNN parameters. We also derive the tensor valued back-propagation algorithm within the TTL framework, by extending the notion of matrix derivatives to tensors. In this way, the physical interpretability of the Tucker decomposition is exploited to gain physical insights into the NN training, through the process of computing gradients with respect to each factor matrix. The proposed framework is validated on both synthetic data, and the benchmark datasets MNIST, Fashion-MNIST, and CIFAR-10. Overall, through the ability to provide the relative importance of each data feature in training, the TTL back-propagation is shown to help mitigate the "black-box" nature inherent to NNs. Experiments also illustrate that the TTL achieves a 66.63-fold compression on MNIST and Fashion-MNIST, while, by simplifying the VGG-16 network, it achieves a 10\% speed up in training time, at a comparable performance.
