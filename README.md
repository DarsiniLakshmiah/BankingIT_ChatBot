# 🤖 BankingAI: AI-Powered IT Support Chatbot for Banking

![AWS](https://img.shields.io/badge/Built%20With-AWS-orange?logo=amazon-aws&logoColor=white)
![Python](https://img.shields.io/badge/Language-Python-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)

An AI-powered chatbot solution built using AWS cloud services to handle **IT-related customer support** inquiries in the **banking domain**. Supports **text-based** interactions, with continuous learning and modular cloud infrastructure.

---

## 🚀 Project Overview

BankingAI is designed to automate IT support in banking environments using natural language understanding. It utilizes Amazon's cloud-native services to deliver accurate, real-time responses with a focus on scalability, security, and continuous improvement.

---

## 🧠 Features

- 🔍 **Natural Language Understanding** using AWS Lex
- ⚙️ **Serverless Business Logic** with AWS Lambda
- 🗂 **Chat History Logging** using Amazon DynamoDB
- 🌐 **Frontend/API Integration** via Amazon API Gateway
- ☁️ **Lambda Package Hosting & Model Storage** on Amazon S3
- 📊 **77 Banking Intents** using [BANKING77 dataset (PolyAI)](https://huggingface.co/datasets/PolyAI/banking77)

---

## 📌 Architecture

```plaintext
User → Amazon Lex → AWS Lambda → DynamoDB
                        ↑
          API Gateway + S3 for dependencies


