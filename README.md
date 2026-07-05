# eCommerce AI Transformation Playbook

A complete AI transformation programme for eCommerce content operations —
covering strategic assessment, use case prioritisation, knowledge architecture,
workflow automation, agentic AI strategy, and governance framework. Each
strategic deliverable is accompanied by a deployed proof of concept.

Built to demonstrate end-to-end transformation leadership capability, from
board-level investment rationale to working production systems.

---

## Components

### Component 1 — AI Landscape & Opportunity Assessment
**Status:** Complete

A structured capability assessment of five major AI platforms tested against real eCommerce content operations tasks. Designed to answer the operational question every transformation lead must answer before recommending any AI platform: which tools can actually be trusted in a production content workflow?

**What was tested:** Claude, ChatGPT, Gemini, Copilot, and Perplexity across three eCommerce tasks — product description generation, category intelligence, and AI use case identification. Identical inputs, structured scoring framework, 25-point maximum across five criteria.

**Key finding:** Claude scored highest (24/25), distinguished by eCommerce context awareness, platform-specific intelligence, and zero hallucination risk. Perplexity was the most underrated platform (22/25). ChatGPT and Copilot tied at 18/25 — reliable for general tasks but weak on platform-specific intelligence without detailed prompting.

**Strategic implication:** Platform selection for eCommerce content AI should prioritise domain accuracy and context awareness over general capability benchmarks. A model that produces accurate content without understanding platform mechanics creates more operational overhead than it removes.

