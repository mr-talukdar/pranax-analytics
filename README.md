# PranaX Gym Intelligence Engine

A modular Python-based analytics and intelligence engine designed to transform gym business data into actionable business insights.

PranaX Gym Intelligence Engine is being developed as the intelligence layer of **PranaX**, a Fitness Business Operating System. It will provide deterministic business analytics, predictive modelling and AI-assisted insights for fitness businesses.

## Overview

The engine processes gym operational and financial data to generate structured business intelligence.

It focuses on building reliable analytical capabilities first, followed by predictive analytics and AI-powered business intelligence.

The long-term objective is to enable gym owners and operators to understand their business performance, identify operational patterns, anticipate potential problems and make data-driven decisions.

## Core Objectives

- **Revenue Analytics:** Track revenue performance, growth, monthly trends and financial indicators.
- **Membership Analytics:** Analyse active memberships, new registrations, renewals and membership trends.
- **Payment Analytics:** Understand payment patterns, outstanding payments and recurring revenue.
- **Attendance Analytics:** Analyse gym attendance, member engagement and utilisation patterns.
- **Predictive Analytics:** Develop revenue forecasting, churn indicators and anomaly detection.
- **Business Intelligence:** Generate structured business summaries and contextual explanations using AI.

## Technology Stack

| Technology   | Purpose                                   |
| ------------ | ----------------------------------------- |
| Python       | Core development language                 |
| NumPy        | Numerical computation                     |
| pandas       | Data processing and analytics             |
| Matplotlib   | Data visualisation                        |
| scikit-learn | Machine learning and predictive modelling |
| pytest       | Automated testing                         |

### Planned Technologies

- FastAPI for exposing analytics capabilities through REST APIs.
- Pydantic for data validation and structured schemas.
- Google Gemini API for AI-assisted business intelligence.
- Embeddings and vector search for contextual retrieval.
- RAG for grounded natural-language business queries.

## Project Structure

```text
pranax-gym-intelligence-engine/
│
├── datasets/           # Development and synthetic datasets
│
├── notebooks/          # Exploratory data analysis and experiments
│
├── src/                # Reusable analytics and intelligence modules
│   └── __init__.py
│
├── tests/              # Automated tests
│   └── __init__.py
│
├── README.md
├── requirements.txt
└── .gitignore
```

The project structure will evolve as new modules and capabilities are introduced.

## Getting Started

### Prerequisites

- Python 3.12 or newer (Python 3.14.4 is the current development environment).
- pip
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/pranax-gym-intelligence-engine.git

cd pranax-gym-intelligence-engine
```

Create a virtual environment:

```bash
python3 -m venv .venv
```

Activate the environment on Linux:

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

### Running Tests

Execute the test suite using:

```bash
pytest
```

## Development Roadmap

### Phase 1: Deterministic Analytics

- Revenue and membership metrics.
- Payment analytics.
- Attendance analytics.
- Subscription analytics.
- Structured gym business summaries.

### Phase 2: Predictive Analytics

- Revenue forecasting.
- Membership churn indicators.
- Churn classification.
- Anomaly detection.
- Model evaluation and validation.

### Phase 3: AI Intelligence Layer

- Gemini API integration.
- Structured AI outputs.
- Natural-language business queries.
- AI-generated business explanations.
- Function calling.

### Phase 4: Contextual Intelligence

- Embeddings.
- Vector search.
- Retrieval-Augmented Generation (RAG).
- Grounded business intelligence.

### Phase 5: API Integration

- FastAPI integration.
- Pydantic validation.
- Supabase connectivity.
- Analytics endpoints.
- Integration with the PranaX TypeScript backend.

### Phase 6: Production Readiness

- Automated testing.
- Input and output validation.
- Error handling and logging.
- Multi-tenant data isolation.
- Deployment and monitoring.

## Engineering Principles

The project follows these principles:

1. **Deterministic First:** Use conventional programming and statistical methods for calculations that do not require machine learning.
2. **Data Integrity:** Validate inputs and outputs before generating business insights.
3. **No Hallucinated Metrics:** AI-generated explanations must be grounded in calculated and verified business metrics.
4. **Responsible Machine Learning:** Prevent data leakage and use chronological validation for time-dependent prediction problems.
5. **Tenant Isolation:** Ensure gym business data remains isolated across tenants.
6. **Reproducibility:** Maintain reproducible datasets, experiments and model evaluations.
7. **Simplicity:** Prefer maintainable solutions over unnecessary architectural complexity.
8. **CPU-Friendly Development:** Prioritise lightweight approaches and avoid unnecessary infrastructure.

## Current Development Status

<badge color="info">Early development</badge>

The initial repository and Python development environment are being established.

The first implementation milestone is a reusable gym analytics module capable of generating structured business summaries from monthly operational data.

## License

To be determined.
