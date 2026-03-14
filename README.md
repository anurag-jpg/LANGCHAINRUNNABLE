# LangChain Runnable Examples

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![LangChain](https://img.shields.io/badge/LangChain-AI%20Framework-green)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Project-Active-success)

A collection of practical Python examples demonstrating how to build modular AI pipelines using **LangChain Runnable Interface**.

---

## Overview

LangChain provides a **Runnable Interface** that allows developers to build flexible and composable AI workflows.  
This repository demonstrates different runnable patterns such as sequential execution, branching logic, parallel processing, lambda transformations, and passthrough operations.

These examples help developers understand how to structure **AI pipelines using LangChain**.

---

## Features

- Demonstrates multiple **LangChain Runnable patterns**
- Beginner-friendly Python implementations
- Modular and easy-to-understand examples
- Useful for learning **AI workflow orchestration**
- Lightweight scripts for experimentation

---

## Tech Stack

- **Python**
- **LangChain**
- **OpenAI API (optional)**
- **python-dotenv**

---

## Project Structure

├── runnable_branch.py
├── runnable_lambda.py
├── runnable_parallel.py
├── runnable_passthrough.py
├── runnable_sequence.py
└── README.md


### File Description

**runnable_sequence.py**  
Demonstrates sequential execution where the output of one runnable becomes the input of the next.

**runnable_parallel.py**  
Shows how multiple tasks can run simultaneously and combine their outputs.

**runnable_branch.py**  
Implements conditional logic to select different execution paths.

**runnable_lambda.py**  
Uses lambda functions to transform data dynamically inside pipelines.

**runnable_passthrough.py**  
Passes inputs through the pipeline without modification.

---

## Installation

Clone the repository


---

## Example Workflow
User Input
   │
   ▼
Runnable Lambda (data processing)
   │
   ▼
Runnable Branch (conditional logic)
   │
 ┌─────────────┐
 ▼             ▼
Path A       Path B
   │
   ▼
Runnable Parallel
   │
   ▼
Final Output
