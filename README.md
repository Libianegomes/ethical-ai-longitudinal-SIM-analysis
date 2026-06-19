# Ethical AI Longitudinal SIM Analysis

## Overview

This repository contains the empirical artifacts, inspection reports, and supporting evidence for the study:

**A Longitudinal Comparative Analysis of Ethical Principles Across System Versions**

The study investigates how explicit and implicit ethical principles evolve across different versions of generative artificial intelligence systems. The analysis applies the **Semiotic Inspection Method (SIM)** to compare communicative strategies, interface cues, documented policies, interaction behavior, ethical safeguards, and potential communicability breakdowns across system versions.

The repository is document-based. It contains PDF inspection reports, scenario materials, and supplementary visual evidence organized by ethical principle; it does not include executable source code, notebooks, or datasets in tabular format.

## Research Objectives

The repository supports the following research objectives:

- Apply the Semiotic Inspection Method to inspect ethical principles in generative AI systems.
- Compare successive versions of the same systems from a longitudinal perspective.
- Identify ethical alignments, gaps, regressions, reinforcements, and communicability issues.
- Consolidate evidence that allows scientific replication, auditability, and cross-system comparison.

## Theoretical and Methodological Basis

The analysis is grounded in:

- **Semiotic Engineering**
- **Semiotic Inspection Method (SIM)**
- **AI4People ethical principles**:
  - Beneficence
  - Non-maleficence
  - Autonomy
  - Justice
  - Explainability

The SIM protocol used in the reports is organized around three sign classes and a consolidation stage:

1. **Metalinguistic Signs** - Policies, terms of use, help pages, institutional messages, privacy notices, usage rules, release notes, and documentation.
2. **Static Signs** - Persistent interface elements such as labels, menus, buttons, prompts, settings, affordances, and configuration options.
3. **Dynamic Signs** - Observed system behavior during interaction, including refusals, warnings, explanations, alternative suggestions, medical safety guidance, policy enforcement, and responses to attempts to bypass safety constraints.
4. **Triangulation and Consolidation** - Integration of the findings to reconstruct the system meta-message and identify ethical patterns by system, version, and principle.

## Repository Structure and File Inventory

