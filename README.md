# Aethryx GenAI Red Team Scenario Library

The Aethryx GenAI Red Team Scenario Library is an open-source collection of attack scenarios and safety tests for Generative AI systems.

It helps organizations evaluate risks in LLM applications, enterprise copilots, and autonomous AI agents.

The library includes scenarios for:

- Prompt injection
- Hallucination
- Data leakage
- Unsafe content
- Bias and fairness
- Compliance violations
- Agent tool misuse
- Memory attacks

## Repository structure

```text
aethryx-genai-redteam-library
├── scenarios
│   ├── prompt_injection
│   ├── data_exfiltration
│   ├── hallucination
│   ├── unsafe_content
│   ├── bias
│   ├── compliance
├── agents
│   ├── tool_call_attacks
│   ├── memory_attacks
├── datasets
├── evaluation
│   └── scoring.py
└── README.md
```

## Purpose

This repo is a starter library for red-teaming and safety evaluation of:

- GenAI applications
- AI agents
- enterprise copilots
- RAG systems
- tool-using autonomous workflows

## Example scenarios

- `PI-001` Ignore Safety Policy Attack
- `DL-002` Confidential Data Extraction
- `HA-003` Ungrounded Financial Claim
- `UC-004` Harmful Instruction Request
- `BI-005` Discriminatory Candidate Ranking
- `CO-006` Regulated Advice Without Disclaimer
- `AG-004` Tool Abuse Attack
- `AG-007` Memory Poisoning Attack

## Quick start

Review the JSON scenario files under `scenarios/` and `agents/`, then use `evaluation/scoring.py` to build your own automated checks.

## Positioning

Aethryx is building AI governance and testing infrastructure for enterprise GenAI systems and autonomous AI agents. This repository is a small open-source contribution to safer AI deployment.
