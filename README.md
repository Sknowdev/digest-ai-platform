# digest-ai-platform
AI-assisted media production platform for scalable short-form video creation.

# Digest AI Platform

Digest AI is an AI-assisted media production platform designed to help
creators and businesses transform long-form information into structured,
short-form video content efficiently and at scale.

The system focuses on **workflow orchestration, reliability, and cost-aware
AI usage**, rather than raw content automation.

---

## Problem

Producing consistent, high-quality short-form video content requires:
- Script writing
- Voice production
- Visual sourcing or generation
- Media assembly
- Operational monitoring

Most creators rely on fragmented tools that do not scale or provide
operational visibility.

---

## Solution

Digest AI provides a unified engine that orchestrates:
- AI-assisted script generation
- Neural voice synthesis
- Generative or stock-based visual production
- Automated media assembly
- Real-time system monitoring via a dashboard

The platform is designed with **fallback-first reliability**, ensuring content
can be produced even when individual AI services are unavailable.

---

## Target Users

Digest AI is designed for:
- Independent media creators
- Small studios and production teams
- Agencies repurposing long-form content
- Businesses that need scalable video production pipelines

---

## Core Capabilities

### AI Orchestration
- Large Language Models for structured script generation
- Neural Text-to-Speech for narration
- Generative video engines with intelligent fallback
- FFmpeg-based media assembly

### Reliability & Scale
- Multi-stage fallback pipeline (AI → alternate AI → stock media)
- Intelligent CPU/GPU job scheduling
- Thermal and memory protection
- Zero-failure design philosophy

### Operations
- Live dashboard for job status and system health
- Queue-based processing
- Cost-aware execution planning

---

## Architecture Overview

- LLMs: Google Gemini (primary)
- Voice: Google Cloud Text-to-Speech
- Media Assembly: FFmpeg
- Orchestration: API-driven workflow engine
- Storage: Object storage for generated assets
- Execution: Containerized services with scalable workers

Core implementation remains private.

---

## Cloud Usage Intent

Digest AI is designed to run on cloud infrastructure to support:
- AI inference workloads
- Media processing pipelines
- Scalable job execution
- Object storage for generated assets
- Monitoring and observability

Cloud credits will be used to deploy, test, and optimize production workloads.

---

## Status

- Active development
- Private core codebase
- Internal dashboard operational
- Preparing for limited pilot usage
