# Awesome-Autonomous-Penetration-Testing

# Top Autonomous Penetration Testing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Agentic Exploit Validation, Multi-Agent Red Teaming & CI/CD Security Gates*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Autonomous Penetration Testing**. These tools enable organizations to run continuous, agent-driven security assessments that don't just flag "possible" issues—they exploit what they find, prove it with a working proof-of-concept, and ship merge-ready fixes.

**Examples** include Horizon3.ai, Pentera, Cymulate, SafeBreach, AttackIQ, Picus Security, RidgeBot, XM Cyber, Vonahi Security, and BreachLock (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, multi-agent orchestration, and open exploit validation—ideal for security engineers, red teams, and developers seeking transparent, vendor-independent autonomous pentesting.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Horizon3.ai NodeZero](https://horizon3.ai/)**  
  **The most experienced AI hacker**, trusted by 6,500+ organizations including the NSA, CISA, four Fortune 10 companies, and major banks. Runs **production-safe autonomous pentests** that chain vulnerabilities across web apps, infrastructure, cloud, data, and identity—proving real business impact. **Critical design choice**: generative models never write or fire exploits; attacks are deterministic and pre-validated, with AI picking targets and writing summaries. Raised **$250M Series E at $2B+ valuation**, 120% YoY ARR growth.

- **[Pentera](https://pentera.io/)**  
  Exposure validation platform trusted by **1,000+ CISOs** globally. Combines **deterministic attack emulation with agentic AI adaptability** to continuously validate security across internal networks, external surfaces, and cloud identity. Reports **80% reduction in cyber risk**, **60% reduction in third-party pentesting costs**, and **90% faster MTTR**.

- **[Cymulate](https://cymulate.com/)**  
  Breach and attack simulation platform with autonomous attack path validation.

- **[SafeBreach](https://www.safebreach.com/)**  
  Continuous security validation platform with 20,000+ attack simulations.

- **[AttackIQ](https://www.attackiq.com/)**  
  Breach and attack simulation platform aligned with MITRE ATT&CK.

- **[Picus Security](https://www.picussecurity.com/)**  
  Security control validation platform with automated attack simulation.

- **[RidgeBot](https://ridgebot.com/)**  
  Autonomous penetration testing platform with AI-driven exploitation.

- **[XM Cyber](https://xmcyber.com/)**  
  Hybrid cloud security platform with attack path management.

- **[Vonahi Security](https://vonahi.com/)**  
  Automated penetration testing platform.

- **[BreachLock](https://www.breachlock.com/)**  
  Human-delivered and AI-augmented penetration testing as a service (PTaaS).

## Open-Source GitHub Projects

- **[Strix](https://github.com/strix-ai/strix)**  
  **The leading open-source AI-native pentest framework** (Apache-2.0) . **66,000+ GitHub stars**—one of the most-starred projects in this category . **Runs autonomous AI agents that behave like real attackers**—they run your code dynamically, probe for vulnerabilities across the OWASP Top 10 and beyond, and **validate every finding with a working proof-of-concept exploit** rather than a "possible issue" flag . **Multi-agent architecture** specializes agents by phase (reconnaissance, exploitation, reporting) that share findings and chain them into larger attack paths . **Docker-based with a strong self-hosting path** . **The benchmark test against vulnbank.org identified multiple critical vulnerabilities including confirmed blind SQL injection with timing-based confirmation (CVSS 10.0)** and mapped a comprehensive attack surface with 40+ endpoints identified . **The strongest all-around pick for teams starting out** .

- **[PentAGI](https://github.com/vxcontrol/pentagi)**  
  **The most comprehensive open-source autonomous AI penetration testing system** (MIT) . **8,200+ GitHub stars** . **Organizes work into a hierarchy of flows, tasks, subtasks, and actions** . **Orchestrator agent coordinates three specialist agents**: **Researcher** (gathers information and queries known vulnerability sources), **Developer** (plans attack strategies and writes customised exploit code in real time), and **Executor** (runs commands in isolated containers, drawing on 20+ specialized security tools including Nmap, Metasploit, and SQLmap) . **All operations happen inside sandboxed Docker environments** with default Kali Linux image pre-loaded with security tools . **Three memory layers**: long-term vector storage, working context, and episodic history, backed by PostgreSQL with pgvector for semantic search . **Chain summarization algorithm** for growing LLM context windows . **Optional Graphiti knowledge graph** (Neo4j) stores semantic relationships between tools, targets, vulnerabilities, and techniques across sessions . **LLM provider flexibility**: OpenAI, Anthropic, Google Gemini, AWS Bedrock, Ollama, DeepSeek, OpenRouter . **REST and GraphQL APIs** with Bearer token authentication for CI/CD integration . **Deployment via Docker Compose**—minimum 2 vCPUs, 4GB RAM, 20GB disk . **MIT licensed and 100% free** .

- **[pentest-agent (isaacs-12)](https://github.com/isaacs-12/pentest-agent)**  
  **Agentic penetration testing with 67+ offensive security skills** (open-source) . **The most skill-comprehensive open-source pentest agent** . **Skill registry covering**: **Injection** (SQLi, XSS, SSTI, command injection, NoSQL injection, XXE, path traversal), **Auth attacks** (JWT manipulation including alg:none bypass and algorithm confusion, session fixation, auth bypass, IDOR), **Exploitation** (race conditions, request smuggling, prototype pollution, deserialization, Metasploit integration), **Fuzzing** (parameter discovery, directory brute-force), **Network** (SMB/SNMP enumeration, credential brute-force), **Cloud** (S3/Azure/GCP bucket misconfiguration checks), and **Stress testing** (Slowloris, resource exhaustion) . **Agent follows aggressive methodology**: Recon → Discovery → Injection → Auth attacks → Exploitation → Chaining → Stress testing . **Doesn't just report "possible SQL injection"—it proves it with extracted data, achieved RCE, or bypassed authentication** . **Custom skills can be added via BaseSkill class** .

- **[Vibe Hacking Agent](https://www.rtrvr.ai/newsletters/vibe-hacking-rover-gemini-flash-lite)**  
  **Autonomous multi-agent based red team testing service** (open-source Rover harness) . **Reverse-engineers site APIs from inside your browser** . **The agent acts on the page, uncovers network calls, and generates reusable extraction scripts at scale** . **Demo results**: used Vibe Hacking to scrape X profiles that OpenClaw founder Peter Steinberger follows—**despite X's UI limits to 50 profiles** . **HTTP scraping is the fastest and cheapest method**—instead of a thousand page actions, the agent generates code for 1,000 API calls and runs them in seconds for pennies . **Browser context provides the strongest anti-bot footing**—headers and authorization propagate automatically, no rebuilding the site's auth stack by hand . **Rover harness is now open-sourced**—drop it into your own stack or pair with cloud browser for cross-domain workflows . **Upgraded to Gemini 3.1 Flash Lite as default model**—validated as good enough for daily-driving agentic tasks, with **500 requests/day free on the AI Studio tier** .

- **[VulnClaw](https://pypi.org/project/vulnclaw/)**  
  **AI-driven penetration testing CLI tool** (open-source) . **Natural language input → automatic full penetration testing workflow** . **The most user-friendly open-source pentest CLI**—"说人话，打漏洞" (speak human, hit vulnerabilities) . **Round-based execution**: Round 1 (information gathering → fingerprinting, port scanning, directory enumeration), Round 2 (vulnerability discovery → injection points, known CVEs, configuration flaws), Round 3 (exploitation → PoC validation, privilege acquisition), Round 4 (report generation → structured report + Python PoC scripts) . **13 LLM providers**: OpenAI, Anthropic, MiniMax, DeepSeek, Zhipu, Moonshot, Qwen, SiliconFlow, Doubao, StepFun, SenseTime, OpenRouter, and local Ollama . **MCP tool chain** with 4 services: fetch/memory (built-in), chrome-devtools/burp (external MCP services for browser automation and HTTP capture/replay) . **50 specialized skills** covering CTF, Web, internal network, reverse engineering, vulnerability validation, and authorized red team knowledge base . **Evidence-level anti-hallucination gate**—claimed flags/conclusions must appear character-by-character in real tool output to be accepted, preventing fabricated flags . **The most accessible open-source pentest tool for Chinese-speaking security professionals** .

- **[PentestAgent (nbshenxm)](https://github.com/nbshenxm/pentest-agent)**  
  **Novel LLM-driven penetration testing framework** (open-source, ACM published) . **Modular three-agent architecture**: **Reconnaissance Agent** (gathers intelligence about target system), **Planning Agent** (identifies and prioritizes vulnerabilities and potential exploits), **Execution Agent** (attempts to execute selected exploits in controlled environment) . **CVE scoring criteria**: vulnerability type, exploit maturity, remote exploitability, attack complexity, source weighting (ExploitDB, GitHub, Google) . **Requires ProjectDiscovery API key, GitLab token, GitHub token** for CVE data access . **Recommended deployment on Kali Linux** .

- **[Vibe Hacker](https://www.npmjs.com/package/vibehacker)**  
  **Terminal AI cybersecurity assistant with autonomous agent mode** (open-source, NPM) . **100% free—works with free-tier API keys, no credit card needed** . **Hunt mode gives the AI 10 tools**: read_file, edit_file, write_file, execute_command, grep, glob, list_files, search_files, create_directory, delete_file . **13 AI providers with smart rotation**—auto-switches on rate limits with circuit breaker protection . **50 free requests/day with zero setup**; add your own free API keys for unlimited usage . **Surgical edit** with exact string replacement, mtime conflict detection, and undo support . **Project memory** reads VIBEHACKER.md for project-specific instructions . **The most accessible free terminal security assistant** .

- **[zimkk-vigil](https://pypi.org/project/zimkk-vigil/)**  
  **Open-source AI-assisted red-team orchestration framework** (MIT) . **18 canonical engagement phases** from passive_recon through reporting . **Controller-driven engagement flow** with queueing, snapshots, and resume support . **SQLite runtime state** with schema normalization . **Deterministic final reporting** from persisted evidence . **CLI and Textual TUI** for interactive operation . **Supports Anthropic and OpenAI-compatible backends** (Ollama, vLLM, LM Studio, OpenRouter) . **The most structured open-source red team orchestration framework** .

### Additional Strong Open-Source Options

- **[CAI (Cybersecurity AI)](https://github.com/aliasrobotics/cai)** — Open-source framework for building and deploying AI agents for offensive and defensive security tasks (open-source) . **Native support for 300+ models** including OpenAI, Anthropic, DeepSeek, and local Ollama . **Pre-configured tools for reconnaissance, exploitation, and privilege escalation** . **Built-in security protocols against prompt injection** . **Validated in CTF environments, bug bounty programs, and professional assessments** .
- **[Nebula](https://github.com/berylliumsec/nebula)** — Open-source penetration testing assistant that integrates LLMs directly into the CLI (open-source) . **Interprets terminal outputs in real-time and provides suggestions** . **Automated note-taking mapped to CWE and NIST** . **Integrated evidence capture** with screenshots and highlights . **Action logging** maintains comprehensive audit trail . **Interactive AI terminal assistant, not a fully autonomous tool** .
- **[Faraday](https://github.com/infobyte/faraday)** — Open-source vulnerability management platform (GPL-3.0) . **Ingests and deduplicates output from 80+ tools** (Nmap, Nessus, Burp, Nuclei, Metasploit) . **Docker Compose with PostgreSQL** . **Built for pentest and red-team collaboration** .
- **[Nuclei](https://github.com/projectdiscovery/nuclei)** — Fast, YAML-template-driven scanner (MIT) . **Community-maintained template library** with new templates shipping within days of major CVE disclosures . **AI-assisted template generation** (2025-2026) .
- **[PentestGPT](https://github.com/GreyDGL/PentestGPT)** — LLM co-pilot for human testers (open-source) . **Maintains running "task tree" of engagement** . **Suggests next logical step and generates specific commands** . **Open-source and free** .
- **[Metasploit Framework](https://github.com/rapid7/metasploit-framework)** — Industry-standard exploitation framework (BSD-3-Clause) . **Vast, actively maintained catalogue of validated exploits** . **Community edition free** .
- Community **n8n** workflows for pentest automation and finding triage.

**Frameworks for building custom systems**: Combine **Strix** for autonomous exploit validation with **PentAGI** for multi-agent orchestration, **pentest-agent (isaacs-12)** for comprehensive offensive skills, **VulnClaw** for natural language pentest workflows, and **zimkk-vigil** for structured red team orchestration—creating a fully self-hosted, enterprise-grade autonomous pentesting platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Autonomous penetration testing must be authorized. **Never run these tools against systems you do not own or have explicit written permission to test.** Unauthorized testing is illegal under CFAA, Computer Misuse Act, and equivalent laws worldwide.
- **Autonomous pentesting has a reliability ceiling.** Independent research testing an internal web application found agents surfaced relevant minor improvement areas but **completely missed an exposed admin interface with default credentials**—a vulnerability no human pentester would overlook. Reports also included a non-existent critical vulnerability (JWT algorithm confusion) with non-working proof-of-exploit scripts.
- **Non-determinism is visible.** Two runs against the same target can produce substantially different findings and reports. Without insufficient scope controls, some models attempt to expand assessment scope by probing adjacent ports, applications, or subdomains.
- **Business logic understanding remains shallow.** Outputs align strongly with generic OWASP-style patterns and may not challenge real business risk or abuse scenarios in sufficiently contextual ways.
- **Sovereignty and confidentiality matter.** Offensive security assessments consolidate highly sensitive technical information about organizational weaknesses. SaaS LLM dependency raises questions about prompts, traces, findings, and attack hypotheses leaving your environment. Data anonymization before LLM step may not be reliable mitigation.
- **Human validation still matters.** Even frontier-grade models miss critical vulnerabilities and produce false positives. Combine autonomous tools with human review and retesting for production-grade assurance. Legacy scanners find issues; automated pentesting proves which ones attackers could exploit.
- Self-hosted open-source solutions require proper security hardening, API key management, and ongoing maintenance. **Autonomous agents consume significant LLM tokens**—set spending limits and monitor usage.
