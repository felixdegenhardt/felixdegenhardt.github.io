---
layout: page
title: Die Küchenschlacht Analysis
description: Analyzing gender patterns in German cooking show using automated NLP pipeline
importance: 1
category: research
github: felixdegenhardt/kuechenschlacht  
---

Automated data extraction pipeline analyzing gender patterns in 200+ episodes of the German cooking show "Die Küchenschlacht" (The Kitchen Battle).

## Summary

- **Goal**: Test whether juror/candidate gender affects competition outcomes
- **Method**: MLX Whisper transcription → GPT-4 extraction → Statistical analysis
- **Sample**: 200+ episodes, 1000+ candidates (2023-2025)

## Key Findings

- No evidence of gender bias (female jurors don't favor female candidates)
- Tasting order matters: Earlier positions have advantage
- Effect weaker for female jurors

## Tech Stack

Python • MLX Whisper • OpenAI GPT-4 • Pandas • Statsmodels

[View full analysis and code on GitHub](https://github.com/felixdegenhardt/kuechenschlacht)
