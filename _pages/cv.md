---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
You can also find my CV here [Li Meng's Curriculum Vitae](../assets/curriculum_vitae.pdf).

Here is the translated version of your content into American English:


### Education

* Ph.D., Control Science and Engineering, Tongji University, 2020 - Present
  * Advisor: [Professor Chen Hong](https://see.tongji.edu.cn/info/1376/10290.htm) 
  * Co-advisor：[Professor Huang Yanjun](https://auto.tongji.edu.cn/info/1146/8712.htm)
* Master's, Control Science and Engineering, Jilin University, 2017 - 2020
  * Advisor: [Professor Gao Jinwu](http://dce.jlu.edu.cn/info/1182/5274.htm)
* Bachelor's, Electrical Engineering and Automation, Changchun University of Science and Technology, 2013 - 2017

### Research Interests
Interpretability in Learning-Based Autonomous Driving Decision-Making

<img src="https://github.com/limeng-1234/limeng-1234.github.io/raw/master/assets/研究内容架构.png" width="800" height="auto">


## Project Experience

### National Key R&D Program: Safe and Trustworthy Human-AI Cooperative Driving System in Open Environments
**Time**: September 2020 - Present  
- **Role**: Core Contributor  
- **Responsibilities**: Development of Explainable Autonomous Driving Decision-Making Algorithms
  - **Feature Attribution Explanation for Autonomous Driving Decisions**: Developed a feature attribution explanation method based on Shapley values in cooperative game theory, incorporating feature attribution with prior knowledge into the autonomous driving decision-making model training, significantly enhancing model performance. Experimental results show that the improved model outperforms the original model by up to 10% in accuracy when noise variance exceeds 0.26.
  
  - **Counterfactual Explanation for Autonomous Driving Decisions**: Proposed a Shapley-value-guided counterfactual explanation optimization method, using Shapley values to quantify feature contributions and optimize counterfactual explanations with targeted feature adjustments. Results indicate that prediction consistency and bias detection improved by 25% and 60%, respectively, demonstrating that the proposed method significantly enhances users' understanding of the model’s decision-making process.

### National Key R&D Program: Key Technologies for Self-Evolving Learning-Based Autonomous Driving Systems
**Time**: September 2022 - Present  
- **Role**: Major Contributor  
- **Responsibilities**: Development of Explainable End-to-End Autonomous Driving Decision-Making Algorithms
  - **End-to-End Autonomous Driving Decision-Making Modeling**: Utilized [Dense Convolutional Networks](https://openaccess.thecvf.com/content_cvpr_2017/html/Huang_Densely_Connected_Convolutional_CVPR_2017_paper.html) and the [BDD-OIA Dataset](https://openaccess.thecvf.com/content_CVPR_2020/html/Xu_Explainable_Object-Induced_Action_Decision_for_Autonomous_Vehicles_CVPR_2020_paper.html) as model structure and data foundation, designing a cross-entropy loss function for model gradient updates.
  - **Semantic-Level Attribution Explanation for End-to-End Decision-Making**: Proposed a semantic-level model decision attribution explanation method, leveraging the deep learning vision model Segment Anything to segment semantic entities in images, thereby constructing a semantic Shapley value model. Evaluated each semantic entity’s contribution to the end-to-end decision-making model, aiding human understanding of the model’s decision process at the semantic level.
  - **Semantic-Level Counterfactual Explanation for End-to-End Decisions**: Based on the semantic Shapley value model and image generation networks, optimized key semantics to generate more representative counterfactual explanation samples.
  
### National Key R&D Program: Key Technologies Research and Platform Development for High-Power Density Fuel Cell Engines
**Time**: January 2018 - December 2020  
- **Role**: Major Contributor  
- **Responsibilities**: Modeling and Decoupling Controller Design for Fuel Cell Nonlinear Systems
  - **Decoupling Control Method Design**: Designed a decoupling control method based on feedback linearization for highly nonlinear and coupled fuel cell intake systems.
  - **State Observation Method Development**: Developed an extended state observer to estimate model mismatch and noise interference, integrating it into the feedback controller.
  - **Control Experiment Platform Establishment**: Established an experimental platform for the fuel cell intake system and deployed control algorithms using a rapid prototyping system (DSpace) to achieve decoupling control of the intake system.

### Dongfeng Motor Corporation Project: Robotaxi Autonomous Driving Technology Development
**Time**: December 2020 - December 2021  
- **Role**: Core Contributor  
- **Responsibilities**: Development and Deployment of Autonomous Driving Planning Algorithms
  - Developed planning and control algorithms for the autonomous driving system.
  - Established a combined virtual and real testing platform for on-road experiments.

[Virtual and Real Testing Platform](https://github.com/limeng-1234/Explanation-system/assets/76480875/aeb61c9a-cab4-4aef-8cbb-1c36a603cd94)

<iframe width="560" height="315" src="https://www.youtube.com/embed/1Ib9VXU_9_E" frameborder="0" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/-k2vmTqKoIg" frameborder="0" allowfullscreen></iframe>

## Skills
* Skill 1: Language Proficiency
  * English: CET-6 (Score: 549)
* Skill 2: Computer Skills
  * Sub-skill 2.1 Programming Languages: Proficient in Python, C++, MATLAB
  * Sub-skill 2.2 Passed National Computer Rank Examination Level 2 (C Language)
* Skill 3: Professional Skills
  * Sub-skill 3.1: Machine Learning and Deep Learning
    Proficient in various machine learning methods, focusing on deep learning and deep reinforcement learning with PyTorch and its interpretability.
  * Sub-skill 3.2: Autonomous Driving Algorithm Development
    Proficient in ROS, familiar with the development of autonomous driving decision-making, planning, and control systems.
    Experienced with autonomous driving simulation software such as Carla and commercial software like Scanner and CarSim.
  * Sub-skill 3.3: Control Algorithms
    Experienced in the design and development of control algorithms, including Model Predictive Control (MPC), PID control, LQR control, and Active Disturbance Rejection Control (ADRC).


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
