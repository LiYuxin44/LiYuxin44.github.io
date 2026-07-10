---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Summary
======
PhD candidate at Nanyang Technological University specializing in multimodal foundation
models, audio-language modeling, and post-training (SFT / RLVR / GRPO / DPO). Core
contributor to Step-Audio 2 / R1 / R1.5 and Step-Audio 2.5, with experience spanning data
construction, evaluation, and research-to-system iteration.

Education
======
* Ph.D., College of Computing and Data Science, **Nanyang Technological University**, Aug 2024 – Present (GPA: 4.67/5.0) — advised by Prof. Cuntai Guan and Prof. Eng Siong Chng
* M.Sc., Knowledge, Information and Data Science, **University College London**, Sep 2022 – Dec 2023 (GPA: 4.0/4.0)
* B.Mgmt., Information Management and Information System, **Central South University**, Sep 2018 – Jun 2022 (GPA: 3.6/4.0)

Experience
======
* **Audio LLM Research Intern**, Anuttacon (Jul 2026 – Present)
  * Research on audio large language models.

* **Research Scientist Intern**, StepFun (Apr 2025 – Jun 2026)
  * *Step-Audio 2* (core author): designed end-to-end pipelines spanning multimodal CoT data construction, SFT, GRPO/DPO optimization, reward and verifier design, iterative model analysis, and benchmarking across audio reasoning, ASR, paralinguistics, and dialogue tasks.
  * *Step-Audio-R1* (core author): co-developed 32B audio reasoning models; owned the RL training (RLVR with verified rewards across math, code, logic, and audio tasks) and the iterative self-distillation data pipeline that power Modality-Grounded Reasoning Distillation (MGRD), keeping long chain-of-thought reasoning grounded in raw acoustic evidence.
  * Contributor to *Step-Audio-R1.5* and *Step-Audio 2.5 Realtime*.
  * Led simultaneous interpretation training workstreams, covering data synthesis, training recipes, and benchmark design.

* **Research Intern**, Speech Lab, Nanyang Technological University (Dec 2023 – Jun 2024)
  * Developed speech-based depression detection systems using self-supervised representations (HuBERT and WavLM).
  * Fine-tuned Qwen-7B and LLaMA-2-13B with LoRA for speech-derived emotion classification and interpretable paralinguistic reasoning.

* **Research Assistant**, University College London (Jan 2023 – Jun 2023)
  * Built multimodal medical classification and speech emotion recognition pipelines using clinical narratives, acoustic features, and self-supervised representations.

* **Research Assistant**, Central South University (Apr 2021 – Dec 2022)
  * Built Transformer-based NER and hybrid information extraction pipelines for Chinese corpora, with large-scale evaluation on open-access datasets.

Research Interests
======
* Multimodal foundation models & audio-language modeling
* Post-training for LLMs / audio LLMs (SFT, RLVR, GRPO, DPO)
* Speech recognition, paralinguistics, and full-duplex spoken dialogue
* Affective computing and mental-health detection from speech

Skills
======
* **Post-training & RL:** SFT, RLVR, GRPO, DPO, reward/verifier design, self-distillation
* **Modeling:** multimodal foundation models, audio-language models, ASR, LoRA fine-tuning
* **Representations:** HuBERT, WavLM, self-supervised speech representations
* **Programming & tooling:** Python, PyTorch, large-scale training & evaluation pipelines

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
