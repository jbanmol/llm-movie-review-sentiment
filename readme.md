# LLM Movie Review Sentiment

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-LLM-4285F4?logo=google&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-Structured_Output-7C3AED)
![Sentiment](https://img.shields.io/badge/Sentiment-Classification-0EA5E9)

Prompt-tested LLM sentiment classifier for movie reviews with single-review and batch-processing workflows.

## What This Demonstrates

- Prompt engineering for structured sentiment outputs
- Single-item and batch inference workflows
- Confidence and evidence extraction from model responses
- Lightweight Python project structure for LLM-powered classification

## Use Case

The tool classifies reviews as positive, negative, or neutral, while also returning supporting evidence from the review text. It is designed as a compact applied-LLM example rather than a large ML training project.

## Suggested Workflow

```text
Movie review text
  -> prompt template
  -> Gemini model call
  -> structured sentiment label
  -> confidence and evidence fields
  -> CSV or CLI output
```

## Tech Stack

Python, Gemini API, prompt templates, CSV batch processing.

## Portfolio Role

This repo is a small but useful companion to the larger ML projects: it shows pragmatic LLM application design and output structuring.
