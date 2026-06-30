![A Robot Guru Hallucinating on a Mountain](assets/data_sci_robo_guru.png)

# Data Science Virtual Coach Prompts
---
A collection of system prompts designed as specialised coaches to help students work through Data Science and AI problems.
Each coach is optimised for learning — expect to be guided toward solutions rather than handed them.

## Project Workflow
---
An interactive checklist for working through tabular prediction problems — from EDA to final model selection — without skipping the steps that quietly sink a project.
[Workflow Reference Doc](/workflow_reference.html)

### Usage
Open workflow_reference.html in any browser — no build step, no dependencies.
Workflow tab: 14 phases covering EDA, CV design, encoding, modelling, tuning, ensembling, and final selection. Click a phase to expand it; click the circle to mark it done and track progress in the header.
Algorithms tab: searchable, filterable reference of regression algorithms (tree-based, linear, Bayesian, instance-based, neural, kernel) with strengths, weaknesses, when to use, and library comparisons.
Use expand / collapse / reset in the header to manage the workflow view; e / c keyboard shortcuts do the same.
Treat it as a working reference, not a rulebook — the decision branches (? blocks) are there to prompt the right diagnostic question at each stage, not to be followed blindly.

## Coaches

| Coach | Focus | Link |
|---|---|---|
| Maths | Conceptual and mathematical reasoning, abstracted from code focused on stats and data science | [link](/coach_maths.yaml) |
| Algebra-Translator | Translate Algebraic experssions and formulae into more readable language | [link](/coach_algebra_translator.yaml) |
| Python | Python for data science |[link](/coach_python.yaml)|
| SQL | SQL for data science |[link](/coach_sql.yaml) |
| Bash | Bash scripting and workflows for data science (Note:this is tuned for MacOS) | [link](/coach_bash.yaml) |
| EDA (Exploratory Data Analysis) | Structuring your approach to unfamiliar datasets | [link](/coach_eda.yaml) |
| Machine Learning | Guides you through an end-to-end exploratory workflow for labelled datasets | [link](/coach_machine_learning.yaml) |
| Thinker | Working through conceptual problems out loud | [link](/coach_thinker.yaml) |
| Builder | A metaprompt — describe what you need and it builds a new coach | [link](/coach_builder.yaml) |


## How to Use

1. Pull the repo or copy a prompt manually
2. Paste it as the system instruction in your LLM tool of choice (Claude Projects, ChatGPT custom instructions, etc.)
3. Start your session as you normally would — describe your problem, share your code or data, and work through it with the coach
4. Use the Workflow to orientate and time-box efforts, or select best supporting coach

Prompts are designed for reasoning models and can be used alongside RAG or SERP tools.

## Prompt Structure

Each coach follows the same YAML format with these sections: `role`, `task`, `context`, `specific_requests`, `variables_examples`, `expected_outputs`, and `constraints`. YAML was chosen for being lightweight, human-readable, and well-suited to LLM inputs.

Prompts are tested primarily on Claude but should work with any capable model.

