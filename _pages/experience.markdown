---
layout: default
title: Experience
permalink: /experience/
---

# Experience

## Microsoft

**Senior Applied Scientist** — Redmond, WA (Mar 2026 – Present)

- Design and develop AI agents for enterprise business workflows
- Reinforcement learning to improve model reliability and task performance
- Collaborate across research, engineering, and product to translate research into production systems

---

## Amazon Alexa

**Applied Scientist** — Bellevue, WA (Aug 2020 – Mar 2026)

### Continued Pre-Training of Alexa Core LLM
- Developed continued pre-training pipeline to embed domain knowledge into the core LLM powering Alexa+
- Improved system efficiency and user experience by reducing prompt length and minimizing inference latency
- Collaborated with several internal cross-functional domain teams to create high quality Alexa pre-training dataset

### Post-Training of Alexa Core LLM
- Served as the release owner of the Supervised Fine-Tuning (SFT) stage for multiple versions of the core Alexa LLM
- Curated high-quality SFT dataset by collaborating with diverse domain teams to gather data for a range of applications, including API invocation, response generation, and complex multi-turn instruction-following
- Designed and executed comprehensive ablation studies to optimize the data mix for each model release

### Fast Routing Model via Knowledge Distillation
- Developed a fast router model to address the high latency of expert selection in Alexa+
- Significantly reduced user-perceived latency by moving from a large, slow LLM to an efficient distilled model
- Conducted extensive experiments with model architectures to ensure fast inference with high routing accuracy

### Data Labeling Pipeline for Alexa Content Moderation
- Developed a comprehensive content moderation system for Alexa, scanning 100% of traffic for inappropriate content
- Developed a multi-stage filtering pipeline, utilizing efficient, high-recall models for initial screening and more computationally intensive LLMs for complex cases in later stages
- Fine-tuned 7B LLM for a variety of content moderation tasks, including flagging inappropriate content, categorizing violation types, and generating detailed explanations for decision-making

### Enhancing LLM Safety and Helpfulness
- Implemented a customer query classifier to identify sensitive topics in multi-turn Alexa LLM interactions
- Employed knowledge distillation to train production-ready, small-scale model from 7B LLM, enabling efficient real-time inference
- Maintained model precision above 90% on live traffic by iteratively deploying updated models to account for evolving data distributions
- Employed weight interpolation technique to reduce the rate of missed detections below 5% at 90% precision
