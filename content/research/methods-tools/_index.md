---
title: "Methods & tools for semantic change"
summary: "Computational tools, benchmarks, and evaluation frameworks for studying semantic change."
---

I develop computational tools for measuring how word meanings change over time. Rather than treating semantic change as a single change score, my work separates change into interpretable dimensions that can be linked to psychological, linguistic, and cultural theory.

This stream is closest to my basic science contribution: building frameworks, benchmarks, and pipelines that make semantic change research more interpretable and evaluable.

## SIBling

**SIBling** is a multidimensional framework for measuring semantic change across **Sentiment**, **Intensity**, and **Breadth**. It helps distinguish whether words become more positive or negative, more emotionally intense, or broader in contextual use.

Useful for: concept creep, mental health language, stigma, public discourse, and cultural change.

[Paper](/publication/journal-article_2024_acl_sibling/) · [Code](https://github.com/naomibaes/lexical_semantic_change_framework)

## LSC-Eval

**LSC-Eval** is an evaluation framework for testing whether semantic change methods can detect specific kinds of change under controlled conditions. It uses LLM generated diachronic synthetic corpora to introduce targeted changes in Sentiment, Intensity, and Breadth.

Useful for: method evaluation, benchmarking, synthetic diachronic data, and interpretable NLP.

[Paper](/publication/journal-article_2025_acl-findings/) · [Code](https://github.com/naomibaes/LSCD_method_evaluation)

## Sense-level evaluation and tracking

I also work on sense-level resources and pipelines for studying how meanings change within and across word senses, including **SenseRel** and a threshold-calibrated sense tracking pipeline for historical corpora.

Relevant work:

- [SenseRel](/publication/journal-article_2026_acl-main/)
- [Threshold-calibrated sense tracking](/publication/workshop-paper-2026_sense-prevalence/)

## Code, data, and benchmarks

Reusable code, data, benchmarks, and supplementary materials are available on my resources page.

[View resources](/resources/)