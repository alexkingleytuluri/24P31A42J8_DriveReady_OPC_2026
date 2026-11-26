# Day 4 – Tools, Structured Output and Google Sheets

## Project: Sweet Crumbs Home Bakery AI Agent

### Objective
Develop an AI-powered bakery assistant that uses custom tools, structured output and Google Sheets to manage customer orders.

### Topics Covered
- Creating custom tools using LangChain's `@tool` decorator.
- Defining structured data models using Pydantic.
- Connecting an LLM with multiple tools.
- Maintaining conversation history.
- Integrating Google Sheets using `gspread`.
- Extracting structured information from customer messages.
- Analysing agent execution traces.
- Understanding the importance of tool names and descriptions.

### Technologies Used
- Python
- LangChain
- Groq LLM
- Pydantic
- Google Colab
- Google Sheets
- gspread

### Implementation

Three main tools were developed:

1. **get_price:** Retrieves the price and calculates the total for a menu item.
2. **is_open:** Checks the bakery's opening hours.
3. **log_order:** Validates and records customer orders in Google Sheets.

A Pydantic `Order` model was created to define the required customer information, including name, item, quantity, date and eggless preference.

The AI agent was connected to these tools and tested using different customer conversations.

### Experiments and Testing
- Tested price calculations for different bakery products.
- Checked opening hours for different days.
- Recorded valid customer orders in Google Sheets.
- Tested missing information and invalid order requests.
- Experimented with structured output using Pydantic.
- Compared tools with vague and descriptive names.
- Analysed agent execution traces.

### Results
- Successfully retrieved product prices and opening hours through tools.
- Successfully recorded valid orders in Google Sheets.
- Tested invalid orders and verified that they were not saved.
- Successfully extracted structured order information from some customer messages.
- Observed structured-output failures in certain test cases and documented them.
- Analysed tool calls and agent messages through execution traces.

### Files
- `Day4_Tools_Structured_Output_Google_Sheets.ipynb` – Complete implementation and experiments.
- `sweet_crumbs_facts.txt` – Bakery business information and order-management rules.

### Key Learning
Learned how an AI agent can use Python functions as tools, produce structured data, interact with external services and perform practical business tasks.
