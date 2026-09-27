# Laya AI System 1 Decision Gateway — Official Showcase & Portal

[![RapidAPI](https://img.shields.io/badge/RapidAPI-Live%20Marketplace-blue.svg)](https://rapidapi.com/harshadjadav849/api/laya-ai-api-gateway-lightning-decision-engine-api)
[![Inference Latency](https://img.shields.io/badge/Inference-%3C35ms-brightgreen.svg)]()
[![Model](https://img.shields.io/badge/Model-convaiinnovations%2Flaya-orange.svg)](https://huggingface.co/convaiinnovations/laya)
[![License](https://img.shields.io/badge/License-MIT-purple.svg)]()

> High-speed (< 35ms), non-generative System 1 decision engine for customer support triage, AI agent prompt injection defense, spam detection, and calibrated typed decisions.

---

## 🚀 Live Links

* **RapidAPI Marketplace Listing**: [Laya AI Decision Engine on RapidAPI](https://rapidapi.com/harshadjadav849/api/laya-ai-api-gateway-lightning-decision-engine-api)
* **Underlying Model on Hugging Face**: [convaiinnovations/laya](https://huggingface.co/convaiinnovations/laya)
* **Author / Developer Profile**: [Harshad Jadav (@harshadprs)](https://github.com/harshadprs)

---

## ⚡ What is System 1 AI?

Unlike generative Large Language Models (LLMs) that generate text token-by-token with 1,500ms to 3,500ms latency and high risk of hallucinations, **Laya System 1** is a non-autoregressive bidirectional encoder (mmBERT-based, 322M parameters).

It evaluates input text across 100+ languages in a **single mathematical forward pass (< 35 ms)**, returning strictly calibrated categorical choices, urgency scores, and boolean decisions.

---

## 🛠️ Core Monetizable Endpoints

1. **Support Ticket Triage** (`POST /v1/triage`): Routes customer inquiries into departments (`billing`, `technical`, `account`), grades urgency (0-2), and flags churn/cancellation threats.
2. **Prompt Injection Firewall** (`POST /v1/guard`): Sub-30ms security perimeter for AI agents to detect jailbreaks and prompt exploits before hitting expensive LLMs.
3. **Spam & Phishing Filter** (`POST /v1/filter/spam`): Real-time detection of marketing junk, unsolicited spam, and credential phishing scams.
4. **Sentiment & Frustration Analyzer** (`POST /v1/sentiment`): Detects positive/neutral/negative tone with customer anger intensity scoring.
5. **Content Moderation Gate** (`POST /v1/moderate`): Zero-shot multi-label safety filter for toxicity, hate speech, and harassment.
6. **Universal Typed Decisions** (`POST /v1/decide`): Executes arbitrary choice, scoring, or boolean questions on any text or state payload.

---

## 🎁 Limited Time Promotion

Get started for **FREE** with **1,000 free requests per month** on RapidAPI:
👉 [Subscribe to Free Tier on RapidAPI](https://rapidapi.com/harshadjadav849/api/laya-ai-api-gateway-lightning-decision-engine-api)

---

## 👥 Authorship & Credits

* **Gateway Creator & Cloud Architect**: **Harshad Jadav** ([GitHub](https://github.com/harshadprs))
* **Underlying Model Creator**: **Convai Innovations** — Creators of the open-source [convaiinnovations/laya](https://huggingface.co/convaiinnovations/laya) model.

---

## ⚖️ Legal & Compliance

* [Privacy Policy](privacy.html) — Zero data retention, in-transit encryption, GDPR & CCPA compliant.
* [Terms of Service](terms.html) — Acceptable use, SLAs, and liability terms.
* [DMCA Policy](dmca.html) — Digital Millennium Copyright Act notices and takedown procedures.

---

## 🌐 Enabling GitHub Pages (1-Click Hosting)

1. Go to this repository's **Settings** on GitHub.
2. Click **Pages** on the left sidebar.
3. Under **Build and deployment** -> **Branch**:
   * Select **`main`**
   * Folder: **`/ (root)`**
4. Click **Save**.
5. Your marketing landing page will be instantly live at:
   `https://harshadprs.github.io/<repo-name>/`
