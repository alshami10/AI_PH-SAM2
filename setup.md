# AI_PH-SAM2 Setup Guide

## Overview

This project implements the AI-PH-SAM2 framework for orthopedic X-ray analysis and segmentation.

Before running the notebook, users must provide their own API keys in the configuration files located in the `assets` folder.

---

## Required API Keys

This project requires:

1. An OpenAI API Key
2. An OpenRouter API Key

### OpenAI API Key

Create an OpenAI account and generate an API key from:

https://platform.openai.com/api-keys

Open the file:

```json
assets/config.json
```

and replace the placeholder value with your OpenAI API key.

Example:

```json
{
    "OPENAI_API_KEY": "YOUR_OPENAI_API_KEY"
}
```

---

### OpenRouter API Key

Create an OpenRouter account and generate an API key from:

https://openrouter.ai/keys

Open the file:

```json
assets/config2.json
```

and replace the placeholder value with your OpenRouter API key.

Example:

```json
{
    "OPENROUTER_API_KEY": "YOUR_OPENROUTER_API_KEY"
}
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/alshami10/AI_PH-SAM2.git
cd AI_PH-SAM2
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

---

## Running the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
AI_PHSAM2.ipynb
```

Run the notebook cells sequentially from top to bottom.

---

## Important Notes

* API keys are not included in this repository.
* Users must supply their own API keys before running the notebook.
* Do not commit personal API keys to GitHub.
* If sharing the repository publicly, keep only template configuration files containing placeholder values.

---
