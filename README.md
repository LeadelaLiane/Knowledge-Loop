# Knowledge-Loop

Final project for the Building AI course

## Summary

Knowledge Loop is a low-friction system for capturing, enriching, and activating organizational knowledge. It supports traceable AI interactions, trustworthy document reuse, and learning integration within regulated public sector environments.

## Background

Public administrations struggle to preserve and reuse knowledge in ways that are traceable, explainable, and accessible — especially under regulatory constraints. 
Staff often face challenges such as:

*Repetitive or redundant document searches
*Fragmented knowledge management systems
*Low trust in AI-generated responses due to missing context or sources

This project is motivated by the need to build trust in AI through traceability and explainability, especially in legal and political contexts. It's designed for environments where auditable knowledge governance and human oversight are essential.

## How is it used?

The Knowledge Loop ingests documents (e.g., legal texts, guidance, FAQs), enriches them with metadata, logs their lifecycle, and makes them reusable in multiple interfaces — including chatbots, LMS modules, and search tools.

It can be used by:

*Internal staff needing reliable guidance
*Legal and policy teams curating compliance material
*HR for on- and offboarding, intern mobility and talent scouting
*Trainers developing microlearning content
*Chatbots serving the public with filtered, auditable information

<img width="572" alt="Loop" src="https://github.com/user-attachments/assets/10877f87-93f9-4efc-b619-6609f1c5590a" />

## Data sources and AI methods

*National legal texts and EU regulations
*International conventions
*Legal notices, recommendation
*Decisions, Litigation, 
*Directives, circulars, notes, reports
*Procedures, processes, forms
*Glossaries, Q&As, and internal feedback

The EAA legal assistant prototype uses:
*Official EU legal texts such as Directive (EU) 2019/882 (EAA)
*Norm EN 301549
*National transpositions (Luxembourg, Germany, France)
*Institutional glossaries, Q&As, and internal feedback

AI methods: GPT-4 (via ChatGPT Plus), semantic search, retrieval-augmented generation (RAG, conceptually)

Example from the prototype:
User: Can a kiosk be exempt from accessibility requirements?
GPT: Under Article 2(3)(a) of Directive (EU) 2019/882, products used exclusively by microenterprises may be exempt. However, Member States may regulate this differently. See also Luxembourg's transposition law, Article 4.

## Challenges

This project does not:

*Replace formal legal advice
*Host sensitive personal data
*Automatically resolve conflicts between EU and national law

Limitations & considerations:

*Requires expert validation
*Must meet GDPR and AI Act traceability requirements
*Needs clear boundaries between public and internal knowledge

Ensuring Traceability, auditability and explainability with the washing machine window:
<img width="571" alt="Washing Machine" src="https://github.com/user-attachments/assets/071c0e40-fe7f-4ff1-9989-54d86df26057" />

## What next?

To move from prototype to deployment, the project would need:

*Scalable infrastructure (e.g., Azure/OpenAI API)
*Governance framework for document curation
*Secure integration into public sector workflows
*UX/UI support to tailor chatbot and LMS interfaces
*Policy and ethics review for AI-assisted guidance

## Acknowledgments

*Inspired by the Knowledge Management cycle and trustworthy AI principles
*Legal texts sourced from EUR-Lex and national legislation portals
*Visuals adapted from Wikimedia Commons