[Read the full assessment →](https://app.notion.com/p/AI-Platform-Comparison-Test-eCommerce-Content-Operations-38d1a1c9f954809aa03fdfe14ae2209b?source=copy_link)

---

### Component 2 — eCommerce Prompt Library
**Status:** Complete

**What this is:** A library of 25 production-tested prompts across 5 eCommerce content operations categories — product content, categorisation and data, quality assurance, competitor and market intelligence, and reporting. Every prompt includes a defined system role, structured output instructions, and a real tested output.

**What was built:** 25 prompts covering the full eCommerce content workflow — from product description generation and attribute extraction to compliance review, competitive positioning analysis, and executive briefing writing. Each prompt is documented with the technique used (role-based, JSON output, chain-of-thought, PASS/FAIL verdict, RAG status format) so it can be replicated and adapted by any content team.

**Key finding:** Prompt structure determines output quality more than platform choice for standard tasks. A role-based prompt with explicit output constraints and negative rules consistently outperforms an open-ended question on the same task — regardless of which AI platform is used. The JSON extraction prompt (Prompt 06) is the highest-value prompt in the library: it returns machine-readable structured data that can feed directly into a catalogue system, removing a manual data entry step entirely.

**Techniques demonstrated:** Role-based prompting, negative constraints, structured output forcing, JSON-only output, chain-of-thought reasoning, PASS/FAIL compliance verdicts, RAG status reporting formats, character and word count constraints, rationale-required instructions.

**Tools:** Claude (primary testing), ChatGPT, Groq API (Llama 3.3 70B)

[Read the full prompt library →](https://github.com/SK-works/eCommerce-AI-Transformation-Playbook/blob/main/eCommerce_Prompt_Library) 
[Read the full documentation →](https://app.notion.com/p/eCommerce-Prompt-Library-25-Production-Grade-Prompts-for-eCommerce-Content-Operations-38e1a1c9f95480d5b3f3c17955776790?source=copy_link)

---

### Component 3 — AI Knowledge Assistant (RAG Chatbot)
**Status:** Complete

A live, publicly accessible RAG (Retrieval-Augmented Generation) chatbot that answers eCommerce content operations questions grounded in a structured 6-document knowledge base. Anyone can open the link, ask a question, and get a grounded, accurate answer drawn directly from the knowledge base.

**Knowledge base covers:** Product description standards, product taxonomy and classification rules, image compliance requirements, content quality framework, eCommerce terminology, and attribute extraction guides.

**Technology:** Botpress · GPT-4o · Semantic search · 6 custom knowledge base documents · Free tier deployment

**Tested and verified:** All three validation questions answered accurately — product description structure, taxonomy classification, and image compliance requirements — with answers grounded directly in knowledge base content.

**Live demo:** [Open the eCommerce AI Assistant →](https://cdn.botpress.cloud/webchat/v3.6/shareable.html?configUrl=https://files.bpcontent.cloud/2026/06/29/10/20260629101945-GGRHALLO.json)

Suggested questions to try:
- "What is the word count for a standard product description?"
- "What attributes are mandatory for instant coffee listings?"
- "What is a ghost mannequin?"
- "Where do I classify a children's tablet?"
- "What makes a listing retail ready?"

---

### Component 4 — Product Brief Process Automation Workflow
**Status:** Complete

**What this is:** A working automation workflow that takes a product 
name and specifications as input and generates a complete, structured 
product brief automatically — title, description, bullet points, 
category, and search keywords — in under 2 seconds.

**Tested across:** 6 product categories including consumer electronics, 
kitchen appliances, fitness technology, food and beverage, and home 
cleaning. 100% success rate across all test products.

**Key performance finding:** AI generation takes 1.2 seconds per SKU 
versus 25-35 minutes manual. With a mandatory human review step of 
2-3 minutes, total time per SKU drops from 30 minutes to 2.5 minutes — 
an 8-10x throughput improvement per operator.

**Tools:** Google Colab, Groq API (Llama 3.3 70B), Python

**Human oversight:** Every brief requires operator review before 
publishing. The workflow automates the drafting step only — human 
judgment on quality, accuracy, and brand alignment is retained.

[Read the full documentation →] https://app.notion.com/p/eCommerce-Product-Brief-Process-Automation-Workflow-3921a1c9f95480e1bed4e5fb838d881e?source=copy_link

---

### Component 5 — AI Competitor Intelligence Agent
**Status:** Complete

**What this is:** A four-step autonomous AI agent that researches 
a product category and generates a complete competitive 
intelligence brief — identifying competitor strategies, market 
gaps, and strategic opportunities — without any manual steps 
between input and output.

**How it works:** Four specialist AI agents run in sequence — 
Market Researcher → Gap Analyst → Opportunity Strategist → 
Intelligence Writer. Each step feeds its output into the next, 
exactly as a human analyst team would work.

**Tested across:** 2 product categories — Wireless Earbuds 
(£30–£80) and Robot Vacuum Cleaners (£150–£300). 100% success 
rate. Different competitors, gaps, and opportunities correctly 
identified for each category automatically.

**Key performance finding:** Manual competitive intelligence 
takes 2–3 hours per category. The agent completes the same 
research and writing in 68 seconds. With a 10–15 minute analyst 
review step, total time per brief drops from 3 hours to 
15 minutes — a 10–12x improvement.

**Tools:** Google Colab, Groq API (Llama 3.3 70B), Python

**Human oversight:** Agent output is a research draft. 
Analyst review covers factual accuracy, client relevance, 
and strategic appropriateness before delivery.

[Read the full documentation →] https://app.notion.com/p/eCommerce-Competitor-Intelligence-Agent-3941a1c9f9548074a129d2de767d1dea?source=copy_link

---

### Component 6 — AI Governance Framework
**Status:** Complete

**What this is:** A complete, practical AI governance framework 
for eCommerce content operations — covering AI system registry, 
risk tier classification, responsible AI principles, data 
classification, incident response, and a 25-point pre-deployment 
checklist.

**Why it matters:** Every AI system in this portfolio is governed 
by this framework. The human review steps, output logging, and 
confidence thresholds built into Components 3, 4, and 5 all 
directly implement the principles and controls defined here.

**Grounded in:** EU AI Act, NIST AI Risk Management Framework, 
GDPR obligations for B2B eCommerce operations.

**Key sections:**
- AI System Registry — master inventory of all deployed systems
- Risk Tier Classification — Low / Medium / High with specific 
  eCommerce examples
- 5 Responsible AI Principles with eCommerce-specific 
  failure mode examples
- Data Classification — 4 tiers from Public to Restricted
- Incident Response — 5-step procedure with time targets
- Pre-Deployment Checklist — 25 checks across 5 categories

[Read the full framework →] https://app.notion.com/p/AI-Governance-Framework-eCommerce-AI-Deployment-3941a1c9f95480aebab5d8beb4b6c6b3?source=copy_link

---

## About This Project

**Role context:** AI Transformation & Strategic Projects Lead — eCommerce Content Operations

**Project goal:** Demonstrate end-to-end AI transformation leadership capability — the ability to assess, prioritise, design, build, govern, and communicate AI initiatives in a real eCommerce operations context.

All tools used are free tier. All proof of concepts are deployed and publicly accessible.
