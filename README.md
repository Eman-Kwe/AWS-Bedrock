# AWS-Bedrock

# AWS Bedrock
 
> A fully managed service for building generative AI applications using foundation models (FMs) from leading AI companies — without managing infrastructure.
 
---
 
## What is AWS Bedrock?
 
**Amazon Bedrock** is a serverless AI service on AWS that provides access to high-performing foundation models via a single API. It enables you to build, customize, and scale generative AI applications securely within the AWS ecosystem.
 
---
 
## Key Features
 
| Feature | Description |
|---|---|
| **Model Access** | Single API to query FMs from Anthropic, Meta, Mistral, Amazon, Cohere, and more |
| **Fine-Tuning** | Customize models with your own data using fine-tuning or continued pre-training |
| **RAG** | Built-in Knowledge Bases for Retrieval-Augmented Generation (RAG) |
| **Agents** | Orchestrate multi-step tasks with Bedrock Agents |
| **Guardrails** | Apply content filters, PII redaction, and topic restrictions |
| **Serverless** | No infrastructure to provision or manage |
 
---
 
## Supported Foundation Models
 
- **Anthropic** — Claude 3 (Haiku, Sonnet, Opus)
- **Meta** — Llama 3
- **Mistral AI** — Mistral & Mixtral
- **Amazon** — Titan Text, Titan Embeddings, Nova
- **Cohere** — Command, Embed
- **Stability AI** — Stable Diffusion (image generation)
---
 
## Quick Start
 
### Prerequisites
 
- An AWS account with Bedrock model access enabled
- AWS CLI configured (`aws configure`)
- Python 3.8+ and `boto3`
