---
title:          "MedTsLLM: Medical Time Series Analysis Using Multimodal LLMs"
date:           2025-10-16 00:01:00 +0800
selected:       true
pub:            "IEEE Journal of Biomedical and Health Informatics"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  Traditional machine learning approaches for biomedical time series analysis face fundamental limitations when integrating the heterogeneous data types essential for comprehensive clinical understanding. Physiological signals must be interpreted within rich clinical contexts that include patient history, current medications, and treatment protocols-information typically stored as unstructured text that conventional time series models cannot effectively utilize. We propose MedTsLLM, a multimodal model that aims to address this critical gap by integrating numerical physiological signals with natural language clinical information through large language models (LLMs). Our framework incorporates patch reprogramming for time series-LLM alignment and introduces two key innovations: novel covariate handling strategies that capture complex physiological relationships, and contextual prompting mechanisms that incorporate patient-specific information. MedTsLLM addresses four clinically significant tasks within a unified architecture: semantic segmentation, boundary detection, anomaly detection, and classification. Through comprehensive evaluation across diverse medical domains, including ECG analysis, respiratory monitoring, and cardiac arrhythmia detection, our approach consistently outperforms state-of-the-art baselines across all tasks and datasets. These results demonstrate the transformative potential of multimodal LLMs for biomedical signal analysis, enabling clinicians to extract deeper insights from physiological data while leveraging comprehensive clinical context to enhance diagnostic accuracy, patient monitoring, and personalized treatment decisions.
# cover:          /assets/images/covers/cover3.jpg
authors:
  - Nimeesha Chan
  - Felix Parker
  - Chi Zhang
  - William Bennett
  - Mung Yao Jia
  - James Fackler
  - Kimia Ghobadi
links:
  Code: https://github.com/flixpar/med-ts-llm
---
