# PAID - Private AI for Democracy

AI tools that foster better democratic societies using political science, history, philosophy and engineering principles. PAID (Private AI for Democracy) is a civic-minded, non-commercial project aimed at building a private AI lab infrastructure for democratic and ethical use. PAID is an open, federated infrastructure that individuals or local communities (chapters) can reuse and scale for their own civic needs. By keeping AI development privacy-focused and local, PAID strives to ensure AI technology serves the public interest – counterbalancing the centralized corporate control of AI that often reflects narrow interests instead of the general public good. This document outlines the repository’s structure and content, including technical setup guides and a dedicated space for the philosophical and civic motivation behind the project.

```bash
.

PAID/                    - Root of the Private AI for Democracy repository
├─ README.md             - Introduction, vision, and usage of PAID (civic/ethical focus)
├─ LICENSE.md            - MIT License (open-source usage permissions)
├─ CONTRIBUTING.md       - Guidelines for contributing to the project
│
├─ docs/                 - Technical documentation and deployment guides
│  ├─ stack.md           - **Core Stack Overview**: Key components of the PAID AI stack 
│  ├─ setup/             - **Setup Guides** for deployment
│  │  ├─ local.md        - Step-by-step instructions for local laptop setup
│  │  └─ remote.md       - Step-by-step instructions for remote/colocated server deployment
│  ├─ privacy.md         - **Privacy & Redaction**: Data privacy practices and redaction architecture
│  └─ cost.md            - **Cost Breakdown**: Hardware recommendations and cost considerations
│
├─ thought/              - Reflections on philosophy, epistemology, and civic purpose (the project's "why")
│  ├─ README.md          - Overview of the **Thought** section and how it informs the project
│  ├─ philosophy.md      - Cyber-philosophical motivations (ethical, humanistic reasoning behind PAID)
│  ├─ epistemology.md    - Notes on knowledge, truth, and misinformation in context of AI & democracy
│  └─ civic.md           - Civic vision: how private AI can strengthen democratic society
│
├─ src/                  - Source code for PAID’s applications and modules
│  ├─ ...                - (To be populated with application code, e.g., LLM interface, API, etc.)
│
├─ data/                 - Sample or placeholder data for AI models (if applicable)
│  ├─ ...                - (E.g., example documents, datasets for testing the AI pipeline)
│
├─ examples/             - Usage examples, demos, or notebooks showing PAID in action
│  ├─ ...                - (E.g., example queries, integration demos with the stack)
│
└─ tests/                - Test suite for ensuring code reliability
   ├─ ...                - (Unit and integration tests for the PAID codebase)