| File | Type | Pages | Description |
|---|---:|---:|---|
| `README.md` | Markdown | - | English documentation for the repository. It explains the study purpose, methodology, file inventory, and recommended use of the artifacts. |
| `Scenarios for SIM.pdf` | PDF | 1 | Defines the inspection scenarios used across the SIM evaluations. Scenario 1 focuses on a user seeking sensitive health-related assistance and sharing personal information. Scenario 2 focuses on misuse risks involving false information, reputational harm, and copyright-related requests. |
| `MIS_CHATGPT_2024_JIS.pdf` | PDF | 22 | SIM inspection report for ChatGPT in the 2024 analysis set. It examines the free version of the system through metalinguistic, static, and dynamic signs, including privacy notices, user rights, age-related warnings, interface affordances, response behavior, potential breakdowns, reconstructed meta-messages, and ethical guiding questions. |
| `MIS_JIS_CHATGPT_2025.pdf` | PDF | 103 | SIM inspection report for ChatGPT in the 2025 analysis set. It expands the inspection with evidence from the system home page, terms of use, release notes, privacy policy, terms of service, usage policies, interface elements, and dynamic interactions. It discusses refusal behavior, source transparency, crisis-related support, age-related limitations, potential breakdowns, and the consolidated meta-message for the 2025 version. |
| `MIS_JIS_CLAUDE_2024.pdf` | PDF | 72 | SIM inspection report for Claude in the 2024 analysis set. It evaluates Claude's communication about safety, privacy, usage rules, user conduct, and interaction limits. The report contains screenshots, translated evidence, dynamic interaction analysis, refusal behavior, potential breakdowns, meta-message reconstruction, and ethical questions mapped to AI4People principles. |
| `MIS_JIS_CLAUDE_2025.pdf` | PDF | 99 | SIM inspection report for Claude in the 2025 analysis set. It analyzes the home page, help and settings areas, support materials, policy communication, personalization flow, interface controls, and dynamic responses. It highlights ethical safeguards, transparency practices, refusal explanations, safe alternatives, age-related inconsistencies, and the complete reconstructed meta-message. |
| `MIS_JIS_GEMINI_2024.pdf` | PDF | 22 | SIM inspection report for Gemini in the 2024 analysis set. It focuses on the free version of Gemini and includes evidence from the Gemini FAQ, Privacy Center, home page, generated answer page, and dynamic prompt interactions. The report discusses privacy, accuracy warnings, age requirements, source indicators, non-diagnostic medical guidance, harmful-content refusals, and ethical questions. |
| `Gemini_2025_JIS (3).pdf` | PDF | 72 | SIM inspection report for Gemini in the 2025 analysis set. It evaluates Gemini's communication through home-page elements, help documentation, chat management resources, connected apps, source-related affordances, settings, and dynamic interactions. The report identifies ethical safeguards, verification guidance, data-control mechanisms, accessibility and autonomy concerns, transparency limitations, and potential breakdowns involving contextualized unsafe requests. |
| `non-maleficence/ChatGPT_Gemini_2025_nonmaleficence1.pdf` | PDF | 1 | Supplementary visual evidence for the 2025 non-maleficence analysis comparing ChatGPT and Gemini. It documents response behavior in sensitive or potentially harmful contexts, including medical caution, reputational-risk handling, and safety-oriented mediation. |
| `non-maleficence/Chatgpt_Claude_2025_nonmaleficence2.pdf` | PDF | 1 | Supplementary visual evidence for the 2025 non-maleficence analysis comparing ChatGPT and Claude. It highlights factual-accuracy limitations, hallucination-reduction communication, uncertainty handling, and safeguards against misleading or overconfident outputs. |
| `explicability/Claude_2025_explicability3.pdf` | PDF | 1 | Supplementary visual evidence for the 2025 explicability analysis of Claude. It presents help and support materials concerning blocking, removing, and reporting content from web search, shared conversations, and generated outputs. |
| `explicability/ChatGPT_2025_explicability2.pdf` | PDF | 1 | Supplementary visual evidence for the 2025 explicability analysis of ChatGPT. It documents platform communication about data retention, training-data minimization, model improvement, and references to privacy and terms documentation. |
| `explicability/Gemini_2025_explicability1.pdf` | PDF | 1 | Supplementary visual evidence for the 2025 explicability analysis of Gemini. It shows explanatory material about how Gemini works, including pre-training, post-training, supervised fine-tuning, reinforcement learning from human feedback, and model refinement. |
| `autonomy/ChatGPT_Gemini_Claude_2025_autonomy1.pdf` | PDF | 1 | Supplementary comparative visual evidence for the 2025 autonomy analysis across ChatGPT, Gemini, and Claude. It documents privacy, personalization, data-control, retention, deletion, export, and shared-link settings that affect user agency and control. |

## Content Description by File

### `README.md`

This file is the main repository documentation. It provides a concise English overview of the research context, methodological approach, ethical framework, file inventory, and recommended usage. It should be the first file read by researchers, reviewers, or collaborators who need to understand the purpose and scope of the repository.

### `Scenarios for SIM.pdf`

This file contains the inspection scenarios used as the basis for interaction testing and comparative evaluation. The scenarios are designed to provoke ethically relevant system behavior, including health-related risk, privacy exposure, misinformation, reputational harm, intellectual-property concerns, and attempts to obtain problematic outputs. It functions as the common scenario baseline for the system inspections.

### `MIS_CHATGPT_2024_JIS.pdf`

This file documents the 2024 SIM inspection of ChatGPT. It includes:

- Method description and inspection preparation.
- Scenario application.
- Analysis of metalinguistic signs, such as privacy policy pages, warnings, and institutional communication.
- Analysis of static signs, including the home page and persistent interface elements.
- Analysis of dynamic signs, including prompt-response behavior and safety mediation.
- Identification of potential breakdowns.
- Reconstruction of the system meta-message.
- Ethical inspection questions associated with AI4People principles.

### `MIS_JIS_CHATGPT_2025.pdf`

This file documents the 2025 SIM inspection of ChatGPT. It is the most extensive ChatGPT artifact in the repository and includes:

- Methodological framing and inspection scope.
- Evidence from terms, privacy policy, terms of service, usage policies, release notes, and interface pages.
- Static interface analysis covering the prompt area, controls, menus, configuration elements, and visible interaction affordances.
- Dynamic interaction analysis involving refusals, safety-related explanations, alternative suggestions, source disclosure, and sensitive contexts.
- Potential communicability breakdowns, particularly around age-related rules and the depth of refusal explanations.
- A consolidated meta-message describing how the 2025 version communicates its intended use, limitations, and safety posture.

### `MIS_JIS_CLAUDE_2024.pdf`

This file documents the 2024 SIM inspection of Claude. It includes:

