# Perplexity Explorer

**An interactive machine learning laboratory for understanding how language models predict text.**

Perplexity Explorer is a browser-based tool that helps users understand how language models process sentences, calculate token probabilities, predict the next token, and measure perplexity.

It uses a local language model through Transformers.js, allowing inference directly in the browser without requiring an API key or backend server.

## 🚀 Live Demo

[Open Perplexity Explorer](YOUR_VERCEL_URL)

## ✨ Features

### 1. Sentence Explorer
- Enter your own sentences.
- Tokenize and analyze the input.
- Explore the probability assigned to each token.

### 2. Token Probability Analysis
- View individual token probabilities.
- Understand how confidently the model predicts each token.
- Explore inverse probability values (1/P).

### 3. Perplexity Calculator
- Calculate sentence perplexity using token probabilities.
- Use log-space calculations for numerical stability.
- Understand how perplexity measures model uncertainty.

### 4. Next Token Predictions
- Generate the top
