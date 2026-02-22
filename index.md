---
layout: splash
title: "Sheikh Samit Muhaimin"
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: 0.35
  overlay_image: /images/header.jpg
excerpt: "PhD Candidate @ Notre Dame — LLM security, robustness & evaluation • VR privacy via network traffic analysis"
intro:
  - excerpt: "I build and evaluate secure, reliable ML systems: adversarial testing for LLMs, RAG robustness benchmarks, and privacy risk analysis in VR/AR networking."
feature_row:
  - image_path: /images/project_vr.jpg
    alt: "VR traffic privacy"
    title: "VR Traffic Privacy"
    excerpt: "Inferring VR apps & in-app activities from encrypted traffic metadata."
    url: /projects/vr-traffic-privacy/
    btn_label: "Read more"
    btn_class: "btn--primary"
  - image_path: /images/project_rag.jpg
    alt: "RAG robustness"
    title: "RAG Robustness Evaluation"
    excerpt: "Stress-testing retrieval noise, source credibility, and hallucination failure modes."
    url: /projects/rag-robustness-evaluation/
    btn_label: "Read more"
    btn_class: "btn--primary"
  - image_path: /images/project_prompt.jpg
    alt: "Prompt injection defense"
    title: "Prompt Injection Defense"
    excerpt: "Automated evaluation + defenses for jailbreak and prompt-injection attacks."
    url: /projects/prompt-injection-defense/
    btn_label: "Read more"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}
