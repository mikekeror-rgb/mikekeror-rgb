# Hi, I'm Michael Keror

**AI engineer in Kenya building tested, human-in-the-loop AI for payments and operations.**

For nine years I've run IT for a five-site business, including its M-Pesa payroll. Now I build AI tools for that kind of work, with one rule: **code makes the decisions that must be exact, AI explains and proposes, and a person approves.**

## Projects

**[payrecon](https://github.com/mikekeror-rgb/payrecon)**: AI-assisted M-Pesa reconciliation and payroll (Python, SQL, Claude API, Safaricom Daraja).
Idempotent payouts, a hash-chained audit log, and 429 CI tests that caught all 89 deliberately injected bugs. [Live demo](https://payrecon-demo.streamlit.app)

**[payrecon-agent](https://github.com/mikekeror-rgb/payrecon-agent)**: payrecon's reconciliation as a **LangGraph** workflow with a guardrailed **Claude Agent SDK** agent and a human approval step.
Custom tools on an in-process MCP server, a PreToolUse hook, turn and budget caps; code checks every finding before a person decides.

**[payroll-console](https://github.com/mikekeror-rgb/payroll-console)**: React + TypeScript approval console with a Fastify API and shared Zod schemas.
Flags changed numbers, keeps Approve locked until every flag is checked, Vitest + Playwright in CI. [Live demo](https://payroll-console.onrender.com)

**[Advocate Remuneration Assistant](https://github.com/mikekeror-rgb/advocate_renumeration_assistant_v1)**: RAG over Kenyan fee law and ~200 court rulings, with an exact fee calculator.
Self-hosted on vLLM, Ollama and TGI; QLoRA + DPO fine-tuning cut fabricated citations from 11 to 0 on a 62-question eval. [Results page](https://mikekeror-rgb.github.io/advocate_renumeration_assistant_v1/) · [Live app](https://advocate-renumeration-assistant.streamlit.app) · [Model](https://huggingface.co/mikekeror/qwen2.5-7b-advocate-dpo-lora)

**[hybrid-retrieval-eval](https://github.com/mikekeror-rgb/hybrid-retrieval-eval)**: BM25 + dense retrieval fused with Reciprocal Rank Fusion, evaluated in a ZenML pipeline.

**[fridge-check](https://github.com/mikekeror-rgb/fridge-check)**: fine-tuned YOLOv8 running in the phone browser with ONNX Runtime Web (early demo). [Try it](https://mikekeror-rgb.github.io/fridge-check/)

**Open source:** [pull request](https://github.com/confident-ai/deepeval/pull/3375) to DeepEval fixing how LLM judge output is parsed.

## Skills

LLMs · RAG · agents (LangGraph, Claude Agent SDK, MCP) · LLM evaluation · fine-tuning (QLoRA, DPO) · self-hosted serving (vLLM, Ollama, TGI)
Python (FastAPI) · TypeScript (React, Node.js) · SQL · REST APIs · Docker · GitHub Actions
M-Pesa payment integration · Microsoft 365 · Windows Server · user support

## Contact

📧 mikekeror@gmail.com · 🤗 [huggingface.co/mikekeror](https://huggingface.co/mikekeror)
