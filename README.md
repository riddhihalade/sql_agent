# Automated Data Analysis with Llama 3 and CrewAI

## Overview
This project leverages the capabilities of **Llama 3** in conjunction with **CrewAI** to build an automated data analysis pipeline. The pipeline is designed to efficiently analyze data stored in a **SQL database**, utilizing a team of specialized AI agents, each assigned a specific role in the workflow.

## Key Features

### Data Management
The process begins with loading a dataset (`ds-salaries.csv`) into a **SQLite database**. The data is subsequently accessed and queried as part of the automated analysis pipeline.

### Agent-Based Architecture
Three AI agents are employed, each with a distinct role:

- **SQL Developer Agent**: Responsible for constructing and executing optimized SQL queries to extract relevant data from the database.
- **Data Analyst Agent**: Analyzes the extracted data, providing detailed insights and interpretations.
- **Report Writer Agent**: Summarizes the analysis into an executive report, focusing on clarity and conciseness.

### LLM Integration
**Llama 3** is integrated into the project to handle natural language processing and decision-making tasks. **Callback mechanisms** are implemented to log and monitor the model's activities for transparency and accuracy.

### Automated Workflow
The entire process, from data extraction to report generation, is automated using **CrewAI**. Tasks are executed sequentially, ensuring coherence and precision in the final output.

## Use Case
This project demonstrates the potential of integrating **AI-driven agents** with database systems for automated, intelligent data analysis. It is particularly useful in scenarios where rapid, high-quality insights are required with minimal human intervention.

## Getting Started

### Installation

To set up the project locally:

1. **Clone the Repository:**
   git clone https://github.com/riddhihalade/sql_agent.git
   cd sql_agent


2. **Install Dependencies:**
   poetry install


3. **Set Up the Environment:**
  Add necessary environment variables and API keys in a .env file located in the project’s root directory.


4. **Prepare the Database:**
   Load the dataset of choice into the SQLite database.




