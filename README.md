# AI Inference Platform

A hands-on project for building and evolving an LLM inference platform from local model serving to Kubernetes, observability, autoscaling, resilience, and GPU-backed cloud validation.

The goal is not only to deploy inference workloads, but to understand and measure the engineering trade-offs involved in operating them.

## Milestones

### Milestone 01 — Local LLM Serving

Serve a small language model locally through an inference API and establish the simplest working baseline.

### Milestone 02 — Kubernetes Deployment

Move the inference workload into Kubernetes and define the basic deployment and runtime configuration.

### Milestone 03 — Observability

Introduce inference-focused metrics and monitoring to understand runtime behavior.

### Milestone 04 — Load Testing & Baseline

Measure latency, throughput, concurrency, and resource utilization under controlled load.

### Milestone 05 — Intelligent Autoscaling

Scale inference workloads using signals that reflect actual inference demand rather than relying only on generic infrastructure metrics.

### Milestone 06 — Scale-to-Zero

Explore idle-cost reduction and the trade-off between GPU availability and cold-start latency.

### Milestone 07 — Failure & Recovery

Introduce controlled failures and evaluate how the platform detects, handles, and recovers from them.

### Milestone 08 — Cloud GPU Validation

Run targeted experiments on GPU-backed cloud infrastructure and compare the results with the local development baseline.

## Current Status

Repository bootstrap complete.

Next:

**Milestone 01 — Local LLM Serving**