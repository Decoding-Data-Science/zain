
https://huggingface.co/spaces/decodingdatascience/newrag-pine

# 📞 Telecom Customer Support LLM with Groq API

This project demonstrates how to build a fast, production-grade AI-powered telecom customer support assistant using the **Groq API** and optimized GenAI configurations.

## 📌 Project Overview

A step-by-step guide to:
- Sending POST requests using **Postman**
- Connecting to the **Groq API**
- Testing default vs. optimized GenAI configurations
- Applying structured **prompt templates**
- Deploying a simple LLM-powered support API

## 🔧 Tech Stack

| Layer         | Tool/Tech               |
|---------------|-------------------------|
| LLM           | [Groq API](https://groq.com/) |
| API Platform  | FastAPI / Postman       |
| Prompt Design | Custom templates        |
| Deployment    | Localhost / Cloud (optional) |

## 🧠 AI Configuration

| Parameter           | Description                          |
|---------------------|--------------------------------------|
| `temperature`       | Controls randomness (default: 0.7)   |
| `top_p`             | Nucleus sampling                     |
| `max_tokens`        | Max tokens to generate               |
| `frequency_penalty` | Repetition control                   |
| `presence_penalty`  | Topic diversity                      |

## 🔄 Experiment Setup

### 1. No Prompt Template + Default Config
- Basic user input
- Uses Groq defaults
- For benchmarking

### 2. With Prompt Template + Tuned Config
- Structured input (e.g., role, intent, constraints)
- Custom temperature and token limits
- Optimized for domain-specific responses

## 🚀 Quickstart

### Step 1: Clone the repo

```bash
git clone https://github.com/your-username/telecom-support-llm.git
cd telecom-support-llm
