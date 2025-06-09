# Knowledge-Loop

## Summary

Knowledge Loop is a low friction, governance-aware system for capturing, enriching, and activating knowledge in complex public institutions. Designed with trust, transparency, and traceability at its core, it empowers employees to reuse and extend organizational knowledge while aligning with the EU AI Act, GDPR, and Luxembourg’s national AI strategies.
Final project for the Building AI course

## Background

Public administrations handle enormous amounts of knowledge — but lack tools to make it trustworthy, dynamic, and shareable. Most AI systems treat knowledge as static input or disposable output. The Knowledge Loop challenges that, offering a structured yet flexible ecosystem where documents, decisions, and learning interact in governed cycles.

It was developed in response to:

* Fragmented knowledge flows across departments
* AI mistrust due to lack of transparency
* Difficulty linking learning, legal updates, and user feedback
* The need to align AI use with regulatory and ethical frameworks

💡 First MVP: A legal assistant trained on EU accessibility law (Directive 2019/882) demonstrated how curated knowledge can safely power AI tools — but also exposed the limits of linear document pipelines.

## How is it used?

The Knowledge Loop acts as a knowledge lifecycle engine. Documents are ingested, enriched (tagged, validated, simplified), logged for traceability, and activated across multiple use cases.

<img width="572" alt="Loop" src="https://github.com/user-attachments/assets/84f0f827-b50f-49d1-869f-893dc0aaa3b8" />

### The Washing Machine Window

One of the Loop’s signature innovations is the “Washing Machine Window” — a transparent UI that lets users observe exactly what happens to a document: when it was ingested, how it was processed, and where it was used. Like the transparent door on early washing machines, it builds trust through visibility and ensures explainability, especially in the adoption phase.

<img width="571" alt="Washing Machine" src="https://github.com/user-attachments/assets/88e05b83-1760-4ed4-9fb9-e7f8d3339747" />

### AI Literacy as a Foundation
The Knowledge Loop is not just a technical system — it’s a cultural shift. For employees to trust, challenge, and co-evolve AI-supported knowledge systems, they need a basic understanding of:

* How AI processes knowledge
* What it can (and cannot) infer from documents
* Why traceability, validation, and human oversight matter
* How their contributions (e.g., feedback, ratings, validations) improve system quality over time

The Loop promotes AI literacy by design:

* Transparent interfaces like the Washing Machine Window demystify AI decisions
* Micro-quests include reflective prompts (“Why is this classification correct?”)
* Learning materials and chatbot answers are explainable, not black-boxed
* AI literacy ensures the Loop is not just used, but understood — anchoring it in public sector values like accountability, equity, and service quality.

### Low Friction, High Impact
The Loop is designed to integrate seamlessly into employee workflows:

* No new software to learn — actions happen inside familiar tools (e.g., chatbots, portals, LMS)
* Feedback and knowledge validation require only a few clicks
* Contributors are guided gently through the process without burden

### Gamified Micro-Contributions
To sustain engagement, the Loop uses light gamification:

* Mini-quests: Validate a document, rate an answer, suggest a better explanation
* XP & badges: Recognize helpful contributions and improvement suggestions
* Community leaderboard: Show active contributors (optionally, anonymously)

This creates a culture of continuous learning and shared ownership — critical for durable AI trust.

## Data sources and AI methods

The Loop is data-source agnostic, but always governed. It can process:

* EU and national regulations
* Standards, decisions, policy notes, circulars 
* Internal reports and meeting notes
* AI outputs (chatbot responses, summaries)
* Feedback from users and learners
* Version-controlled knowledge objects

It can use:

* GPT-4/Mistral/Llama (for language enrichment and simplification)
* Semantic search or RAG (for scalable retrieval)
* CAG (for precise results depending on user roles)
* Governance overlays (who validated what, when, why)

The EAA legal assistant prototype uses:
* Official EU legal texts such as Directive (EU) 2019/882 (EAA)
* Standard EN 301549
* National transpositions (Luxembourg)
* Institutional glossaries, Q&As, and internal feedback

Example from the prototype:
User: Can a kiosk be exempt from accessibility requirements?
GPT: Under Article 2(3)(a) of Directive (EU) 2019/882, products used exclusively by microenterprises may be exempt. However, Member States may regulate this differently.
See also Luxembourg's transposition law, Article 4.

## Challenges

The Loop does not:

* Replace formal legal or expert review
* Manage raw personal data
* Operate without human oversight

Ethical and legal considerations:

* Must maintain clear access control and auditability
* Needs regular validation cycles
* Requires hybrid governance: part automated, part expert-led

 <img width="573" alt="Governance" src="https://github.com/user-attachments/assets/331702f9-55ff-4652-9e38-7ac9a1564d94" />
  
## What next?

The Knowledge Loop is modular and scalable. Next phases could include:

* 📦 Integration with enterprise search or chatbot tools
* 📊 Visual lifecycle dashboard for stakeholders
* 🔐 Secure document-level audit trail (for EU AI Act conformity)
* 🏛 Alignment with national cloud infrastructure or public sector strategies

Skills needed:

* Backend/data architecture
* UX for trust-centric interfaces
* Legal and compliance input
* Change management for adoption
 
## Acknowledgments

* Inspired by Luxembourg’s AI Strategy, the AI Act, and public sector innovation goals
* Washing Machine metaphor: From the story of early users mistrusting automation — until they could see it work by Michèle Staus
* Hybrid Governance: Community-driven transformation by Michèle Staus
* Built using OpenAI tools for prototyping, experimentation, and dialogue testing
* Washer Machine Window by Lutz Maertens / CC BY-SA 3.0
