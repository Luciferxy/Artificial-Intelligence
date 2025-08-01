# Building AI Agents From Scratch: A Daily Python Journey

A warm welcome to this open-source project where we embark on a daily adventure to build Artificial Intelligence agents from the ground up using Python. This repository serves as a learning resource, providing a new Python file each day that focuses on a specific aspect of creating AI agents.

## 🌟 Project Overview

This project is designed for anyone interested in learning the fundamentals of AI agent development. Whether you're a student, a developer looking to expand your skills, or just curious about AI, you'll find valuable insights and practical code examples here. Each day, a new, well-commented Python file will be added, breaking down complex concepts into manageable pieces.

### Key Features:
*   **Daily Python Files:** New, focused content added every day.
*   **Step-by-Step Learning:** Concepts are introduced progressively.
*   **Practical Code:** All examples are hands-on and ready to run.
*   **Open to All:** A welcoming environment for learners of all levels.

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

This project uses Python 3. Make sure you have it installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

You will also need `git` to clone the repository.

### Installation

1.  Clone the repo:
    ```sh
    git clone https://github.com/Luciferxy/Artificial-Intelligence.git
    ```
2.  Navigate to the project directory:
    ```sh
    cd Artificial-Intelligence
    ```
3.  (Optional) It is recommended to create a virtual environment to manage dependencies:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
4.  Install any necessary packages (if any are added later):
    ```sh
    pip install -r requirements.txt
    ```

## 🗓️ Daily Content Log

Here you will find a log of the daily Python files, with the most recent at the top. Each entry will include the day, a description of the topic covered, and a direct link to the file.

*   **Day 002: Giving AI Agents Tools** - This notebook explores the "Tool Pattern," demonstrating how to give an AI agent new capabilities. It features a `@tool` decorator that turns a standard Python function (for fetching Hacker News stories) into a tool that the `ToolAgent` can intelligently decide to use to answer user queries. [Link to file](./Day2(tool_pattern).ipynb)
*   **Day 001: Introduction to Reflection Patterns** - This notebook introduces the concept of reflection in AI agents. It uses the `agentic_patterns` library to show how a `ReflectionAgent` can iteratively write and refine code. The example demonstrates the creation of a Merge Sort algorithm, where one agent generates the initial code and a second "reflector" agent provides feedback for improvement. [Link to file](./Day1(refecting_patterns).ipynb)
*   *(...and so on...)*

## 🤖 Usage

Each daily file is a self-contained lesson. To run a file, navigate to the project directory and use Jupyter Notebook or your preferred IDE.

For example, to run the file for Day 2:
```sh
# This is a Jupyter Notebook, so open it with Jupyter:
jupyter notebook "Day2(tool_pattern).ipynb"
