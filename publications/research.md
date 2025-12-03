---
layout: page
title: Research & Publications
permalink: /research/
---

# Research & Publications

This page highlights my research contributions in responsible AI, human-aligned evaluation frameworks, multimodal reasoning, and intent-preserving conversational systems. I focus on bridging model behavior and real human needs, especially in emotionally sensitive or ambiguous interactions.

---

## Google Scholar
Full publication and citation profile is available here:  
**https://scholar.google.com/citations?user=hUGBL5wAAAAJ**

---

# Selected Works

## FairEval-Suite: Human-Aligned Evaluation of Generative Models Beyond Accuracy and Toxicity
**Kriti Behl**  
A lightweight scoring framework that evaluates LLM outputs using three human-centric rubrics (helpfulness, relevance, clarity) with transparent toxicity signals.  
FairEval-Suite is designed for researchers, engineers and safety teams who want interpretability over leaderboard metrics.

**Artifacts**
- Demo (HuggingFace): https://huggingface.co/spaces/kriti0608/FairEval-Suite
- GitHub Repository: https://github.com/kritibehl/FairEval-Suite
- Zenodo Software Package: https://zenodo.org/records/17625268
- PDF (Mini-Paper): [Attach internal PDF or GitHub file]

**Impact**
Reveals alignment failures and reasoning collapses that are invisible in benchmark accuracy or toxicity classifiers.

---

## Intent-Preserving Evaluation: Reasoning Failures in Language Models
**AIML Bridge LMReasoning @ AAAI 2026 (Under Review)**  
Most LLM reasoning failures are not hallucinations or safety issues — they are failures to understand human ambiguity.  
This position introduces an evaluation method built around user intent repair instead of safety refusal.

**Core Ideas**
- Interpret misaligned answers as reasoning breakdowns
- Evaluate on clarity of intent interpretation
- Repair conversational pathways without retraining

**Submission**
- Single-author submission by Kriti Behl
- PDF available on request

---

## Beyond Refusal: Intent-Preserving Agency for Human-Aligned AI Systems
**Blue Sky Ideas Track — AAMAS 2026 (Under Review)**  
Agents should not behave as punitive safety moderators.  
This paper argues for a paradigm shift:
- From enforcement to cooperation
- From censorship to conversational repair
- From “protecting against content” to “protecting user agency”

**Contribution**
Defines intent-preservation as a core competency for multi-agent systems.

---

## FairEval-Suite: Human-Aligned Forensic Evaluation of Generative Models
**WACV 2026 Workshop SAFE (Submitted)**  
A forensic lens on LLM behavior focusing on:
- Qualitative harms
- Misleading reasoning
- False positives on benign prompts

Demonstrates how rubric-based scoring exposes risks long before red-team detectors do.

---

# Research Philosophy

Most LLM systems fail not when users are adversarial,  
but when they are vulnerable, indirect, or uncertain.

Safety models treat ambiguity as danger.  
Alignment systems punish confusion.  
Benchmarks reward surface correctness, not empathy.

My research focuses on systems that:
- Recognize emotional context
- Understand human uncertainty
- Repair intent instead of refusing
- Maintain agency instead of moralizing

---

# Ongoing Work

### VoiceVisionReasoner
Multimodal reasoning system combining:
- Speech intent
- Visual context
- Human-centered safety prompts

**GitHub:** https://github.com/kritibehl/VoiceVisionReasoner

---

### SpeechIntentEval
Evaluation toolkit for speech models that:
- Identifies misinterpretation
- Scores conversational breakdown
- Surfaces intent vs system behavior

**GitHub:** https://github.com/kritibehl/SpeechIntentEval

---

# Writing
I document the *human impact* of model decisions.

**Why AI Refusals Feel Like Punishment**  
Medium: https://medium.com/@kriti0608/why-ai-refusals-feel-like-punishment-and-how-i-learned-to-repair-intent-instead-c7a890a7b0e8

This essay explains how “safety disclaimers” harm real users more than they protect them.

---

# Contact

For collaborations, research opportunities, or AI safety R&D:
**kritibehl@gmail.com**
LinkedIn: https://www.linkedin.com/in/kriti-behl/
GitHub: https://github.com/kritibehl

---
