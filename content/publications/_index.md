+++
title = "Publications"
description = "Academic publications and research papers by Serge Youmbi on Category Theory, Deep Learning, Multi-Agent AI, and Computational Finance."
sort_by = "date"
weight = 1
template = "publications/section.html"

[extra]
lead = "My academic contributions to the fields of AI, mathematics, and computational finance."
+++

## 2026

### Deriving Insights: Traditional Neural Networks using Haskell Grenade

**Serge Youmbi** | *2026*

This paper explores neural network implementation via Grenade, a dependently-typed library for Haskell. It presents ten distinct financial machine learning examples including feedforward networks, CNNs, RNNs, autoencoders, VAEs, GANs, attention mechanisms, graph neural networks, and ensemble systems. The work demonstrates practical applications across a portfolio of sixteen stocks with specific performance metrics.

<div class="publication-meta">
  <span class="badge bg-primary">Haskell</span>
  <span class="badge bg-secondary">Neural Networks</span>
  <span class="badge bg-info">Dependent Types</span>
</div>

**Key Contributions:**
- Comprehensive implementation of ten neural network architectures in Grenade
- Type-safe neural network construction using dependent types
- Practical financial machine learning applications with real portfolio data
- Performance benchmarks across sixteen stock instruments

[View on Academia.edu](https://derby.academia.edu/SergeYoumbi)

---

### Probabilistic Programming for Quantitative Finance: A Functional Approach Using Algebraic Effects

**Serge Youmbi** | *2026*

This paper presents a framework for expressing financial models as probabilistic programs using algebraic effects in Haskell. It includes ten detailed case studies spanning derivative pricing, credit risk modelling, portfolio allocation, interest rate dynamics, market regime detection, and multi-factor asset pricing.

<div class="publication-meta">
  <span class="badge bg-primary">Probabilistic Programming</span>
  <span class="badge bg-secondary">Algebraic Effects</span>
  <span class="badge bg-info">Quantitative Finance</span>
</div>

**Key Contributions:**
- Novel framework combining probabilistic programming with algebraic effects
- Ten comprehensive case studies in quantitative finance
- Type-safe uncertainty quantification for financial models
- Applications to derivative pricing, credit risk, and portfolio allocation

[View on Academia.edu](https://derby.academia.edu/SergeYoumbi)

---

### A Foundational Framework for Understanding Neural Computation through Category Theory and Operational Semantics

**Serge Youmbi** | *2026*

This paper establishes formal correspondences between categorical structures and neural network architecture. It demonstrates that backpropagation emerges from the contravariant nature of gradient computation through categorical duality, with soundness and completeness results analogous to logic programming systems.

<div class="publication-meta">
  <span class="badge bg-primary">Category Theory</span>
  <span class="badge bg-secondary">Operational Semantics</span>
  <span class="badge bg-info">Neural Computation</span>
</div>

**Key Contributions:**
- Formal categorical foundations for neural network architectures
- Proof that backpropagation arises from categorical duality
- Soundness and completeness results for neural computation
- Bridge between logic programming and deep learning theory

[View on Academia.edu](https://derby.academia.edu/SergeYoumbi)

---

### Deep Neural Networks: An Interactive Exploration Through State Machine-Orchestrated Visualisations

**Serge Youmbi** | *2026*

This paper explores nine fundamental neural network architectures through interactive visualisation using finite state machines. It employs XState and D3.js for state machine patterns to manage UI complexity, temporal navigation, and real-time rendering during model inference.

<div class="publication-meta">
  <span class="badge bg-primary">Visualisation</span>
  <span class="badge bg-secondary">State Machines</span>
  <span class="badge bg-info">Interactive Learning</span>
</div>

**Key Contributions:**
- Interactive visualisation framework for nine neural network architectures
- Novel application of XState for managing complex UI state
- Real-time rendering of model inference using D3.js
- Educational tool for understanding deep learning internals

[View on Academia.edu](https://derby.academia.edu/SergeYoumbi)

---

### Deep Neural Networks: An Implementation in Haskell Using Recursion Schemes

**Serge Youmbi** | *2026*

This paper implements neural networks via recursion schemes from category theory. Forward propagation functions as a catamorphism (generalised fold); backward propagation as an anamorphism (generalised unfold). The implementation supports dense networks, CNNs, RNNs, LSTMs, and Transformers with applications to financial forecasting.

<div class="publication-meta">
  <span class="badge bg-primary">Recursion Schemes</span>
  <span class="badge bg-secondary">Haskell</span>
  <span class="badge bg-info">Category Theory</span>
</div>

**Key Contributions:**
- Novel formulation of neural networks using recursion schemes
- Forward propagation as catamorphism, backpropagation as anamorphism
- Support for dense, CNN, RNN, LSTM, and Transformer architectures
- Applications to financial time series forecasting

[View on Academia.edu](https://derby.academia.edu/SergeYoumbi)

---

## 2025

### A Survey of Category Theory and Deep Learning

**Serge Youmbi** | *2025*

A comprehensive examination of the intersection between category theory and deep learning. The survey is organised around six thematic clusters: compositional foundations, differentiation and learning dynamics, geometric and equivariant structures, semantic and logical frameworks, probabilistic perspectives, and implementation paradigms.

<div class="publication-meta">
  <span class="badge bg-primary">Category Theory</span>
  <span class="badge bg-secondary">Deep Learning</span>
  <span class="badge bg-info">Survey</span>
</div>

**Key Contributions:**
- Comprehensive survey of category-theoretic approaches to deep learning
- Organisation into six thematic clusters for systematic understanding
- Coverage of compositional, geometric, probabilistic, and semantic perspectives
- Roadmap for future research at the category theory–AI intersection

[View on Academia.edu](https://derby.academia.edu/SergeYoumbi)

---

### Multi-Agent AI Systems for Financial Portfolio Management and Option Pricing

**Serge Youmbi** | *2025*

In advanced multi-agent frameworks, the deployment of domain-specific LLM-powered agents—each fulfilling unique functions such as fundamental analysis, sentiment interpretation, technical assessment, and trading with tailored risk profiles—creates a robust ecosystem for financial strategy formulation. Through systematic deliberation and cooperative decision-making, these agents collectively enhance trading efficacy, yielding marked improvements in cumulative returns, risk-adjusted performance (Sharpe ratio), and drawdown resilience relative to conventional benchmark approaches.

<div class="publication-meta">
  <span class="badge bg-primary">Multi-Agent Systems</span>
  <span class="badge bg-secondary">Portfolio Management</span>
  <span class="badge bg-info">LLMs</span>
</div>

**Key Contributions:**
- Framework for orchestrating domain-specific LLM agents in financial contexts
- Systematic deliberation protocols for consensus-based trading decisions
- Empirical evidence of improved Sharpe ratios and reduced drawdowns

[View on Academia.edu](https://derby.academia.edu/SergeYoumbi)

---

### Algebraic Effects and Delimited Continuations for Multi-Agent AI Systems in Financial Portfolio Management and Options Pricing

**Serge Youmbi** | *2025*

This document presents an architectural framework for building multi-agent AI systems in the financial domain using Kyo's algebraic effect system. Kyo, developed by Flavio Brasil at Nubank, introduces a novel approach to effect handling through first-class delimited continuations that can be resumed zero, one, or multiple times.

Unlike traditional approaches that rely on callback chains, promise combinators, or actor-based message passing, Kyo's continuation-based semantics enable sophisticated control flow patterns essential for financial applications: speculative execution for latency-sensitive pricing, transactional rollback for failed multi-leg trades, fan-out aggregation for consensus pricing, and checkpoint/resume for long-running optimisation loops.

<div class="publication-meta">
  <span class="badge bg-primary">Algebraic Effects</span>
  <span class="badge bg-secondary">Continuations</span>
  <span class="badge bg-info">Options Pricing</span>
</div>

**Key Contributions:**
- First application of Kyo's algebraic effects to financial systems
- Type-safe effect tracking for regulatory compliance
- Formal reasoning framework for multi-agent financial systems
- Production-ready architecture for institutional finance

[View on Academia.edu](https://derby.academia.edu/SergeYoumbi)

---

### Multi-LLM Orchestration Patterns for Supply Chain Systems

**Serge Youmbi** | *2025*

Modern supply chains operate across vast, interconnected networks that demand intelligent coordination of logistics, inventory, and distribution. Building on foundational principles from operations research—such as Simchi-Levi's "Operations Rules" for balancing efficiency and resilience—this work explores how multi-LLM orchestration can extend these frameworks.

By dynamically selecting and coordinating large language models based on task complexity, urgency, and precision, it introduces a principled architecture for applying advanced AI to supply chain optimisation.

<div class="publication-meta">
  <span class="badge bg-primary">Supply Chain</span>
  <span class="badge bg-secondary">LLM Orchestration</span>
  <span class="badge bg-info">Operations Research</span>
</div>

**Key Contributions:**
- Multi-LLM orchestration framework with dynamic model selection
- Integration of classical operations research with modern AI
- Principled architecture balancing efficiency and resilience
- Application to real-world supply chain optimisation

[View on Academia.edu](https://derby.academia.edu/SergeYoumbi)

---

## Theoretical Foundations

### Conceptualising Trigraphs: A Generalisation of Milner's Bigraphs

**Serge Youmbi** | *Working Paper*

We explore a conceptual generalisation of Robin Milner's Bigraphs, known for forming a symmetric partial monoidal category, into a novel concept termed "Trigraphs." We discuss the foundational aspects of Bigraphs, propose potential interpretations for a third structural component in Trigraphs, and consider how the categorical operations might be extended.

<div class="publication-meta">
  <span class="badge bg-primary">Category Theory</span>
  <span class="badge bg-secondary">Bigraphs</span>
  <span class="badge bg-info">Formal Methods</span>
</div>

**Key Contributions:**
- Novel generalisation of Milner's Bigraph formalism
- Extension of symmetric partial monoidal category structure
- Exploration of third structural components (temporal, computational, informational)
- Foundations for modelling complex distributed systems

[View on Academia.edu](https://derby.academia.edu/SergeYoumbi)

---

## Research Themes

My publications span several interconnected themes:

| Theme | Focus Areas | Publications |
|-------|-------------|--------------|
| **Category Theory & Deep Learning** | Recursion schemes, categorical semantics, operational semantics | 4 papers |
| **Functional Programming** | Haskell, dependent types, algebraic effects | 4 papers |
| **Multi-Agent AI** | LLM orchestration, consensus mechanisms, financial applications | 3 papers |
| **Quantitative Finance** | Portfolio management, derivative pricing, risk modelling | 5 papers |
| **Visualisation & Education** | Interactive tools, state machines, D3.js | 1 paper |
| **Supply Chain** | Operations research, AI optimisation | 1 paper |

---

## Upcoming Work

- **Coalgebraic Semantics for Generative Models** — Stream-based interpretation of diffusion models
- **Effect Systems for Regulatory Compliance** — Type-level guarantees for financial audit trails
- **Functorial Data Augmentation** — Category-theoretic framework for training data transformations

---

<div class="text-center mt-5">
  <a href="https://derby.academia.edu/SergeYoumbi" class="btn btn-primary btn-lg" target="_blank">Academia.edu Profile</a>
  <a href="https://derby.academia.edu/SergeYoumbi" class="btn btn-outline-primary btn-lg ms-3" target="_blank">Request Papers</a>
</div>
