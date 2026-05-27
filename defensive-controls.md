# Defensive Controls for Prompt Injection

## Core Principle

Never allow untrusted content to become trusted instruction.

## Recommended Controls

1. Treat all pasted, uploaded, retrieved, or external content as untrusted data.
2. Clearly separate user instructions from document content.
3. Use delimiters around documents, logs, tickets, and emails.
4. Instruct the model to identify assistant-directed text inside documents.
5. Validate whether the model answered the user's original task.
6. Do not give the model direct access to email, files, APIs, or automation tools during early testing.
7. Require human approval before the AI system sends messages, opens tickets, modifies records, or triggers workflows.
8. Log prompts, model responses, test cases, and findings.
9. Use synthetic data only in labs.
10. Align controls to OWASP LLM Top 10 and NIST AI RMF.