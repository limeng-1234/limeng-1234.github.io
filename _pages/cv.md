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

Education
======
* Ph.D. in Control Science and Engineering, Tongji University, expected 2024
  * Advisor: [Professor Chen Hong](https://see.tongji.edu.cn/info/1376/10290.htm)
* M.S. in Control Science and Engineering, Jilin University, 2017-2020
  * Advisor: [Professor Gao Jinwu](http://dce.jlu.edu.cn/info/1182/5274.htm)
* B.S. in Electrical Engineering and Automation, Changchun University of Science and Technology, 2013-2017

## Project Experience  
  
### National Key Research and Development Program Subproject: Trustworthy and Explainable Human-Machine Collaborative Intelligent Decision-Making and Online Evaluation for Autonomous Driving  
**Duration**: September 2020 - Present  
- **Role**: Key Contributor  
- **Responsibilities**:  
  - Developed explainable autonomous driving decision algorithms to enhance the credibility of data-driven autonomous driving models.  
  - Established a feature attribution explanation method based on Shapley values from cooperative game theory to interpret model decision processes.  
  - Integrated feature attribution methods with prior knowledge into model training to improve model performance.  
  - Proposed a semantic-level model decision attribution explanation method for end-to-end autonomous driving decision models.  
  - Introduced an expected integral discrete gradient method for model reliability verification, significantly improving computational efficiency.  
  
### National Key Research and Development Program Subproject: Key Technologies for Self-Evolving Learning-Based Autonomous Driving Systems  
**Duration**: September 2022 - Present  
- **Role**: Key Contributor  
- **Responsibilities**:  
  - Developed an explainable vehicle intention prediction algorithm to improve the reliability of data-driven vehicle intention models.  
  - Proposed a counterfactual model diagnosis method guided by feature attribution to analyze model decision mechanisms and diagnose potential defects.  
  - Applied the method to diagnose various machine learning-based lane change intention models such as XGBoost, LSTM, and Attention models.  
  
### National Key Research and Development Program Subproject: Research and Platform Development of Key Technologies for High-Power-Density Fuel Cell Engines  
**Duration**: January 2018 - December 2020  
- **Role**: Key Contributor  
- **Responsibilities**:  
  - Designed a decoupling control method based on feedback linearization for the highly nonlinear and coupled fuel cell air intake system.  
  - Implemented an extended state observer to estimate model mismatches and noise disturbances, integrated into the feedback controller.  
  - Built an experimental platform for the fuel cell air intake system and implemented robust decoupling control algorithms using DSpace real-time control.  
  
### Dongfeng Motor Corporation Project: Robotaxi Autonomous Vehicle Technology Development  
**Duration**: December 2020 - December 2021  
- **Role**: Key Contributor  
- **Responsibilities**:  
  - Developed autonomous driving system planning and control algorithms.  
  - Established a virtual-real combined testing platform and conducted real-vehicle experiments.
  
Skills
======
* Skill 1: Foreign Language Proficiency
  * English: CET-6 (Score: 549)
* Skill 2: Computer Skills

  * Sub-skill 2.1 Programming Languages: Proficient in Python, Proficient in C++, Proficient in MATLAB
  * Sub-skill 2.2 National Computer Rank Examination Passed Level 2 (C Language)
* Skill 3: Professional Skills

  * Sub-skill 3.1: Machine Learning and Deep Learning
  Proficient in various machine learning methods, with a focus on deep learning and deep reinforcement learning under the PyTorch framework, as well as interpretability.
  * Sub-skill 3.2: Autonomous Driving Development
  Proficient in ROS and familiar with the development of autonomous driving decision-making, planning, and control systems.
  Experienced in using autonomous driving open-source simulation software such as Carla and commercial software like Scanner and CarSim.
  * Sub-skill 3.3: Control Algorithms
  Proficient in developing and testing control algorithms such as Model Predictive Control (MPC), PID, and Active Disturbance Rejection Control (ADRC).

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
