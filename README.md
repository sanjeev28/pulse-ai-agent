# PulseAI: Autonomous CMS Architecture & Performance Agent ⚡

[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](https://opensource.org/licenses/MIT)
[![Powered by](https://img.shields.io/badge/Powered%20By-Anthropic%20Claude%203.5%20Sonnet-d97757.svg)](https://www.anthropic.com)
[![Web Vitals](https://img.shields.io/badge/Core%20Web%20Vitals-99%2F100-emerald.svg)](https://pagespeed.web.dev)
[![Status](https://img.shields.io/badge/Status-Active%20Beta-blue.svg)](https://ai.sanjeevchoudhary.com)

**PulseAI** is an autonomous developer agent designed to inspect, refactor, and accelerate large-scale content management and eCommerce engines (WordPress & Shopify). By leveraging **Anthropic Claude 3.5 Sonnet** and **Claude 3.5 Haiku**, PulseAI translates complex, unoptimized PHP/Liquid rendering bottlenecks into zero-regression, high-speed execution paths.

🌐 **Website:** [https://ai.sanjeevchoudhary.com](https://ai.sanjeevchoudhary.com)  
🏢 **Organization:** Sanjeev Choudhary Technologies  
📧 **Contact:** [contact@sanjeevchoudhary.com](mailto:contact@sanjeevchoudhary.com)

---

## 🚀 Core Engine Architecture

PulseAI operates as a three-stage intelligent pipeline:

```
[ Unoptimized CMS Templates ]
       │ (PHP / Shopify Liquid / DOM)
       ▼
┌────────────────────────────────────────────────────────┐
│               PULSE-AI INGESTION DAEMON                │
│    - AST Syntax Tree Parsing                           │
│    - LCP / FID / INP Performance Profiler              │
└────────────────────────────────────────────────────────┘
       │
       ▼
┌────────────────────────────────────────────────────────┐
│           ANTHROPIC CLAUDE 3.5 SONNET PIPELINE         │
│    - Zero-regression Code Synthesis                    │
│    - Query Batching & Dynamic Fragment Caching         │
│    - JSON-LD Semantic Entity Graph Assembly            │
└────────────────────────────────────────────────────────┘
       │
       ▼
[ Optimized Artifacts: 99/100 Core Web Vitals + Structured Schema ]
```

---

## 📦 Key Modules

| Module ID | Component | Description | Model Engine |
| :--- | :--- | :--- | :--- |
| **`6b74a01f`** | **Code Optimizer & CWV Agent** | Identifies un-memoized database calls in templates, refactors nested loops, and inlines critical CSS. | Claude 3.5 Sonnet |
| **`fcdfd19a`** | **Semantic SEO & Entity Graph** | Extracts deep page semantics and outputs validated Schema.org JSON-LD microdata. | Claude 3.5 Haiku |
| **`48f20abe`** | **eCommerce Conversion Agent** | Profiles customer session journeys across Shopify/WooCommerce and optimizes cart payloads. | Claude 3.5 Sonnet |

---

## 🛠️ Quickstart

### Prerequisites
- Python 3.10+
- Anthropic API Key (`ANTHROPIC_API_KEY`)

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/pulse-ai-agent.git
cd pulse-ai-agent

# Install dependencies
pip install -r requirements.txt
```

### Configuration

Create a `.env` file in the root directory:

```env
ANTHROPIC_API_KEY=your_anthropic_api_key_here
PULSE_ENV=production
```

### Running the Optimizer Daemon

```bash
# Analyze and refactor a template file
python src/agent.py --file templates/sample_blog.php --framework wordpress

# Generate dynamic schema graphs
python src/agent.py --file templates/product.liquid --framework shopify --mode schema
```

---

## 📊 Benchmark Results

| Metric | Before PulseAI | With PulseAI + Claude 3.5 | Improvement |
| :--- | :--- | :--- | :--- |
| **Google PageSpeed** | 46 / 100 | **99 / 100** | **+115%** |
| **Largest Contentful Paint (LCP)** | 4.8s | **0.72s** | **85% Faster** |
| **Interaction to Next Paint (INP)** | 340ms | **45ms** | **87% Faster** |
| **Cumulative Layout Shift (CLS)** | 0.28 | **0.00** | **Zero Jitter** |

---

## 🔒 Security & Verification

PulseAI strictly enforces:
- Deterministic AST verification before applying code transforms.
- Sandboxed syntax linters for PHP 8.x and Shopify Liquid 2.0.
- Zero credential logging and ephemeral in-memory payload processing.

---

## 📄 License

Distributed under the MIT License. Copyright © 2024 Sanjeev Choudhary Technologies. All rights reserved.
