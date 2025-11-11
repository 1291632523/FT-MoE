# FT-MoE
<h1 align="center">FT-MoE</h1>
<div align="center">
  <a href="https://github.com/imperial-qore/PreGAN/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-BSD%203--Clause-red.svg" alt="License">
  </a>
   <a>
    <img src="https://img.shields.io/badge/python-3.9-blue.svg" alt="Python 3.9">
  </a>
</div>

   <!-- <a>
    <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fimperial-qore%2FPreGAN&count_bg=%23FFC401&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false" alt="Hits">
  </a>
   <a href="https://github.com/imperial-qore/PreGAN/actions">
    <img src="https://github.com/imperial-qore/COSCO/workflows/DeFog-Benchmarks/badge.svg" alt="Actions Status">
  </a>
 <br>
   <a>
    <img src="https://img.shields.io/docker/pulls/shreshthtuli/yolo?label=docker%20pulls%3A%20yolo" alt="Docker pulls yolo">
  </a>
   <a>
    <img src="https://img.shields.io/docker/pulls/shreshthtuli/pocketsphinx?label=docker%20pulls%3A%20pocketsphinx" alt="Docker pulls pocketsphinx">
  </a>
   <a>
    <img src="https://img.shields.io/docker/pulls/shreshthtuli/aeneas?label=docker%20pulls%3A%20aeneas" alt="Docker pulls aeneas">
  </a> -->
  > __Note__: . 

</div>
Intelligent fault-tolerant (FT) computing has recently demonstrated significant advantages in predicting and diagnosing faults proactively, thereby ensuring reliable service delivery. However, due to the heterogeneity of fault knowledge, dynamic workloads, and limited data support, existing deep learning-based FT algorithms face challenges in fault detection quality and training efficiency. This is primarily because their homogenization of fault knowledge perception difficuties to fully capture diverse and complex fault patterns. To address these challenges, we propose FT-MoE, a sustainable-learning fault-tolerant computing framework based on a dual-path architecture for high-accuracy fault detection and classification. This model employs a mixture-of-experts (MoE) architecture, enabling different parameters to learn distinct fault knowledge. Additionally, we adopt a two-stage learning scheme that combines comprehensive offline training with continual online tuning, allowing the model to adaptively optimize its parameters in response to evolving real-time workloads. To facilitate realistic evaluation, we construct a new fault detection and classification dataset for edge networks, comprising 10,000 intervals with fine-grained resource features, surpassing existing datasets in both scale and granularity. Finally, we conduct extensive experiments on the FT benchmark to verify the effectiveness of FT-MoE. Results demonstrate that our model outperforms state-of-the-art methods. The code will be made available upon publication.

## License

BSD-3-Clause. 
Copyright (c) 2021, Shreshth Tuli.
All rights reserved.

See License file for more details.
