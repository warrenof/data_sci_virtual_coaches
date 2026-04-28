![A Robot Guru Hallucinating on a Mountain](assets/data_sci_robo_guru.png)

# Data Science Virtual Coach Prompts
---
A collection of system prompts designed as specialised coaches to help students work through Data Science and AI problems.
Each coach is optimised for learning — expect to be guided toward solutions rather than handed them.

## Coaches

| Coach | Focus | Link |
|---|---|---|
| Maths | Conceptual and mathematical reasoning, abstracted from code focused on stats and data science | [link](/coach_maths.yaml) |
| Python | Python for data science |[link](/coach_python.yaml)|
| SQL | SQL for data science |[link](/coach_sql.yaml) |
| Bash | Bash scripting and workflows for data science (Note:this is tuned for MacOS) | [link](/coach_bash.yaml) |
| EDA (Exploratory Data Analysis) | Structuring your approach to unfamiliar datasets | [link](/coach_eda.yaml) |
| Thinker | Working through conceptual problems out loud | [link](/coach_thinker.yaml) |
| Builder | A metaprompt — describe what you need and it builds a new coach | [link](/coach_builder.yaml) |

## How to Use

1. Pull the repo or copy a prompt manually
2. Paste it as the system instruction in your LLM tool of choice (Claude Projects, ChatGPT custom instructions, etc.)
3. Start your session as you normally would — describe your problem, share your code or data, and work through it with the coach

Prompts are designed for reasoning models and can be used alongside RAG or SERP tools.

## Prompt Structure

Each coach follows the same YAML format with these sections: `role`, `task`, `context`, `specific_requests`, `variables_examples`, `expected_outputs`, and `constraints`. YAML was chosen for being lightweight, human-readable, and well-suited to LLM inputs.

Prompts are tested primarily on Claude but should work with any capable model.

