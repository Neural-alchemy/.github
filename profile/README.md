# Neuralchemy

<p align="center">
  <strong>Secure AI Infrastructure for Long-Term Systems</strong>
</p>

<p align="center">
  Research • Safety • Reasoning • Developer Infrastructure
</p>

<p align="center">
  <a href="https://www.neuralchemy.in">Website</a> •
  <a href="https://huggingface.co/neuralchemy">Hugging Face</a> •
  <a href="https://github.com/openclay-ai">OpenClay Org</a>
</p>

---

## Overview

Neuralchemy is a research and engineering organization building secure, reliable, and production-grade infrastructure for modern AI systems.

We focus on the parts of AI that become critical when models move beyond chat and begin executing tools, making decisions, and interacting with external systems.

Our work centers on:

- secure execution
- prompt attack resistance
- reasoning reliability
- evaluation systems
- developer-first runtime infrastructure

---

## Why This Exists

Current AI systems are increasingly capable but still fragile in production environments.

The hardest problems are no longer only model quality.

They are infrastructure problems:

- How do you safely execute model outputs?
- How do you isolate untrusted instructions?
- How do you detect adversarial prompts?
- How do you evaluate reasoning under failure conditions?
- How do you build systems that remain maintainable over years?

Neuralchemy exists to solve these problems through practical, long-horizon engineering.

---

# Core Research Areas

## AI Security

Defensive systems for real-world model deployment:

- prompt injection defense
- adversarial instruction filtering
- zero-trust execution pipelines
- policy-constrained tool invocation

---

## Reasoning Systems

Infrastructure for measuring and improving:

- structured reasoning quality
- consistency under long context
- task reliability
- evaluation under adversarial inputs

---

## Developer Infrastructure

Production-first tooling designed for:

- explicit control
- predictable execution
- low abstraction overhead
- operational clarity

---

# Projects

## OpenClay

OpenClay

Secure First → Execute Second

Universal zero-trust execution framework for LLM agents.

OpenClay treats every model action as untrusted until explicitly validated.

### Core Principles

- zero-trust runtime
- isolated tool execution
- explicit permission boundaries
- deterministic execution paths
- secure multi-step orchestration

### Why OpenClay Matters

Most agent systems fail because they assume model output is trustworthy.

OpenClay assumes the opposite.

### Repository

https://github.com/openclay-ai/openclay

---

## Prompt Injection Detection Model

prompt-injection-deberta

DeBERTa-based security classifier for prompt injection detection.

### Designed For

- prompt risk scoring
- adversarial instruction classification
- defensive filtering pipelines

### Model Link

https://huggingface.co/neuralchemy/prompt-injection-deberta

---

## Prompt Injection Dataset

Prompt-injection-dataset

Security-oriented benchmark dataset for prompt injection research.

### Dataset Size

- 6,000 curated samples
- 15,000 augmented samples

### Use Cases

- model training
- benchmark evaluation
- defense experiments

### Dataset Link

https://huggingface.co/datasets/neuralchemy/Prompt-injection-dataset

---

# Architecture Direction

Neuralchemy systems are built around one core principle:

> unsafe execution must never be the default

This means:

- models propose
- infrastructure verifies
- execution happens only after control checks

---

# Engineering Philosophy

We deliberately avoid unnecessary complexity.

We prefer:

- explicit systems over hidden abstraction
- stable interfaces over fragile novelty
- long maintenance horizons over short hype cycles

---

# Current Focus

Active work includes:

- zero-trust agent runtimes
- prompt attack resilience
- secure tool invocation
- reasoning evaluation infrastructure
- production-safe model execution

---

# Contributing

We welcome contributors working in:

- AI safety
- systems engineering
- runtime design
- evaluation infrastructure
- security tooling

Before large changes:

- open an issue
- describe the design
- explain operational impact

---

# Long-Term Goal

Build infrastructure that still remains understandable, secure, and maintainable years after deployment.

That standard is higher than model performance alone.

It is the standard required for real AI systems.

---

# External Links

Website: https://www.neuralchemy.in

Hugging Face: https://huggingface.co/neuralchemy

OpenClay Org: https://github.com/openclay-ai