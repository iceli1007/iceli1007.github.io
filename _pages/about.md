---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a Associate Professor in the team of [Zhangjie Fu](https://faculty.nuist.edu.cn/zhangjiefu/zh_CN/index.htm), [School of Computer Science](https://scs.nuist.edu.cn/main.htm), [Nanjing University of Information Science and Technology](https://www.nuist.edu.cn/main.htm). I received my Ph.D. degree from the [Department of Electronic Engineering and Information Science](https://eeis.ustc.edu.cn/) at [University of Science and Technology of China](https://ustc.edu.cn/), under the supervision of professor [Bin Li](http://staff.ustc.edu.cn/~binli/) in 2024. I received my Bachelor’s degree from [University of Science and Technology of China](https://ustc.edu.cn/) in 2019.

My research interests mainly lie in **Artificial Intelligence Generated Content** and **AI Security**. My works focus on GANs, Diffusion, and backdoor learning of neural networks.


# 🔥 News
- *2025.09*: &nbsp;🎉🎉 One paper accepted to **NeurIPS 2025**.
- *2025.08*: &nbsp;🎉🎉 One paper accepted to **IEEE Transactions on Dependable and Secure Computing (IEEE TDSC)**.
- *2025.07*: &nbsp;🎉🎉 Three paper accepted to **ACM Multimedia 2025**.
- *2024.10*: &nbsp;🎉🎉 One paper accepted to **IEEE Transactions on Circuits and Systems for Video Technology (IEEE TCSVT)**.
- *2024.10*: &nbsp;🎉🎉 One paper accepted to **International Journal of Computer Vision (IJCV)**.
- *2024.09*: &nbsp;🎉🎉 One paper accepted to **IEEE Transactions on Information Forensics and Security (IEEE TIFS)**.
- *2024.07*: &nbsp;🎉🎉 One paper accepted to **ECCV 2024**.
- *2024.07*: &nbsp;🎉🎉 One paper accepted to **ICLR 2024**.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TDSC 2025</div><img src='images/fus_plus.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Explore the Effect of Data Selection on Poison Efficiency in Backdoor Attacks](https://ieeexplore.ieee.org/abstract/document/11119781)

**Ziqiang Li**, Pengfei Xia, Hong Sun, Yueqi Zeng, Wei Zhang, Bin Li

- we investigate the role of forgettable event and loss landscape curvature in enhancing poisoning sample efficiency. Our findings reveal that samples most likely to be forgotten during the poisoning process are crucial for effective attacks, and that low-curvature regions of the loss surface correlate with higher poisoning efficiency.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/decouping.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Infinite-ID: Identity-preserved Personalization via ID-semantics Decoupling Paradigm](https://link.springer.com/chapter/10.1007/978-3-031-73242-3_16)

Yi Wu, **Ziqiang Li** (Equal Contribution), Heliang Zheng, Chaoyue Wang, Bin Li.

[**Project**](https://infinite-id.github.io/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- An ID-semantics decoupling paradigm for tuning-free identity-preserved personalization. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2024</div><img src='images/PIP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Peer is Your Pillar: A Data-unbalanced Conditional GANs for Few-shot Image Generation](https://ieeexplore.ieee.org/abstract/document/10731854)

**Ziqiang Li**, Chaoyue Wang, Xue Rui, Chao Xue, Jiaxu Leng, ZhangJie Fu, Bin Li

- A novel pipeline called Peer is your Pillar (PIP), which combines a target few-shot dataset with a peer dataset to enable data-unbalanced conditional generation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2024</div><img src='images/one-shot-GDA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[One-Shot Generative Domain Adaptation in 3D GANs](https://link.springer.com/article/10.1007/s11263-024-02268-4)

**Ziqiang Li** (Equal Contribution), Yi Wu, Chaoyue Wang, Xue Rui, Bin Li.

- Introducing a novel task, One-shot 3D Generative Domain Adaptation (GDA), which focuses on transferring a pre-trained 3D generator from one domain to a new one using only a single reference image.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIFS 2024</div><img src='images/PFS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Proxy Attack-Free Strategy for Practically Improving the Poisoning Efficiency in Backdoor Attacks](https://ieeexplore.ieee.org/abstract/document/10703160)

**Ziqiang Li**, Hong Sun, Pengfei Xia, Beihao Xia, Xue Rui, Wei Zhang, Qinglang Guo, Zhangjie Fu, Bin Li.

- A Proxy attack-Free Strategy (PFS) designed to identify efficient poisoning samples based on the similarity between clean samples and their corresponding poisoning samples.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2024</div><img src='images/LLM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Large Language Models are Good Attackers: Efficient and Stealthy Textual Backdoor Attacks](https://arxiv.org/pdf/2408.11587)

**Ziqiang Li**, Yueqi Zeng, Pengfei Xia, Lei Liu, Zhangjie Fu, Bin Li.

- Leveraging Large Language Models (LLMs) to acquire Efficient and Stealthy Textual backdoor attack method.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/data-const.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Efficient Backdoor Attacks for Deep Neural Networks in Real-world Scenarios](https://openreview.net/pdf?id=vRyp2dhEQp)

**Ziqiang Li** (Equal Contribution), Hong Sun, Pengfei Xia, Heng Li, Beihao Xia, Yi Wu, Bin Li.

- Introducing a realistic backdoor attack scenario where victims collect data from
multiple sources, and attackers cannot access the complete training data. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/DoRM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Domain Re-Modulation for Few-Shot Generative Domain Adaptation](https://openreview.net/pdf?id=jown9RvYn7)

Yi Wu, **Ziqiang Li** (Equal Contribution), Chaoyue Wang, Heliang Zheng, Shanshan Zhao, Bin Li, and Dacheng Tao.

- Not only fulfills three essential properties of few-shot GDA but also introduces two new capabilities: Memory and Domain Association.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CSUR 2023</div><img src='images/CSUR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Systematic Survey of Regularization and Normalization in GANs](https://dl.acm.org/doi/10.1145/3569928)

**Ziqiang Li**, Muhammad Usman, Rentuo Tao, Pengfei Xia, Chaoyue Wang, Huanhuan Chen, and Bin Li.

- Conducting a comprehensive survey on the regularization and normalization techniques from different perspectives of GANs training.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TOMM 2023</div><img src='images/HFC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring The Effect of High-frequency Components in GANs Training](https://dl.acm.org/doi/abs/10.1145/3578585)

**Ziqiang Li**, Pengfei Xia, Xue Rui, and Bin Li.

- Proposing two simple yet effective frequency operations for eliminating the side effects caused by high-frequency differences in GANs training.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TETCI 2023</div><img src='images/DAT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A New Perspective on Stabilizing GANs Training: Direct Adversarial Training](https://ieeexplore.ieee.org/document/9851855)

**Ziqiang Li**, Pengfei Xia, Rentuo Tao, Hongjing Niu, and Bin Li.

- Images produced by the generator act like adversarial examples of the discriminator during the training process, which may be part of the reason causing the unstable training of GANs.
</div>
</div>

- `TDSC 2022` [Enhancing Backdoor Attacks with Multi-Level MMD Regularization](https://ieeexplore.ieee.org/abstract/document/9743735), Pengfei Xia, Hongjing Niu, **Ziqiang Li**, and Bin Li. 


- `ECCV 2022` [Fakeclr: Exploring Contrastive Learning for Solving Latent Discontinuity in Data-efficient GANs](https://link.springer.com/chapter/10.1007/978-3-031-19784-0_35), **Ziqiang Li**, Chaoyue Wang, Heliang Zheng, Jing Zhang, Bin Li.


# 🎖 Honors and Awards
- *2023.12* Best Student Paper Award of BigDIA 2023. 
- *2019.4* National Encouragement Scholarship. USTC.
- *2018.12* Bronze Award of the Excellent Student Scholarship. USTC.

# 📖 Educations
- *2019.09 - 2024.06*, Ph.D. student, Department of Electronic Engineering and Information Science, University of Science and Technology of China.
- *2015.09 - 2019.06*, Bachelor, Department of Electronic Science and Technology, University of Science and Technology of China.

# 💬 Invited Talks

# 💻 Experiences
- *2025.07 - now*, Associate Professor of **School of Computer Science**, **Nanjing University of Information Science and Technology**.
- *2024.07 - 2025.06*, Lecturer of **School of Computer Science**, **Nanjing University of Information Science and Technology**.
- *2023.04 - 2024.02*, Research Intern of **Initi AI (An AIGC startup)**. Under the supervision of Dr. [Chaoyue Wang](https://wang-chaoyue.github.io/).
- *2021.08 - 2023.03*, Research Intern of **JD Explore**. Under the supervision of Dr. [Chaoyue Wang](https://wang-chaoyue.github.io/).
