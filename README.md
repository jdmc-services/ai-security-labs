# AI Security Lab 1: Prompt Injection Testing

This lab demonstrates how prompt injection can affect local large language models in a controlled, defensive learning environment.

## Purpose

The purpose of this lab is to help cybersecurity students, IT leaders, and AI governance professionals understand how prompt injection can manipulate AI-generated responses, especially when models summarize documents, tickets, emails, logs, or knowledge-base content.

## Safety Scope

This lab is for defensive cybersecurity education only.

- Use synthetic data only.
- Do not test public systems.
- Do not test employer systems.
- Do not use PHI, PII, credentials, internal documents, or production data.
- Do not connect the model to email, browsers, cloud drives, APIs, or automation tools.

## Framework Mapping

- OWASP LLM Top 10: LLM01 Prompt Injection
- NIST AI RMF: Govern, Map, Measure, Manage
- Security+: Vulnerability assessment, risk analysis, remediation documentation

## Lab Outcome

By the end of this lab, the learner will be able to:

1. Deploy a local LLM.
2. Test baseline model behavior.
3. Demonstrate direct prompt injection.
4. Demonstrate indirect prompt injection using a synthetic document.
5. Document the issue as a pentest-style finding.
6. Recommend defensive controls.