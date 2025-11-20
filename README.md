📘 README.md for Gogle AI – Multi-Agent Automation for Micro- & Nanoengineering
Overview

Gogle AI is a modular multi-agent system designed to automate reasoning, simulation workflows, and engineering tasks in the fields of micro- and nanotechnology.
It provides specialized agents for semiconductor physics, AFM/SEM/EDX analysis, COMSOL instruction generation, and Python-based calculation tools.

This repository contains the full codebase used in the Kaggle Agents Intensive Capstone Project.

🔧 Features

Multi-agent orchestration

Python tool execution

COMSOL instruction generator

Semiconductor physics solver (BJT, MOSFET, pn-junction)

AFM/SEM/EDX explanation tools

Memory + embedding retrieval

Multi-step planning & reasoning with evaluator loop

🗂 Project Structure
agents/               # Agent files (Gem, Flash, Evaluator, etc.)
tools/                # Tool functions (COMSOL, Python runner)
memory/               # Embedding & memory manager
config/               # Settings, templates
main.py               # Main orchestrator
system_prompt.md      # Agent philosophy and instructions
requirements.txt      # Python dependencies


The ZIP file (2.2.zip) contains the entire structured project.

📦 Installation

Download the repository

Extract the ZIP file

Install dependencies:

pip install -r requirements.txt

▶️ Usage

Run the main system:

python main.py


Or load specific agents/tools depending on your workflow.

📚 License

For educational purposes as part of the Kaggle Agents Intensive course.
