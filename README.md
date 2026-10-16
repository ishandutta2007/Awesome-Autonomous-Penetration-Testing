# Awesome-Autonomous-Penetration-Testing

## Top Autonomous Penetration Testing Ecosystem



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

| Platform | Category / Focus | Key Capabilities & Highlights | Pricing / Starting Tier | Free Tier Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Horizon3.ai NodeZero](https://horizon3.ai/)** | Autonomous Penetration Testing | Production-safe autonomous pentests chaining vulnerabilities across web apps, infrastructure, cloud, data, and identity with deterministic attack validation and AI summarization. Trusted by 6,500+ orgs. | Custom quote (~$25,000–$50,000+/year based on hosts/IPs/assets) | No permanent free tier; free trial / 1-time scoped assessment available upon request |
| **[Pentera](https://pentera.io/)** | Automated Security Validation | Continuous exposure validation combining deterministic attack emulation with agentic adaptability across internal networks, external surfaces, and cloud identity. | Custom quote (~$75,000–$120,000+/year based on IP nodes & AD users) | No free tier; demo & guided evaluation available |
| **[Cymulate](https://cymulate.com/)** | Breach & Attack Simulation (BAS) | Continuous BAS and exposure management with modular attack vectors (email, web gateway, endpoint, WAF, lateral movement). | Custom quote (~$30,000–$60,000+/year modular/employee based) | 14-day free trial; no permanent free tier |
| **[SafeBreach](https://www.safebreach.com/)** | Breach & Attack Simulation (BAS) | Continuous security control validation with 20,000+ attack playbooks aligned with MITRE ATT&CK. | Custom quote (~$40,000–$80,000+/year based on simulator node count) | No free tier; guided interactive demo / PoC available |
| **[AttackIQ](https://www.attackiq.com/)** | Breach & Attack Simulation (BAS) | Enterprise BAS control validation platform mapped to MITRE ATT&CK and MITRE D3FEND. | Custom quote (~$50,000–$100,000+/year platform license) | Free educational access via AttackIQ Academy; platform requires paid enterprise license |
| **[Picus Security](https://www.picussecurity.com/)** | Security Control Validation | Automated attack simulation and threat exposure management with mitigation validation. | Custom quote (~$35,000–$70,000+/year based on integration scope) | No free tier; 14-day free trial / guided demo available |
| **[RidgeBot](https://ridgebot.com/)** | Autonomous Penetration Testing | AI-driven autonomous vulnerability discovery and exploit simulation across web, network, and cloud targets. | Custom quote (~$20,000–$45,000+/year based on target IP scope) | No free tier; proof-of-concept / evaluation license available |
| **[XM Cyber](https://xmcyber.com/)** | Continuous Exposure Management | Attack path management mapping relationships between identities, misconfigurations, and vulnerabilities to critical assets. | Custom quote (~$40,000–$90,000+/year based on total assets) | No free tier; enterprise demonstration & assessment PoC available |
| **[Vonahi Security (vPenTest)](https://vonahi.com/)** | Automated Network Penetration Testing | Automated internal and external network penetration testing built for enterprises and MSPs/MSSPs. | Custom quote (~$15,000–$35,000+/year or per-assessment scan credits) | No free tier; single-assessment trial available for qualified organizations/partners |
| **[BreachLock](https://www.breachlock.com/)** | Pentest-as-a-Service (PTaaS) | Hybrid model combining continuous AI-augmented automated scanning with certified human penetration testing. | Custom quote (~$15,000–$50,000+/year depending on asset count & retest cadence) | Free external attack surface assessment scanner; comprehensive PTaaS is paid |

## Open-Source GitHub Projects

*Sorted in descending order by GitHub Star count.*

- **[Strix](https://github.com/usestrix/strix)** [![GitHub Repo stars](https://img.shields.io/github/stars/usestrix/strix?style=social&color=white)](https://github.com/usestrix/strix/stargazers)  
  **The leading open-source AI-native pentest framework** (Apache-2.0). Runs autonomous AI agents that act like real attackers—dynamically exploring target applications, probing for vulnerabilities across the OWASP Top 10, and **validating findings with working proof-of-concept exploits**. Multi-agent architecture separates tasks into reconnaissance, exploitation, and reporting, chaining individual flaws into multi-stage attack paths. Docker-based with easy self-hosting.

- **[Metasploit Framework](https://github.com/rapid7/metasploit-framework)** [![GitHub Repo stars](https://img.shields.io/github/stars/rapid7/metasploit-framework?style=social&color=white)](https://github.com/rapid7/metasploit-framework/stargazers)  
  **Industry-standard exploitation framework** (BSD-3-Clause). The canonical offensive engine used worldwide by red teams and autonomous pentesting agents alike for reliable, modular payload delivery and vulnerability validation.

- **[Nuclei](https://github.com/projectdiscovery/nuclei)** [![GitHub Repo stars](https://img.shields.io/github/stars/projectdiscovery/nuclei?style=social&color=white)](https://github.com/projectdiscovery/nuclei/stargazers)  
  **Fast and customizable vulnerability scanner** (MIT). Driven by community-maintained YAML templates for automated vulnerability detection, protocol-level probing, and AI-assisted template generation across web applications and infrastructure.

- **[PentAGI](https://github.com/vxcontrol/pentagi)** [![GitHub Repo stars](https://img.shields.io/github/stars/vxcontrol/pentagi?style=social&color=white)](https://github.com/vxcontrol/pentagi/stargazers)  
  **Autonomous AI penetration testing system** (MIT). Organizes work into hierarchical flows, tasks, and actions coordinated by an Orchestrator agent across Researcher, Developer, and sandboxed Kali Linux Executor agents. Includes pgvector semantic memory, optional Neo4j Graphiti knowledge graph, and broad LLM backend support.

- **[Promptfoo](https://github.com/promptfoo/promptfoo)** [![GitHub Repo stars](https://img.shields.io/github/stars/promptfoo/promptfoo?style=social&color=white)](https://github.com/promptfoo/promptfoo/stargazers)  
  **Open-source automated AI red teaming & LLM security validation** (MIT). Automates adversarial penetration testing, prompt injection, and security fuzzing against LLMs, AI agents, and RAG architectures in CI/CD pipelines.

- **[PentestGPT](https://github.com/GreyDGL/PentestGPT)** [![GitHub Repo stars](https://img.shields.io/github/stars/GreyDGL/PentestGPT)](https://github.com/GreyDGL/PentestGPT/stargazers)  
  **LLM-driven automated penetration testing testing framework** (MIT). Operates using an interactive task tree mechanism (parsing, reasoning, and generation modules) to guide and execute end-to-end cyber assessments.

- **[HexStrike AI](https://github.com/0x4m4/hexstrike-ai)** [![GitHub Repo stars](https://img.shields.io/github/stars/0x4m4/hexstrike-ai?style=social&color=white)](https://github.com/0x4m4/hexstrike-ai/stargazers)  
  **Autonomous offensive cybersecurity orchestration framework via MCP** (GPL-3.0). Bridges AI models with 150+ security tools (Nmap, Metasploit, Nuclei, Gobuster, SQLmap) to conduct automated reconnaissance, vulnerability scanning, and exploit discovery.

- **[CAI (Cybersecurity AI)](https://github.com/aliasrobotics/cai)** [![GitHub Repo stars](https://img.shields.io/github/stars/aliasrobotics/cai?style=social&color=white)](https://github.com/aliasrobotics/cai/stargazers)  
  **AI agent framework for offensive and defensive security** (Apache-2.0). Features native multi-model support (OpenAI, Anthropic, DeepSeek, Ollama) and pre-configured agents for automated reconnaissance, vulnerability analysis, and privilege escalation.

- **[Faraday](https://github.com/infobyte/faraday)** [![GitHub Repo stars](https://img.shields.io/github/stars/infobyte/faraday?style=social&color=white)](https://github.com/infobyte/faraday/stargazers)  
  **Open-source collaborative penetration testing and vulnerability management platform** (GPL-3.0). Ingests and normalizes outputs from 80+ tools into an integrated attack graph and real-time dashboard.

- **[T3MP3ST](https://github.com/elder-plinius/T3MP3ST)** [![GitHub Repo stars](https://img.shields.io/github/stars/elder-plinius/T3MP3ST?style=social&color=white)](https://github.com/elder-plinius/T3MP3ST/stargazers)  
  **Autonomous red teaming platform and multi-agent offensive security meta-harness**. Coordinates autonomous security probing and adversarial exploitation pipelines across targets.

- **[VulnClaw](https://github.com/Netw0rkNoob/VulnClaw)** [![GitHub Repo stars](https://img.shields.io/github/stars/Netw0rkNoob/VulnClaw?style=social&color=white)](https://github.com/Netw0rkNoob/VulnClaw/stargazers)  
  **AI-driven penetration testing CLI tool** (Apache-2.0). Provides round-based automated pentesting (information gathering → vulnerability discovery → exploitation → report generation) with MCP toolchain integrations and anti-hallucination validation gates.

- **[Cairn](https://github.com/oritera/Cairn)** [![GitHub Repo stars](https://img.shields.io/github/stars/oritera/Cairn?style=social&color=white)](https://github.com/oritera/Cairn/stargazers)  
  **AI state-space search engine designed for autonomous penetration testing**. Formulates penetration testing as a state-space traversal problem to systematically discover, evaluate, and navigate attack vectors to target objectives.

- **[RedAmon](https://github.com/samugit83/redamon)** [![GitHub Repo stars](https://img.shields.io/github/stars/samugit83/redamon?style=social&color=white)](https://github.com/samugit83/redamon/stargazers)  
  **Self-hosted AI penetration testing framework** (Apache-2.0). Maps attack surfaces into graphs, autonomously exploits them from sandboxed Kali containers with human approval gates, and generates pull requests to remediate identified flaws.

- **[Pentest-Swarm-AI](https://github.com/Armur-Ai/Pentest-Swarm-AI)** [![GitHub Repo stars](https://img.shields.io/github/stars/Armur-Ai/Pentest-Swarm-AI?style=social&color=white)](https://github.com/Armur-Ai/Pentest-Swarm-AI/stargazers)  
  **Multi-agent autonomous penetration testing swarm** (Apache-2.0). Built with Go, coordinating recon, classification, exploitation, and reporting specialist agents with ReAct reasoning across bug bounty and continuous monitoring targets.

- **[Xalgorix](https://github.com/xalgorix/xalgorix)** [![GitHub Repo stars](https://img.shields.io/github/stars/xalgorix/xalgorix?style=social&color=white)](https://github.com/xalgorix/xalgorix/stargazers)  
  **Autonomous AI pentesting agents** (Go + TypeScript). Delivers real-time target reconnaissance, vulnerability assessment, and exploit orchestration in automated workflows.

- **[Nebula](https://github.com/berylliumsec/nebula)** [![GitHub Repo stars](https://img.shields.io/github/stars/berylliumsec/nebula?style=social&color=white)](https://github.com/berylliumsec/nebula/stargazers)  
  **AI-assisted penetration testing terminal co-pilot** (GPL-3.0). Integrates directly with shell sessions, offering real-time command suggestions, automated CWE/NIST note-taking, and evidence logging.

- **[Pentest-Agents](https://github.com/H-mmer/pentest-agents)** [![GitHub Repo stars](https://img.shields.io/github/stars/H-mmer/pentest-agents?style=social&color=white)](https://github.com/H-mmer/pentest-agents/stargazers)  
  **Offensive agent framework and exploit-chain builder**. Features 48 specialized agents, 26 automation commands, and MCP servers compatible with Claude Code, Cursor, and terminal agents.

- **[APTS](https://github.com/OWASP/APTS)** [![GitHub Repo stars](https://img.shields.io/github/stars/OWASP/APTS?style=social&color=white)](https://github.com/OWASP/APTS/stargazers)  
  **OWASP Autonomous Penetration Testing Standard**. Community-driven standardization framework specifying architectures, safety bounds, evaluation criteria, and methodologies for autonomous pentesting agents.

- **[HackSynth](https://github.com/aielte-research/HackSynth)** [![GitHub Repo stars](https://img.shields.io/github/stars/aielte-research/HackSynth?style=social&color=white)](https://github.com/aielte-research/HackSynth/stargazers)  
  **LLM agent and evaluation benchmark framework for autonomous penetration testing**. Evaluates LLM reasoning and real-world attack trajectory success across captured flags and enterprise scenarios.

- **[VulnBot](https://github.com/KHenryAegis/VulnBot)** [![GitHub Repo stars](https://img.shields.io/github/stars/KHenryAegis/VulnBot?style=social&color=white)](https://github.com/KHenryAegis/VulnBot/stargazers)  
  **Multi-agent collaborative framework for autonomous penetration testing**. Employs cooperative multi-agent task planning and execution strategies for systematic vulnerability discovery and validation.

- **[Autonomous Pentest Agent](https://github.com/kutukam/autonomous-pentest-agent)** [![GitHub Repo stars](https://img.shields.io/github/stars/kutukam/autonomous-pentest-agent?style=social&color=white)](https://github.com/kutukam/autonomous-pentest-agent/stargazers)  
  **Full-stack autonomous pentesting system** (AGPL-3.0). Combines a Go backend orchestrator with an intuitive Next.js web dashboard to run end-to-end automated security assessments.

- **[PentestAgent](https://github.com/nbshenxm/pentest-agent)** [![GitHub Repo stars](https://img.shields.io/github/stars/nbshenxm/pentest-agent?style=social&color=white)](https://github.com/nbshenxm/pentest-agent/stargazers)  
  **Academic LLM-driven penetration testing framework** (ACM published). Uses a three-agent modular architecture (Reconnaissance, Planning, Execution) with quantitative CVE scoring models for automated exploitation in Kali Linux environments.

- **[pentest-agent (isaacs-12)](https://github.com/isaacs-12/pentest-agent)** [![GitHub Repo stars](https://img.shields.io/github/stars/isaacs-12/pentest-agent?style=social&color=white)](https://github.com/isaacs-12/pentest-agent/stargazers)  
  **Agentic penetration testing with 67+ offensive security skills**. Comprehensive skill registry spanning injection attacks, authentication bypasses, race conditions, request smuggling, and network discovery.

- Community **n8n** workflows for pentest automation and finding triage.

**Frameworks for building custom systems**: Combine **Strix** for autonomous exploit validation with **PentAGI** or **HexStrike AI** for multi-agent orchestration, **Promptfoo** for AI/LLM evaluation gates, **Faraday** for centralized vulnerability management, and **APTS** for OWASP compliance.



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
