# 📊 Smart Finance Assistant – Budget Buddy

<!-- BADGES:START -->
[![curtin](https://img.shields.io/badge/-curtin-f57c00?style=flat-square)](https://github.com/topics/curtin) [![ai-assistant](https://img.shields.io/badge/-ai--assistant-blue?style=flat-square)](https://github.com/topics/ai-assistant) [![chatbot](https://img.shields.io/badge/-chatbot-blue?style=flat-square)](https://github.com/topics/chatbot) [![edtech](https://img.shields.io/badge/-edtech-4caf50?style=flat-square)](https://github.com/topics/edtech) [![finance](https://img.shields.io/badge/-finance-blue?style=flat-square)](https://github.com/topics/finance) [![financial-tools](https://img.shields.io/badge/-financial--tools-blue?style=flat-square)](https://github.com/topics/financial-tools) [![gradio](https://img.shields.io/badge/-gradio-blue?style=flat-square)](https://github.com/topics/gradio) [![jupyter-notebook](https://img.shields.io/badge/-jupyter--notebook-blue?style=flat-square)](https://github.com/topics/jupyter-notebook) [![python](https://img.shields.io/badge/-python-3776ab?style=flat-square)](https://github.com/topics/python) [![rag](https://img.shields.io/badge/-rag-blue?style=flat-square)](https://github.com/topics/rag)
<!-- BADGES:END -->

Welcome to your project repository for the **ISYS2001 Final Programming Project**. This repo provides a starting point for building your **Smart Finance Assistant**.

---

## 📖 Project Overview
In this project, you will design and implement a **Smart Finance Assistant** using:
- Python (Google Colab)
- [hands-on-ai](https://pypi.org/project/hands-on-ai/) (chat, RAG, agent tools)
- [Gradio](https://www.gradio.app/) (to create a simple app interface)

Your Assistant should include:
- **Chat**: a finance-oriented personality bot
- **RAG**: retrieval from CSV or other documents
- **Agent Tool**: one custom tool (e.g., budget calculator, currency converter)
- **Gradio UI**: a simple interface tying everything together
- **Tests**: a Testing Section in your notebook

---
# 💰 Budget Buddy – Smart Finance Assistant

## 📖 Project Overview

Budget Buddy is a Smart Finance Assistant developed using Python, Google Colab, Gradio, and the hands-on-ai package. The purpose of this project is to help users better understand their spending habits by analysing transaction data from CSV files and generating simple financial insights and recommendations.

This system allows users to:
- Upload transaction CSV files
- Analyse spending patterns by category
- Receive personalised budgeting advice
- Use a financial chatbot for simple finance questions
- Calculate savings goals using a custom financial tool
- Interact with the system through a Gradio user interface

The project was developed following the six-step development methodology provided in the assignment specification.

---

# ⚙️ Technologies Used

- Python
- Pandas
- Google Colab
- Gradio
- hands-on-ai
- CSV transaction datasets

---

# ✨ Features

## 📊 CSV Spending Analysis

Users can upload CSV transaction files containing:
- Date
- Amount
- Category
- Description

The system cleans and analyses the data to:
- Calculate total spending
- Identify top spending categories
- Generate spending insights
- Provide budgeting recommendations

### Example Analysis:
- Total spending calculation
- Category percentage breakdown
- Top spending category detection
- Financial recommendations based on spending behaviour

---

## 🤖 Financial Chatbot

Budget Buddy includes a finance-focused chatbot that can answer simple financial questions such as:
- “How can I reduce coffee spending?”
- “What is a good budgeting strategy?”
- “How can I save more money?”
- “How can I reduce entertainment expenses?”

The chatbot provides short, easy-to-understand financial advice for users.

---

## 💵 Savings Goal Calculator

The project includes a custom financial tool that helps users estimate how long it will take to reach a savings goal based on:
- Current savings
- Monthly contribution
- Target savings amount

### Example:
- Current Savings: $1000
- Monthly Contribution: $250
- Goal: $5000

The system calculates the estimated number of months required to reach the goal.

---

## 📚 RAG Financial Advice System

A simple Retrieval-Augmented Generation (RAG) system was implemented using financial advice documents. The system retrieves relevant financial tips based on user questions and spending categories.

Example topics include:
- Grocery budgeting
- Entertainment spending
- Coffee spending
- Transport savings
- Saving habits

Example question:
> “How can I reduce coffee spending?”

Example response:
> “Making coffee at home may reduce unnecessary spending.”

---

## 🖥️ Gradio User Interface

The application uses Gradio to create an interactive web interface with:
- CSV upload functionality
- Financial chatbot
- Savings calculator
- Spending analysis dashboard

The Gradio UI allows users to interact with the finance assistant through a simple browser interface.

---

# 🧪 Testing and Debugging

Comprehensive testing was completed to ensure the system works correctly.

The testing section includes:
- Normal transaction datasets
- Refund transactions
- Missing data scenarios
- Invalid file handling
- Spending analysis validation
- Recommendation validation
- Integration workflow testing

### Example Tests:
- CSV loading tests
- Spending calculation tests
- Recommendation generation tests
- Error handling tests
- Integration tests

The system successfully handled:
- Missing values
- Refund transactions
- Invalid CSV files
- Incorrect file names
- Edge case financial data

---

# 🐞 Debugging Process

During development, several Python errors were identified and fixed, including:
- `NameError`
- `IndentationError`
- `ModuleNotFoundError`
- `return outside function`

AI-assisted debugging helped identify coding mistakes and improve overall code quality.

---

# 📂 Sample CSV Format

Example CSV structure:

| Date | Amount | Category | Description |
|------|------|------|------|
| 2024-05-01 | 25.50 | Coffee | Starbucks |
| 2024-05-02 | 120.00 | Groceries | Coles |
| 2024-05-03 | 45.00 | Transport | Uber |
| 2024-05-04 | -15.00 | Refund | Woolworths Refund |

---

# 🚀 How to Run the Project

## Step 1: Open the Notebook
Open the Google Colab notebook file.

## Step 2: Install Required Packages
Run the installation cells:
```python
!pip install gradio
!pip install hands-on-ai
```

## Step 3: Run All Python Cells
Run all implementation cells in order:
- Data loading
- Spending analysis
- Financial recommendations
- RAG system
- Savings calculator
- Gradio interface

## Step 4: Launch the Gradio UI
Run:
```python
demo.launch(share=True)
```

## Step 5: Use the System
Users can:
- Upload CSV files
- Ask finance questions
- Calculate savings goals
- Receive financial insights

---

# 📁 Project Structure

```text
/README.md
/smart_finance_assistant.ipynb
/sample_transactions.csv
/developer_diary.md
/tests/
```

### File Descriptions

- `smart_finance_assistant.ipynb`
  - Main Google Colab notebook containing the full project

- `sample_transactions.csv`
  - Example transaction dataset used for testing

- `developer_diary.md`
  - AI collaboration reflections and evidence

- `tests/`
  - Testing scripts and validation examples

---

# 🤝 AI Collaboration

AI tools such as ChatGPT were used throughout the project to:
- Generate coding ideas
- Improve prompts
- Debug Python errors
- Design financial analysis logic
- Create testing scenarios
- Improve Gradio UI implementation
- Generate pseudocode
- Improve business logic validation

All AI-generated code was reviewed, tested, and improved before final implementation.

---

# 📈 Business Value

Budget Buddy helps users:
- Understand spending habits
- Improve budgeting decisions
- Identify unnecessary spending
- Build savings habits
- Receive simple financial guidance

The project demonstrates how AI and data analysis can support personal finance management.

---

# 📌 Conclusion

Budget Buddy demonstrates how AI-powered financial tools can help users better understand their spending behaviour and improve budgeting habits.

The project combines:
- Data analysis
- AI collaboration
- Chatbot interaction
- Financial tools
- Testing and debugging
- User interface design

into one integrated Smart Finance Assistant system.

---

# 👨‍💻 Author

Olivia Nguyen  
ISYS2001 – Introduction to Business Programming
---