- Inspection purpose, focus, and scope.
- Evidence from the initial interface, conduct rules, policy-related communication, and user guidance.
- Static signs associated with interface affordances and interaction structure.
- Dynamic signs from user-system exchanges involving safety limits, lawful alternatives, misinformation refusal, and health-related caution.
- Potential breakdowns, especially inconsistencies between stated access rules and observed interaction continuity.
- Ethical questions mapped to beneficence, non-maleficence, autonomy, justice, and explainability.

### `MIS_JIS_CLAUDE_2025.pdf`

This file documents the 2025 SIM inspection of Claude. It includes:

- Analysis of Claude's introductory experience, personalization flow, help resources, settings, and policy communication.
- Evidence from interface screenshots and translated excerpts.
- Static sign analysis of prompts, menus, support paths, tutorials, and controls.
- Dynamic sign analysis of safe refusals, alternative suggestions, content-generation boundaries, and sensitive-use cases.
- Potential breakdowns related to age handling, continued interaction after stated limits, and policy-application consistency.
- A final reconstructed meta-message summarizing Claude's communicative stance toward safety, transparency, usability, and user control.

### `MIS_JIS_GEMINI_2024.pdf`

This file documents the 2024 SIM inspection of Gemini. It includes:

- Method description and inspection scope for the free system version.
- Analysis of the Gemini FAQ, Privacy Center, home page, and generated answer page.
- Evidence concerning inaccuracies, offensive-content warnings, age limitations, privacy controls, and source references.
- Static and dynamic sign analysis focused on prompt submission, generated responses, and safety behavior.
- Discussion of non-diagnostic behavior in health contexts and refusals to generate harmful or defamatory content.
- Ethical inspection questions and a consolidated system meta-message.

### `Gemini_2025_JIS (3).pdf`

This file documents the 2025 SIM inspection of Gemini. It includes:

- Method description and inspection preparation.
- Analysis of Gemini home-page communication and help documentation.
- Evidence from resources about using Gemini Apps, managing recent chats, connected apps, source indicators, and settings.
- Static sign analysis of interface affordances and user-control mechanisms.
- Dynamic interaction analysis involving safety boundaries, medical-risk contexts, verification guidance, source support, and responses to contextualized harmful requests.
- Potential breakdowns involving safety-filter circumvention through contextual framing, as well as issues related to autonomy, accessibility, and transparency.
- Ethical questions aligned with AI4People principles and a consolidated meta-message for the 2025 version.

### `non-maleficence/ChatGPT_Gemini_2025_nonmaleficence1.pdf`

This supplementary evidence file supports the 2025 non-maleficence analysis by comparing ChatGPT and Gemini in ethically sensitive interaction contexts. It includes visual evidence related to safety-oriented response behavior, cautious handling of health-related or reputationally harmful requests, and the systems' communicative strategies for reducing potential harm while preserving useful guidance.

### `non-maleficence/Chatgpt_Claude_2025_nonmaleficence2.pdf`

This supplementary evidence file supports the 2025 non-maleficence analysis by comparing ChatGPT and Claude. It emphasizes factual-accuracy limitations, hallucination-related warnings, uncertainty communication, and the presentation of safer alternatives or mitigations when systems identify risks related to incorrect, misleading, or unsupported content.

### `explicability/Claude_2025_explicability3.pdf`

This supplementary evidence file supports the 2025 explicability analysis of Claude. It contains visual materials concerning content blocking, removal, and reporting mechanisms, including how users are instructed to address content from Claude web search, shared conversations, and generated outputs. It contributes evidence about institutional transparency, procedural guidance, and user-facing accountability mechanisms.

### `explicability/ChatGPT_2025_explicability2.pdf`

This supplementary evidence file supports the 2025 explicability analysis of ChatGPT. It documents how the platform communicates aspects of data retention, personal-information minimization, model improvement, and references to privacy and terms documentation. It is relevant to the inspection of how the system explains data-related processes to users.

### `explicability/Gemini_2025_explicability1.pdf`

This supplementary evidence file supports the 2025 explicability analysis of Gemini. It presents explanatory material about how Gemini works, including pre-training, post-training, supervised fine-tuning, reinforcement learning from human feedback, and model refinement. It contributes evidence about how the system communicates its development and behavioral alignment processes.

### `autonomy/ChatGPT_Gemini_Claude_2025_autonomy1.pdf`

This supplementary evidence file supports the 2025 autonomy analysis across ChatGPT, Gemini, and Claude. It brings together visual evidence of privacy settings, data controls, personalization options, retention choices, deletion mechanisms, export functions, and shared-link controls. It is relevant to evaluating how each system communicates user agency, consent, and control over personal data and interaction history.

