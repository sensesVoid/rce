# Reflexive Context Engine (RCE)

Welcome to the Reflexive Context Engine (RCE)! This framework provides a structured and comprehensive context for AI-driven software development. It ensures the AI is fully context-aware and aligned with project goals.

## How It Works

The RCE acts as a centralized repository of project information, guidelines, and memory. It provides the necessary context for the AI to effectively interpret your requests, understand project requirements, and generate code.

The core workflow with the RCE:

1.  **Define**: Provide project requirements in `user_input/prd_template.md`.
2.  **Contextualize**: The RCE provides structured context via `gemini.md`, `guidelines/`, `tools/`, and `persistency/`.
3.  **Develop**: The AI uses this context to write code, create tests, and build the application in the `project/` directory, adhering to all provided guidelines.
4.  **Persist**: Utilize `persistency/` to maintain context, track tasks, and store learnings.

## Getting Started

To use the RCE:

1.  **Define Your Project**:
    -   Open `user_input/prd_template.md`.
    -   **Paste your Product Requirements Document (PRD) content directly into this file.**
    -   Save the file.

2.  **Utilize Context**:
    -   The AI will now use the context provided by the RCE to perform development tasks. Refer to `gemini.md`, `guidelines/`, `tools/`, and `persistency/` for comprehensive project understanding.
    -   Once you have pasted your PRD, simply say "Orchestrate" to begin the development process.

## Folder Structure

-   **`/examples/`**: Sample PRDs and example code for reference.
-   **`/guidelines/`**: Modular rulebooks for the AI (e.g., coding standards, security, communication, core mandates, workflow, self-healing, etc.).
-   **`/tools/`**: Definitions and usage guidelines for the AI's available tools.
-   **`/initializer/`**: Templates for generating internal AI plans (e.g., PRP templates).
-   **`/persistency/`**: RCE's memory and state management.
    -   `task_list.md`: Project task checklist.
    -   `memory.md`: Stores long-term facts and decisions.
    -   `rag/`: Documents for Retrieval-Augmented Generation.
-   **`/project/`**: Application source code written by the AI.
-   **`/user_input/`**: Your primary input, most importantly the PRD.

This engine is a powerful tool for structured, AI-driven development. By investing a small amount of time in defining your requirements upfront, you can achieve a high degree of automation and quality in your projects.
