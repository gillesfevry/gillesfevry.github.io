---
title: "SurvTreeSHAP(t): scalable explanation method for tree-based survival models"
collection: publications
category: papers
permalink: /publication/2025-08-16-survtreeshap
excerpt: 'Lucas Ducrot, <b>Gilles Fevry</b>, Clément Dano, Raphaël Texier, Juliette Murris, Sandrine Katsahian'
date: 2025-08-16
venue: 'Workshop on Explainable Artificial Intelligence (XAI), IJCAI 2025, Montreal'
paperurl: 'https://hal.science/hal-05108033/file/SurvTreeSHAP___scalable_explanation_method_for_tree_based_survival_models.pdf'
citation: 'Ducrot, L., Fevry, G., Dano, C., Texier, R., Murris, J., & Katsahian, S. (2025). &quot;SurvTreeSHAP(t): scalable explanation method for tree-based survival models.&quot; <i>Workshop on Explainable Artificial Intelligence (XAI), IJCAI 2025</i>, Montreal, Canada.'
---

Tree-based survival models such as Random Survival Forests and Gradient Boosted Survival Trees offer state-of-the-art predictive performance for time-to-event data. However, their lack of interpretability limits their use in domains like healthcare, where understanding individual risk is crucial. SHAP method and a survival-specific extension SurvSHAP(t), have emerged as promising tools for feature attribution. Yet, their applicability remains limited in high-dimensional settings due to computational inefficiencies. TreeSHAP allows scalable explanation for tree-based models but does not support survival setting. We present SurvTreeSHAP(t), a scalable interpretability method tailored to tree-based survival models. Combining TreeSHAP and SurvSHAP(t), our approach allows a scalable computation time. Feature contributions are computed efficiently and aggregated over time to provide meaningful, individual and global insights into survival predictions. Through simulations and real-world clinical data, we show that our method produces reliable explanations while maintaining scalability across hundreds of variables. This work enables interpretable and efficient survival modeling at scale, with practical implications for clinical decision-making and large-scale biomedical applications.

[HAL page](https://hal.science/hal-05108033)
