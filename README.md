# Awesome-AI-Guardrails-Prompt-Sandboxing

## Top AI Guardrails & Prompt Sandboxing Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Prompt Injection Defense, Programmable LLM Guardrails, AI Agent & Code Sandboxing, PII Redaction & Adversarial Red-Teaming*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Guardrails & Prompt Sandboxing**. These tools protect LLM applications and autonomous agents against direct and indirect prompt injection, enforce topical and structured output policies, isolate coding/shell agents inside locked-down sandboxes, redact sensitive PII, and continuously red-team models.



**Examples** include Lakera Guard, NVIDIA NeMo Guardrails, Protect AI, HiddenLayer, Arthur Shield, Patronus AI, Fiddler AI, Aporia, Robust Intelligence, Guardrails AI, and Lee-xeo/Claude-Cage (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for coding-agent sandboxing (`Claude-Cage`, `E2B`, `Firecracker`, `Bubblewrap`/`Seatbelt` wrappers), programmable guardrail runtimes (`NeMo Guardrails`, `Guardrails AI`, `LLM Guard`), open safety classifiers (`Llama Guard`, `ShieldGemma`, `WildGuard`), and automated LLM red-teaming (`Garak`, `PyRIT`) — ideal for AI security engineers, platform architects, and developers deploying safe autonomous agents.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Lakera Guard](https://lakera.ai)**  

  Ultra-low-latency real-time AI security firewall protecting LLM applications and agents from prompt injections, jailbreaks, data leakage, and malicious content via a single API call.



- **[Protect AI (Layer & Guardian)](https://protectai.com)**  

  Enterprise AI security platform offering real-time prompt firewalling, ML supply-chain vulnerability scanning (`ModelScan`), and continuous AI red-teaming.



- **[HiddenLayer](https://hiddenlayer.com)**  

  Enterprise AI security platform delivering real-time adversarial attack detection, prompt injection monitoring, model scanning, and automated AI red-teaming.



- **[Arthur Shield (Arthur AI)](https://arthur.ai)**  

  Real-time LLM firewall and observability suite providing prompt injection detection, PII/sensitive data filtering, hallucination scoring, and toxicity guardrails.



- **[Patronus AI](https://patronus.ai)**  

  Automated AI safety and evaluation platform featuring adversarial red-team test generation, specialized hallucination detection models (Lynx), and compliance guardrails.



- **[Fiddler AI (Fiddler Guardrails)](https://fiddler.ai)**  

  Enterprise AI observability and governance platform offering sub-100ms safety, jailbreak, PII, and faithfulness guardrails alongside drift monitoring.



- **[Aporia Guardrails](https://aporia.com)**  

  Customizable real-time AI guardrail platform allowing teams to define and enforce custom behavioral, hallucination, and prompt-injection policies in milliseconds.



- **[Cisco AI Defense (formerly Robust Intelligence)](https://cisco.com)**  

  Enterprise AI validation and runtime protection suite providing automated algorithmic red-teaming, model supply-chain risk assessment, and real-time runtime guardrails.



- **[Guardrails AI Hub (Cloud)](https://guardrailsai.com)**  

  Hosted validator registry and server infrastructure for deploying composable input/output guardrails, structured schema validation, and PII filters in production.



- **[E2B Cloud](https://e2b.dev)**  

  Managed cloud infrastructure providing isolated Firecracker MicroVM sandboxes specifically engineered for safely executing untrusted AI agent code and shell commands.





## Open-Source GitHub Projects



- **[Lee-xeo/Claude-Cage](https://github.com)**  

  Open-source sandboxing wrapper and isolation cage engineered specifically for running Claude Code and autonomous terminal agents safely with restricted filesystem, network, and process boundaries.



- **[NVIDIA NeMo Guardrails (`NVIDIA/NeMo-Guardrails`)](https://github.com)**  

  Flagship open-source (`Apache-2.0`) programmable guardrail toolkit using Colang to add topical, safety, jailbreak, and tool-execution rails to conversational and agentic LLM systems.



- **[Guardrails AI (`guardrails-ai/guardrails`)](https://github.com)**  

  Popular open-source (`Apache-2.0`) Python framework and validator Hub for enforcing structural, semantic, PII, and safety guarantees on LLM inputs and outputs.



- **[LLM Guard (`protectai/llm-guard`)](https://github.com)**  

  Comprehensive open-source (`MIT`) security toolkit by Protect AI providing local scanners for prompt injection detection, PII anonymization, secrets scanning, toxicity filtering, and output sanitization.



- **[Llama Guard & Purple Llama (`meta-llama/PurpleLlama`)](https://github.com)**  

  Open-weight (`Llama Community License`) input-output safeguard models (`Llama Guard 3` / `Prompt Guard`) and CyberSecEval benchmarks from Meta for classifying prompt injections and policy violations.



- **[E2B Code Interpreter / Infra (`e2b-dev/code-interpreter`)](https://github.com)**  

  Open-source (`Apache-2.0`) SDK and sandbox runtime enabling autonomous AI agents to execute untrusted Python, JavaScript, and Bash code inside isolated cloud or self-hosted MicroVMs.



- **[Firecracker (`firecracker-microvm/firecracker`)](https://github.com)**  

  Open-source (`Apache-2.0`) lightweight Virtual Machine Monitor (VMM) built in Rust by AWS providing hardware-level KVM isolation for multi-tenant AI code-execution sandboxes.



- **[gVisor (`google/gvisor`)](https://github.com)**  

  Open-source (`Apache-2.0`) application kernel for containers from Google providing defense-in-depth syscall interception and OCI (`runsc`) sandboxing for AI agent workloads.



- **[Bubblewrap (`containers/bubblewrap`) & Sandbox-Exec Profiles](https://github.com)**  

  Lightweight open-source (`LGPL-2.0+`) unprivileged Linux sandboxing tool used under the hood by modern coding-agent cages (`Claude Code`, `Codex CLI`) to isolate filesystem mounts and namespaces.



- **[PyRIT (`Azure/PyRIT`)](https://github.com)**  

  Microsoft's open-source (`MIT`) Python Risk Identification Tool for generative AI enabling security teams to automate multi-turn adversarial red-teaming and prompt-injection stress testing.



- **[Garak (`NVIDIA/garak`)](https://github.com)**  

  Open-source (`Apache-2.0`) LLM vulnerability scanner from NVIDIA that probes language models and endpoints for prompt injections, jailbreaks, encoding bypasses, and data leakage.



- **[Microsoft Presidio (`microsoft/presidio`)](https://github.com)**  

  Industry-standard open-source (`MIT`) context-aware PII detection and anonymization SDK for scrubbing sensitive names, credentials, and financial/medical identifiers before LLM ingestion.



- **[Rebuff (`protectai/rebuff`) & Vigil (`deadbits/vigil-llm`)](https://github.com)**  

  Open-source (`Apache-2.0` / `MIT`) multi-layered prompt-injection detection frameworks combining heuristics, vector similarity signatures, canary tokens, and LLM classifiers.



- **[ModelScan (`protectai/modelscan`)](https://github.com)**  

  Open-source (`Apache-2.0`) model serialization security scanner detecting arbitrary code execution exploits (`pickle`, `SavedModel`, `Keras`) hidden inside downloaded open-weight models.



- **[Open Policy Agent / OPA (`open-policy-agent/opa`)](https://github.com)**  

  General-purpose open-source (`Apache-2.0`) declarative policy engine (`Rego`) increasingly paired with MCP gateways and AI agents to enforce fine-grained tool-call authorization rails.



- **[LiteLLM Guardrails (`BerriAI/litellm`)](https://github.com)**  

  Open-source (`MIT`) AI gateway supporting pre-call and post-call guardrail hooks (`Presidio`, `Lakera`, `Llama Guard`, `Bedrock Guardrails`) across 100+ LLM endpoints.



### Additional Strong Open-Source Options



- **[OpenSandbox / Docker Sandboxes (`docker/mcp-gateway`)](https://github.com)** and **[CUA (`trycua/cua`)](https://github.com)** for containerized MCP tool isolation and hardware-virtualized macOS/Linux desktop agent sandboxes.

- **[Promptfoo (`promptfoo/promptfoo`)](https://github.com)** for automated CI/CD red-teaming against OWASP Top 10 for LLMs, indirect prompt injections, and jailbreak suites.

- **[ShieldGemma (`google-deepmind/gemma`)](https://github.com)** and **[WildGuard (`allenai/wildguard`)](https://github.com)** for compact, open-weight safety moderation and refusal/jailbreak classifier models runnable locally.

- **[Gitleaks (`gitleaks/gitleaks`)](https://github.com)** and **[TruffleHog (`trufflesecurity/trufflehog`)](https://github.com)** for preventing AI coding agents from leaking or committing API keys, tokens, and secrets.

- **[nsjail (`google/nsjail`)](https://github.com)** and **[Landlock / Seatbelt CLI wrappers](https://github.com)** for lightweight process, network, and syscall sandboxing of untrusted agent subprocesses.
