---
layout: page
title: Projects
permalink: /projects/
---

# Projects

Below is a selection of my most important technical projects, each centered around responsible AI, multimodal reasoning, and human-aligned evaluation. These projects are original work, fully implemented, and publicly available.

---

## FairEval-Suite
**Human-Aligned Evaluation of Generative Models Beyond Accuracy and Toxicity**

Traditional benchmarks measure accuracy or toxicity flags, but fail to capture how humans actually experience model responses.  
FairEval-Suite introduces three interpretable rubric dimensions:

- Helpfulness
- Relevance
- Clarity

paired with lightweight toxicity signals.

**Key Features**

- Produces continuous score ∈ [0,1]
- Transparent breakdown for interpretability
- HuggingFace space demo + Python package
- Benchmark comparison across GPT-4o, Claude, DeepSeek

**Links**
- GitHub: https://github.com/kritibehl/FairEval-Suite
- Demo (HuggingFace): https://huggingface.co/spaces/kriti0608/FairEval-Suite
- Zenodo: https://zenodo.org/records/17625268

---

## VoiceVisionReasoner
**Multimodal Reasoning with Speech + Visual + Human Context**

Modern LLMs treat modalities in isolation:
- Speech → transcription → answer
- Image → caption → answer

This separation causes hallucinations, moralizing, and failures of safety, especially for emotionally sensitive input.

VoiceVisionReasoner unifies:
- Speech transcription
- Visual description
- Joint reasoning
- Context-aware checks

It aims to interpret human signals, not punish confusion.

**Links**
- GitHub: https://github.com/kritibehl/VoiceVisionReasoner

---

## SpeechIntentEval
**A Dataset and Evaluation Tool for Detecting Misinterpretation of Human Intent in Speech-Driven Systems**

Many refusal events are not adversarial—they result from misaligned assumptions about user intent.  
SpeechIntentEval analyses model behaviors when users speak plainly, indirectly, or emotionally.

**Highlights**
- Measures alignment failures beyond toxicity
- Designed for conversational assistants
- Built for transparency and reproducibility

**Links**
- GitHub: https://github.com/kritibehl/SpeechIntentEval

---

## JailBreakDefense (Prototype v0.1)
**Lightweight Detection + Repair Framework for Jailbreak Prompts**

Instead of blocking generative models entirely, JailBreakDefense:
- Detects jailbreak attempts
- Repairs and preserves original user intent
- Avoids censorship-style refusals or “punishment responses”

**Approach**
- Lightweight detectors
- Context window repair
- Modular, model-agnostic pipeline

**Links**
- Zenodo (Software): https://zenodo.org/records/XXXXXX
- GitHub: https://github.com/kritibehl/JailBreakDefense

---

## Additional Work
Beyond the listed flagship projects, I continually experiment with:
- Evaluation frameworks
- Conversational safety analysis
- Reasoning under ambiguity
- User-centric alignment methods

If you are interested in collaborations, research internships, or safety-driven R&D roles, please reach out.

---
