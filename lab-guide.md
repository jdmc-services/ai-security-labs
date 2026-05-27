# Lab Guide: Prompt Injection Testing with a Local LLM

## Objective

Test whether a local LLM follows untrusted instructions that attempt to override the user's intended task.

## Tools

- Ollama
- llama3.2
- Local terminal
- Synthetic text file

## Step 1: Install Ollama

Download and install Ollama from:

https://ollama.com

Then run:

```bash
ollama pull llama3.2