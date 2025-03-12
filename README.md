# LangGraph Projects Overview

## 1. Blog Generation from User Topics
This project leverages LangGraph to automate blog creation using open-source Large Language Models (LLMs). It structures blog generation into sequential steps:
- Initial content creation
- Iterative refinement
- Quality checking

Integrated LangSmith tracing ensures effective debugging and content quality assurance.

## 2. AI Code Review Peer Reviewer
This tool helps developers by automatically reviewing their code using a structured workflow with LangGraph. Steps include:
- Code submission and language identification
- Structural analysis
- Issue detection (bugs, performance issues, style)
- Suggesting improvements
- Comprehensive review generation with scoring

Uses LangSmith for monitoring and optimization.

![LangGraph Workflow for Automated Code Peer Review](code-review-workflow.png)

## 3. Technical Documentation Orchestrator & Synthesizer
This application creates technical documentation from high-level requirements through:
- Workflow orchestration (planning, content generation, reviewing, refining)
- Synthesizing detailed documentation sections, including code examples
- Iterative content refinement based on feedback (up to two iterations)

Utilizes Grok api to access open ai gpt-4o model with fallback options. LangSmith provides comprehensive debugging and performance analysis.

