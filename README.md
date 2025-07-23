Build an AI Agent to Answer E-commerce Data Questions
This project creates a smart AI agent that can answer natural language questions using e-commerce data from Excel files. The agent uses Google's Gemini large language model (LLM) and Python's pandas library to generate and execute code based on the user's question.

Features
Loads three Excel files: Ad Sales, Total Sales, and Eligibility

Uses Gemini 1.5 Flash model to generate Python code

Executes the generated code and prints results

No need for a database; works entirely with pandas DataFrames

Example question: "Calculate the RoAS (Return on Ad Spend)"

Dataset Structure
You need the following Excel files:

Product-Level Ad Sales and Metrics (mapped).xlsx

Product-Level Total Sales and Metrics (mapped).xlsx

Product-Level Eligibility Table (mapped).xlsx

Make sure the file paths in the script are updated to reflect where your files are stored.

How It Works
Loads the Excel files into pandas DataFrames

Accepts a natural language question from the user

Sends the question to the Gemini LLM to generate Python code

Executes the generated code and prints the answer
