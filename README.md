# Awesome-Generative-AI-Cybersecurity-Assistant

# Awesome-Generative-AI-Cybersecurity-Assistant

# Awesome-Generative-AI-Cybersecurity-Assistant

## Top Generative AI Cybersecurity Assistant Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on AI-Powered SOC Assistance, Threat Triage, Investigation Copilots, Natural-Language Query & Agentic Security Response*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Generative AI Cybersecurity Assistants**. These systems use large language models and agentic AI to help security analysts triage alerts, investigate incidents, generate queries, hunt threats, and accelerate response—acting as copilots or autonomous helpers inside the SOC.

**Examples** include Microsoft Security Copilot, CrowdStrike Charlotte AI, SentinelOne Purple AI, Google Cloud Security AI Workbench, Palo Alto Cortex Copilot, Recorded Future AI, Trellix GenAI, Cisco AI Assistant, Fortinet GenAI, and Darktrace HEAL (the category leaders).

**Open-source emphasis**: Enterprise GenAI security assistants are tightly coupled to commercial platforms. Strong open building blocks exist for **cybersecurity-tuned LLMs**, **LLM-based triage**, **red-teaming frameworks**, and **agent security tooling**. This section expands those while remaining realistic about the commercial gap for full production SOC copilots.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Microsoft Security Copilot](https://www.microsoft.com/en-us/security/business/ai-machine-learning/microsoft-security-copilot)**  
  Generative AI security assistant integrated across Microsoft Defender, Sentinel, Entra, and related products—supports natural-language investigation, KQL generation, and guided response.

- **[CrowdStrike Charlotte AI](https://www.crowdstrike.com/platform/charlotte-ai/)**  
  Generative and agentic AI layer on the Falcon platform that accelerates detection triage, investigation, and threat hunting with high claimed decision accuracy.

- **[SentinelOne Purple AI](https://www.sentinelone.com/)**  
  GenAI security analyst built into the Singularity platform—enables plain-English threat hunting, auto-investigation, and autonomous verification flows.

- **[Google Cloud Security AI Workbench](https://cloud.google.com/security)**  
  Google’s AI-assisted security tooling within Chronicle, Security Command Center, and related Google Cloud security services.

- **[Palo Alto Cortex Copilot](https://www.paloaltonetworks.com/cortex)**  
  Generative AI assistant within the Cortex XSIAM/XDR ecosystem for investigation, hunting, and response acceleration.

- **[Recorded Future AI](https://www.recordedfuture.com/)**  
  AI-enhanced threat intelligence capabilities that assist analysts with summarization, prioritization, and contextual investigation.

- **[Trellix GenAI](https://www.trellix.com/)**  
  Generative AI features within the Trellix security portfolio for detection, investigation, and operational assistance.

- **[Cisco AI Assistant](https://www.cisco.com/)**  
  AI assistance offerings across Cisco security products, including open-source AI security tooling from Cisco AI Defense.

- **[Fortinet GenAI](https://www.fortinet.com/)**  
  Generative AI capabilities integrated into Fortinet’s Security Fabric for threat analysis and SOC support.

- **[Darktrace HEAL](https://darktrace.com/)**  
  AI-driven autonomous response and recovery capabilities that complement Darktrace’s detection and investigation AI.

## Open-Source GitHub Projects
- **[CyberGuardian](https://github.com/unibuc-cs/CyberGuardian)**  
  Open LLM fine-tuned for cybersecurity tasks, with interactive assistant UI for specialists.

- **[SecureBERT / cybersecurity domain models](https://github.com/)**  
  Domain-adapted language models for cybersecurity intelligence, NER, semantic search, and threat analysis.

- **[Garak](https://github.com/leondz/garak)**  
  Open-source LLM vulnerability scanner (“Nmap for LLMs”) useful for testing security assistants and models.

- **[PyRIT](https://github.com/Azure/PyRIT)**  
  Microsoft’s open-source red-teaming framework for generative AI—automates multi-turn adversarial testing.

- **[Cisco AI Defense open tools](https://cisco-ai-defense.github.io/)**  
  Collection of open-source scanners and tools for AI agent security, MCP scanning, skill scanning, and AI BOM generation.

- **[LLM triage and autotriage projects](https://github.com/)**  
  Community tools that use LLMs to prioritize, deduplicate, and classify security findings (e.g., SARIF, scanner output).

- **[Offensive and defensive security fine-tunes](https://github.com/)**  
  Open-weight models fine-tuned on cybersecurity corpora for penetration testing, threat analysis, and SOC assistance.

- **[Agent security frameworks](https://github.com/ProjectRecon/awesome-ai-agents-security)**  
  Curated open tools for securing AI agents, including gateways, red-teaming, and runtime protection.

- **[Documentation and local LLM security playbooks](https://github.com/)**  
  Guides for running cybersecurity-tuned models with Ollama, vLLM, or llama.cpp for private SOC assistance.

- **[Self-hosted GenAI security assistant stacks](https://github.com/)**  
  Patterns combining open LLMs + RAG over internal threat intel + SIEM query generation for private copilots.

### Additional Strong Open-Source Options
- Running cybersecurity-tuned open LLMs locally for private investigation assistance.
- Using **Garak** and **PyRIT** to stress-test any GenAI security assistant.
- Building RAG-based copilots over internal runbooks, MITRE ATT&CK, and ticket history.
- Accepting that production-grade, platform-integrated, high-accuracy SOC copilots with agentic action still require commercial platforms (Security Copilot, Charlotte AI, Purple AI, Cortex Copilot, etc.).
- Focusing open-source efforts on model transparency, private deployment, and independent evaluation of AI security claims.

**Frameworks for building custom systems**: Fine-tune or RAG a cybersecurity LLM → connect to SIEM/EDR APIs → generate queries and summaries → keep humans in the loop for response. Suitable for research and privacy-sensitive SOCs. Most enterprises adopt vendor copilots tightly integrated with their existing security stack.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Generative AI security assistants can hallucinate, miss context, or suggest unsafe actions. They must be used with human oversight and proper access controls. This list is not security or operational advice.

---
**Made for SOC analysts, detection engineers, and open security AI advocates.**
Let's keep defense faster, smarter, and as open as practical.
