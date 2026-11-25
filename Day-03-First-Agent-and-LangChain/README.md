# Day 3 – Your First Agent: LangChain

**Workshop:** One Person Company – AI Agents Workshop  
**Institution:** Aditya University – DoTT  
**Project:** Sweet Crumbs Home Bakery

## Overview

Day 3 focused on understanding AI agents and learning the basics of LangChain. A LangChain-powered chatbot was developed for Sweet Crumbs Home Bakery, with conversation memory and automated response testing.

## Topics Covered

- Chatbot vs AI Agent
- Four components of an AI Agent
- Think → Act → Observe → Repeat
- Traditional AI, Generative AI and Agentic AI
- LangChain models, prompts and chains
- Conversation History and Memory
- Automated Chatbot Testing
- Prompt Engineering
- Temperature Experiment
- Python Functions, Type Hints and Docstrings

## Practical Implementation

- Built a bakery assistant using LangChain and Groq.
- Implemented reusable prompt templates and chains.
- Added conversation history using `HumanMessage` and `AIMessage`.
- Created a CSV dataset with 10 customer questions.
- Developed an automated testing function.
- Improved the chatbot's keyword-based test pass rate through prompt engineering.
- Experimented with temperature 1.0.
- Created two Python functions for future agent tools.

## Testing Results

| Experiment | Result |
|---|---:|
| Initial Prompt | 80% |
| Improved Prompt – V2 | 90% |
| Improved Prompt – V3 | 100% |
| Temperature 1.0 – Run 1 | 90% |
| Temperature 1.0 – Run 2 | 100% |

## Python Functions Created

1. `calculate_total()` – Calculates the total price of bakery items.
2. `check_availability()` – Checks the 24-hour advance notice requirement.

## Files

- `Day3_First_Agent_and_LangChain.ipynb` – Complete practical notebook.
- `tests.csv` – Customer questions and expected keywords.

## Learning Outcome

Learned how to build and evaluate an LLM-powered chatbot using LangChain, improve its responses through prompt engineering, maintain conversation history and prepare Python functions for future AI agent tools.

**Next:** Day 4 – Building a Tool-Using AI Agent.
