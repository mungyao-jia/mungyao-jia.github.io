---
title:          "AutoToM: Scaling Model-based Mental Inference via Automated Agent Modeling"
date:           2025-09-18 00:01:00 +0800
selected:       true
pub:            "NeurIPS 2025"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  Theory of Mind (ToM), the ability to understand people’s minds based on their behavior, is key to developing socially intelligent agents. Current approaches to ToM reasoning either rely on prompting Large Language Models (LLMs), which are prone to systematic errors, or use handcrafted, rigid agent models for model-based inference, which are more robust but fail to generalize across domains. In this work, we introduce AutoToM, an automated agent modeling method for scalable, robust, and interpretable mental inference. Given a ToM problem, AutoToM first proposes an initial agent model and then performs automated Bayesian inverse planning based on this model, leveraging an LLM backend. Guided by inference uncertainty, it iteratively refines the model by introducing additional mental variables and/or incorporating more timesteps in the context. Across five diverse benchmarks, AutoToM outperforms existing ToM methods and even large reasoning models. Additionally, we show that AutoToM can produce human-like confidence estimates and enable online mental inference for embodied decision-making.
cover:          /assets/images/covers/cover_autotom.png
authors:
  - Zhining Zhang* 
  - Chuanyang Jin*
  - <b> Mung Yao Jia </b> *
  - Shunchi Zhang*
  - Tianmin Shu
links:
  Project Page: https://chuanyangjin.com/AutoToM/ 
  Code: https://github.com/SCAI-JHU/AutoToM
---
