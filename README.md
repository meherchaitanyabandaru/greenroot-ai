# GreenRoot AI

GreenRoot AI is the artificial intelligence platform for GreenRoot.

The goal of GreenRoot AI is to provide intelligent insights, automation, forecasting, search, and decision support for nursery businesses.

---

## Overview

GreenRoot AI is not part of the core dispatch platform.

It operates as a separate service and consumes data from:

* GreenRoot API
* Dispatch Data
* Nursery Data
* Driver Data
* Trip Data
* Customer Data

---

## Mission

Transform nursery operations using Artificial Intelligence.

GreenRoot AI helps nursery owners:

* Make better business decisions
* Improve dispatch efficiency
* Forecast demand
* Discover customers
* Automate routine tasks

---

## Technology Stack

### Language

Python

### Framework

FastAPI

### AI Frameworks

Future Evaluation:

* LangChain
* LangGraph
* CrewAI

### LLM Providers

Future Options:

* OpenAI
* Anthropic
* AWS Bedrock
* Google Gemini

### Vector Database

Future Options:

* pgvector
* Pinecone
* Weaviate

---

## Architecture

```text
GreenRoot Mobile
        ↓
GreenRoot API
        ↓
GreenRoot AI
        ↓
LLM Provider
```

---

## Planned Modules

### AI Search

Examples:

* Find nurseries selling Ashoka plants
* Find nurseries near Hyderabad
* Search historical dispatches

---

### AI Assistant

Examples:

* Show pending deliveries
* Show active trips
* Show top customers

---

### Business Analytics

Examples:

* Monthly growth analysis
* Dispatch trends
* Customer insights

---

### Demand Forecasting

Examples:

* Predict seasonal demand
* Predict plant shortages
* Predict high demand regions

---

### Recommendation Engine

Examples:

* Recommended customers
* Recommended plants
* Recommended routes

---

### Marketplace Intelligence

Examples:

* Popular plants
* Regional demand
* Nursery rankings

---

## Repository Structure

```text
greenroot-ai

app/

├── search/
├── chat/
├── analytics/
├── forecasting/
├── recommendations/

docs/

README.md
```

---

## Development Phases

### Phase 1

Not Started

Focus on GreenRoot Core Platform.

---

### Phase 2

AI Search

Natural language search over nursery data.

---

### Phase 3

GreenRoot Copilot

Business assistant for nursery owners.

---

### Phase 4

Forecasting & Recommendations

Advanced analytics and demand prediction.

---

## Current Status

Planned

No production code yet.

Repository created for future roadmap and architecture planning.

---

## Product Vision

GreenRoot AI will become the intelligence layer of the GreenRoot ecosystem, helping nursery businesses make faster and smarter decisions using data and artificial intelligence.
