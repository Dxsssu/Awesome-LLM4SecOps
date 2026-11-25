# Awesome LLM4SecOps

![Awesome LLM4SecOps](assets/awesome-llm4secops-banner.png)

A curated collection of papers, projects, datasets, benchmarks, and practical resources on **Large Language Models for Security Operations (LLM4SecOps)**. This repository covers threat detection, alert triage, threat intelligence, threat hunting, incident investigation, and response, including the security copilots, agents, and tool integrations that support these workflows.

## Contents

- [Surveys & Overviews](#surveys--overviews)
- [Threat Intelligence](#threat-intelligence)
- [Detection Engineering](#detection-engineering)
- [Alert Triage](#alert-triage)
- [Threat Hunting](#threat-hunting)
- [Incident Investigation & Response](#incident-investigation--response)
- [Security Copilots & Agents](#security-copilots--agents)
- [Datasets & Benchmarks](#datasets--benchmarks)

## Organization

Resources are organized by their primary security operations task and labeled by material type:

| Label | Material type |
| --- | --- |
| `Paper` | Academic research and survey papers, including preprints; excludes technical reports |
| `Open Source` | Open-source tools, libraries, and systems |
| `Product` | Commercial or hosted products |
| `Dataset` | Datasets and benchmarks, including logs, alerts, task data, and evaluation suites |
| `Report` | Technical reports, articles, guides, tutorials, documentation, and practical walkthroughs |

## Surveys & Overviews

Surveys and overviews of LLMs for security operations and foundational SecOps topics, including alert analysis, threat intelligence, and incident response. These resources cover key methods, evaluation practices, and open challenges.

- [[Paper](https://doi.org/10.1145/3769676)] Large Language Models for Cyber Security: A Systematic Literature Review, ACM Transactions on Software Engineering and Methodology, 2026.
- [[Paper](https://doi.org/10.1016/j.comnet.2026.112817)] The application of Large Language Model in system log analysis: A literature review, Computer Networks, 2026.
- [[Paper](https://doi.org/10.1007/s10115-026-02736-y)] Large language models for cyberattack defense: a critical survey, Knowledge and Information Systems, 2026.
- [[Paper](https://doi.org/10.1186/s42400-025-00361-w)] When LLMs meet cybersecurity: a systematic literature review, Cybersecurity, 2025.
- [[Paper](https://doi.org/10.1145/3747587)] Exploring the Role of Artificial Intelligence in Enhancing Security Operations: A Systematic Review, ACM Computing Surveys, 2025.
- [[Paper](https://doi.org/10.1016/j.comnet.2025.111614)] Large Language Models for computer networking operations and management: A survey on applications, key techniques, and opportunities, Computer Networks, 2025.
- [[Paper](https://doi.org/10.1145/3723158)] Alert Fatigue in Security Operations Centres: Research Challenges and Opportunities, ACM Computing Surveys, 2025.
- [[Paper](https://doi.org/10.1145/3772280)] A Comprehensive Survey of Threat Intelligence Research: A Measurement-Based Study, ACM Computing Surveys, 2025.
- [[Paper](https://doi.org/10.1016/j.cose.2024.104016)] A survey of large language models for cyber threat detection, Computers & Security, 2024.
- [[Paper](https://doi.org/10.1145/3695462)] Alert Prioritisation in Security Operations Centres: A Systematic Survey on Criteria and Methods, ACM Computing Surveys, 2024.
- [[Paper](https://doi.org/10.1145/3571726)] What Are the Attackers Doing Now? Automating Cyberthreat Intelligence Extraction from Text on Pace with the Changing Threat Landscape: A Survey, ACM Computing Surveys, 2023.
- [[Paper](https://doi.org/10.1109/COMST.2021.3117338)] A Comparative Study on Cyber Threat Intelligence: The Security Incident Response Perspective, IEEE Communications Surveys & Tutorials, 2021.
- [[Paper](https://doi.org/10.1145/3184898)] A Systematic Mapping Study on Intrusion Alert Analysis in Intrusion Detection Systems, ACM Computing Surveys, 2018.

- [[Report](https://assets.contentstack.io/v3/assets/bltabe50a4554f8e97f/blt953aed5dc46d4d60/sans-2026-soc-report)] 2026 SANS SOC Survey Insights: A Decade of Evolution in Cyber Defense, SANS Institute, 2026.
- [[Report](https://www.sans.org/white-papers/ai-human-collaboration-modern-socs)] AI-Human Collaboration in Modern SOCs, SANS Institute, 2026.
- [[Report](https://www.sans.org/white-papers/sans-2025-ai-survey-measuring-ai-impact-security-three-years-later)] SANS 2025 AI Survey: Measuring AI’s Impact on Security Three Years Later, SANS Institute, 2025.
- [[Report](https://www.mitre.org/sites/default/files/2022-04/11-strategies-of-a-world-class-cybersecurity-operations-center.pdf)] 11 Strategies of a World-Class Cybersecurity Operations Center, MITRE, 2022.

## Threat Intelligence

Threat report analysis, indicator extraction, threat actor profiling, and identification and mapping of tactics, techniques, and procedures (TTPs).

- [[Paper](https://doi.org/10.1109/TDSC.2026.3742408)] THREATPILOT: An Attack-Level Cyber Threat Intelligence Extraction Framework, IEEE Transactions on Dependable and Secure Computing, 2026.
- [[Paper](https://doi.org/10.1186/s42400-025-00505-y)] CTI-Thinker: an LLM-driven system for CTI knowledge graph construction and attack reasoning, Cybersecurity, 2026.
- [[Paper](https://doi.org/10.14722/ndss.2026.242926)] NEXUS: Towards Accurate and Scalable Mapping between Vulnerabilities and Attack Techniques, Network and Distributed System Security Symposium, 2026.
- [[Paper](https://doi.org/10.14722/ndss.2026.240102)] Actively Understanding the Dynamics and Risks of the Threat Intelligence Ecosystem, Network and Distributed System Security Symposium, 2026.
- [[Paper](https://www.usenix.org/conference/usenixsecurity25/presentation/buechel)] SoK: Automated TTP Extraction from CTI Reports – Are We There Yet?, USENIX Security Symposium, 2025.
- [[Paper](https://doi.org/10.14722/ndss.2025.230139)] Tweezers: A Framework for Security Event Detection via Event Attribution-centric Tweet Embedding, Network and Distributed System Security Symposium, 2025.
- [[Paper](https://doi.org/10.1016/j.cose.2024.104220)] AttacKG+: Boosting attack graph construction with Large Language Models, Computers & Security, 2025.
- [[Paper](https://doi.org/10.1007/s10115-025-02491-6)] Mining temporal attack patterns from cyberthreat intelligence reports, Knowledge and Information Systems, 2025.
- [[Paper](https://doi.org/10.1145/3719027.3765026)] Can IOCs Impose Cost? The Effects of Publishing Threat Intelligence on Adversary Behavior, ACM SIGSAC Conference on Computer and Communications Security, 2025.
- [[Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/5acd3c628aa1819fbf07c39ef73e7285-Abstract-Datasets_and_Benchmarks_Track.html)] CTIBench: A Benchmark for Evaluating LLMs in Cyber Threat Intelligence, Advances in Neural Information Processing Systems (Datasets and Benchmarks Track), 2024.
- [[Paper](https://www.ndss-symposium.org/ndss-paper/sharing-cyber-threat-intelligence-does-it-really-help/)] Sharing cyber threat intelligence: Does it really help?, Network and Distributed System Security Symposium, 2024.
- [[Paper](https://doi.org/10.1145/3607199.3607208)] Looking Beyond IoCs: Automatically Extracting Attack Patterns from External CTI, International Symposium on Research in Attacks, Intrusions and Defenses, 2023.
- [[Paper](https://doi.org/10.1007/978-3-031-17140-6_29)] AttacKG: Constructing Technique Knowledge Graph from Cyber Threat Intelligence Reports, European Symposium on Research in Computer Security, 2022.
- [[Paper](https://www.usenix.org/conference/usenixsecurity22/presentation/bouwman)] Helping hands: Measuring the impact of a large threat intelligence sharing community, USENIX Security Symposium, 2022.
- [[Paper](https://www.usenix.org/conference/usenixsecurity19/presentation/li)] Reading the Tea leaves: A Comparative Analysis of Threat Intelligence, USENIX Security Symposium, 2019.
- [[Paper](https://doi.org/10.1145/3134600.3134646)] TTPDrill: Automatic and Accurate Extraction of Threat Actions from Unstructured Text of CTI Sources, Annual Computer Security Applications Conference, 2017.

- [[Open Source](https://github.com/peng-gao-lab/CTINexus)] CTINexus: LLM-based extraction of entities and relationships from threat reports, with entity alignment and cybersecurity knowledge graph construction.
- [[Open Source](https://github.com/muchdogesec/txt2stix)] txt2stix: Extracts IoCs, TTPs, and their relationships from text using LLMs, patterns, and lookups, and exports STIX 2.1 bundles.
- [[Open Source](https://github.com/center-for-threat-informed-defense/tram)] TRAM: Maps threat report text to MITRE ATT&CK techniques using machine learning, with annotation tools and notebooks for adapting the models.
- [[Open Source](https://github.com/OpenCTI-Platform/opencti)] OpenCTI Community Edition: A platform for ingesting, organizing, and visualizing threat intelligence using a STIX-based knowledge model and integrations with external sources.
- [[Open Source](https://github.com/MISP/MISP)] MISP: A platform for collecting, correlating, and sharing structured threat intelligence, including indicators, threat actors, and attack techniques.
- [[Open Source](https://github.com/intelowlproject/IntelOwl)] IntelOwl: Enriches files and observables through multiple intelligence sources and analyzers, with APIs and connectors for integrating analysis results into CTI workflows.

## Detection Engineering

Detection rule and query generation, rule explanation and refinement, and detection coverage analysis.

- [[Paper](https://www.usenix.org/conference/usenixsecurity26/presentation/cai)] From Texts to Rules: Generating Sigma Rules with Large Language Models from Cyber Threat Reports, USENIX Security Symposium, 2026.

## Alert Triage

Alert enrichment, interpretation, deduplication, correlation, prioritization, and assessment of false positives.

- [[Paper](https://www.usenix.org/conference/usenixsecurity26/presentation/wu-weiheng)] Cutting the Fuse: Actionable APT Attack Blocking in Provenance-based IDS, USENIX Security Symposium, 2026.
- [[Paper](https://doi.org/10.14722/ndss.2025.230798)] Raconteur: A Knowledgeable, Insightful, and Portable LLM-Powered Shell Command Explainer, Network and Distributed System Security Symposium, 2025.
- [[Paper](https://doi.org/10.1109/SP40000.2020.00096)] Tactical Provenance Analysis for Endpoint Detection and Response Systems, IEEE Symposium on Security and Privacy, 2020.
- [[Paper](https://www.ndss-symposium.org/ndss-paper/nodoze-combatting-threat-alert-fatigue-with-automated-provenance-triage/)] NoDoze: Combatting Threat Alert Fatigue with Automated Provenance Triage, Network and Distributed System Security Symposium, 2019.

## Threat Hunting

Hunting hypothesis generation, query planning, proactive searches across security telemetry, and validation of suspicious activity.

- [[Paper](https://doi.org/10.14722/ndss.2026.230199)] KnowHow: Automatically Applying High-Level CTI Knowledge for Interpretable and Accurate Provenance Analysis, Network and Distributed System Security Symposium, 2026.
- [[Paper](https://doi.org/10.1145/3319535.3363217)] Poirot: Aligning Attack Behavior with Kernel Audit Records for Cyber Threat Hunting, ACM SIGSAC Conference on Computer and Communications Security, 2019.
- [[Paper](https://doi.org/10.1145/3243734.3243829)] Threat Intelligence Computing, ACM SIGSAC Conference on Computer and Communications Security, 2018.

## Incident Investigation & Response

Evidence analysis, timeline reconstruction, attack tracing, root cause analysis, response planning, and remediation workflows.

- [[Paper](https://doi.org/10.14722/ndss.2026.240358)] Incident Response Planning Using a Lightweight Large Language Model with Reduced Hallucination, Network and Distributed System Security Symposium, 2026.
- [[Paper](https://doi.org/10.1145/3719027.3765219)] OCR-APT: Reconstructing APT Stories from Audit Logs using Subgraph Anomaly Detection and LLMs, ACM SIGSAC Conference on Computer and Communications Security, 2025.
- [[Paper](https://doi.org/10.1109/SP54263.2024.00060)] Do You Play It by the Books? A Study on Incident Response Playbooks and Influencing Factors, IEEE Symposium on Security and Privacy, 2024.
- [[Paper](https://www.usenix.org/conference/usenixsecurity21/presentation/alsaheel)] ATLAS: A Sequence-based Learning Approach for Attack Investigation, USENIX Security Symposium, 2021.

## Security Copilots & Agents

Assistants and agent systems spanning multiple security operations tasks, including tool integration, workflow orchestration, human oversight, and operational reliability. Systems focused on a single task belong under that task's topic.

- [[Paper](https://doi.org/10.1109/SP63933.2026.00111)] LLMs in the SOC: An Empirical Study of Human-AI Collaboration in Security Operations Centres, IEEE Symposium on Security and Privacy, 2026.
- [[Paper](https://www.usenix.org/conference/usenixsecurity26/presentation/karanjai)] Context Contamination in LLM Analysis of Network Security Logs: Poison with Passive Prompt Injection and Mitigation Evaluation, USENIX Security Symposium, 2026.

## Datasets & Benchmarks

Shared datasets, evaluation suites, and simulation environments for LLM4SecOps, including task definitions, ground truth, evaluation protocols, and metrics.

- [[Paper](https://doi.org/10.14722/ndss.2026.240375)] Chimera: Harnessing Multi-Agent LLMs for Automatic Insider Threat Simulation, Network and Distributed System Security Symposium, 2026.
