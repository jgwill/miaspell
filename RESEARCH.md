# SpecLang Project - External LLM Research Requests

This document contains research requests intended for an external Large Language Model (LLM) to conduct deep-searches. The goal is to gather information that can inform and accelerate the development of the SpecLang portal and its associated ecosystem of tools and methodologies.

## Research Request 1: Existing Landscape of NL-to-Specification & NL-to-UI/Code Tools

**Prompt for LLM:**

"Conduct an in-depth market and academic research survey to identify and analyze existing software tools, open-source projects, and research prototypes that focus on translating natural language (NL) user requirements, user stories, or feature descriptions directly into:

1.  **Formal or Semi-Formal Software Specifications:** This includes tools generating outputs like UML diagrams, Behavior-Driven Development (BDD) feature files (Gherkin), formal DSLs, structured Markdown similar to SpecLang, or other machine-readable specification formats.
2.  **UI Wireframes, Mockups, or Prototypes:** Systems that take NL descriptions and generate visual UI representations or interactive prototypes.
3.  **Initial Code Skeletons or Stubs:** Tools that attempt to generate boilerplate or foundational code in common programming languages from NL.

For each identified system, please provide:
*   **Name and Origin:** (Commercial, Open-Source, Academic Project)
*   **Core Functionality & Approach:** How does it work? What NL processing techniques or AI models (if known) are used?
*   **Input Format(s):** What kind_of natural language input does it expect?
*   **Output Format(s):** What kind of specifications, UI elements, or code does it produce?
*   **Key Strengths & Weaknesses:** Based on available documentation, reviews, or papers.
*   **Maturity & Adoption Level:** Is it widely used, a niche tool, or purely conceptual?
*   **Relevance to SpecLang:** How does its approach compare or contrast with SpecLang's philosophy (intent-driven, iterative, prose-code)?

The search should cover commercial products, active open-source repositories (GitHub, GitLab), academic publications (ACM Digital Library, IEEE Xplore, arXiv), and relevant industry blogs or forums from the last 5-7 years."

## Research Request 2: Advanced Prompt Engineering & Interaction Patterns for Structured Markdown Generation

**Prompt for LLM:**

"Perform a comprehensive literature review and best-practices search focused on advanced prompt engineering techniques and conversational interaction patterns for Large Language Models (e.g., Gemini, GPT-series, Claude) specifically when the desired output is highly structured, hierarchical Markdown documents, like technical specifications (similar to SpecLang).

The research should cover:
1.  **Prompt Structuring Techniques:**
    *   Multi-shot prompting (few-shot, many-shot) examples tailored for complex Markdown.
    *   Role-playing instructions and persona design for AI agents generating specs.
    *   Techniques for embedding meta-instructions or constraints within the prompt to control Markdown structure (e.g., enforcing heading levels, list styles, table formats).
    *   Strategies for handling ambiguity in user input and prompting the AI to ask clarifying questions before generating the spec.
2.  **Output Control & Validation:**
    *   Methods to guide the LLM towards specific Markdown flavors or conventions.
    *   Techniques to instruct the LLM to self-critique or validate its own Markdown output for structural integrity or completeness against a given schema/template.
    *   Reducing verbosity or ensuring conciseness while maintaining necessary detail.
3.  **Iterative Refinement Patterns:**
    *   Effective ways to feed an existing Markdown specification back to the LLM along with new natural language instructions for modification, addition, or deletion of sections.
    *   Managing context windows effectively during iterative spec development.
4.  **Handling Complex Elements:**
    *   Generating complex Markdown elements like nested lists, tables, code blocks with syntax highlighting hints, and diagrams (e.g., Mermaid.js syntax within Markdown).
5.  **Mitigating Common Issues:**
    *   Strategies to reduce issues like "prompt drift," hallucination of Markdown syntax, or inconsistent formatting in long-form spec generation.

Please include references to academic papers, AI research lab publications, practical guides from LLM providers, and impactful community discussions or blog posts."

## Research Request 3: Methodologies and Technologies for Bi-Directional Mapping & Synchronization between Specifications and UI/Code Artifacts

**Prompt for LLM:**

"Conduct a thorough investigation into existing methodologies, theoretical frameworks, software tools, and research projects that address the challenges of creating and maintaining bi-directional traceability and synchronization between abstract software specifications (such as those in SpecLang, textual DSLs, or even BDD scenarios) and their corresponding concrete software artifacts, particularly:

1.  **User Interface (UI) Designs/Components:** How can changes in a textual specification be reflected in a UI design tool (e.g., Figma, Sketch) or UI component library, and vice-versa?
2.  **Source Code:** How can code be generated from detailed specs, and more importantly, how can changes in the source code (refactoring, bug fixes, feature additions) be reflected back into the specification to maintain consistency, or how can specs be updated to drive code changes?

The research should focus on:
*   **Traceability Techniques:** Methods for establishing and maintaining links between specification elements and UI/code elements.
*   **Change Detection & Propagation:** Algorithms or approaches for identifying changes in one artifact and propagating them to linked artifacts.
*   **Conflict Resolution:** Strategies for handling inconsistencies or conflicts when changes occur concurrently in both the specification and the implementation.
*   **Model-Driven Engineering (MDE) Approaches:** Relevant MDE techniques or tools that support round-trip engineering or view consistency across different models/representations.
*   **AI/LLM in Synchronization:** Any research on using AI or LLMs to assist in understanding changes, suggesting updates, or automating parts of the synchronization process.
*   **Challenges & Limitations:** Documented difficulties in achieving robust bi-directional synchronization in real-world projects.
*   **Examples/Case Studies:** Any known systems or projects that have successfully implemented (even partially) such bi-directional capabilities.

Source materials should include academic research (e.g., software engineering conferences like ICSE, ASE; journals like TSE), industry best practices, and descriptions of relevant tool capabilities."
