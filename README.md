# QualityGate

A unified test automation and LLM evaluation framework for an AI-powered customer support assistant (built on top of my SupportSense project).

> Status: In progress. Items are checked off as they are completed.

## What it will cover

- **Web UI automation:** Playwright + Pytest with Page Object Model, fixtures, config-driven environments and Allure reporting
- **API testing:** Postman/Newman collection and OpenAPI/Swagger contract tests for the FastAPI backend
- **Mobile automation:** Appium tests on Android (Flutter app)
- **LLM evaluation:** DeepEval and Ragas scoring for groundedness, faithfulness and hallucination rate on a curated golden dataset
- **AI safety testing:** promptfoo red-teaming and Pytest checks for prompt injection, jailbreaks and PII leakage
- **CI/CD:** Dockerized GitHub Actions pipelines with smoke tests on PRs, nightly regression and metric-based quality gates that block merges

## Roadmap

- [ ] Playwright + Pytest skeleton (POM, Allure, Docker)
- [ ] API layer (Postman/Newman, OpenAPI contract tests)
- [ ] DeepEval + Ragas evaluation with golden dataset and CI thresholds
- [ ] promptfoo red-team suite and PII/prompt-injection tests
- [ ] Appium Android tests
- [ ] Model regression
