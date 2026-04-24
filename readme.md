# LLM Movie Review Sentiment

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
