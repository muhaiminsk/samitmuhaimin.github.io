---
title: "Automated Evaluation and Defense Against Prompt Injection Attacks"
collection: portfolio
permalink: /projects/prompt-injection-defense/
---

## Overview

This project focuses on **prompt injection and jailbreak attacks** against large language models, developing **automated evaluation frameworks and defenses** that improve safety without retraining the model.

---

## Problem

LLMs are vulnerable to:
- Prompt injection via external content
- Jailbreaks that bypass safety policies
- Context manipulation in RAG pipelines

Most defenses require retraining or manual rule updates, limiting scalability.

---

## Approach

- Built automated adversarial test suites covering:
  - Jailbreak prompts
  - Instruction hijacking
  - Context poisoning
- Developed defense mechanisms using:
  - In-context learning
  - Literature-aware filtering
  - Response consistency checks
- Evaluated defenses across multiple task domains

---

## Results

- Significant reduction in successful jailbreaks
- Improved response consistency without degrading task performance
- Defenses generalize across prompts and domains
- No model retraining required

---

## Contributions

- Automated evaluation framework for LLM safety testing
- Scalable, training-free defense strategies
- Empirical analysis of safety–performance trade-offs

---

## Tools & Methods

- Hugging Face Transformers
- LangChain
- Python-based evaluation pipelines
- Human-in-the-loop validation

---

## Publication

Accepted at **IEEE TPS 2025**  
*“Helping Large Language Models Protect Themselves: An Enhanced Filtering and Summarization System”*
