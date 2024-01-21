# AI Code Summarizer

## Introduction
This Python application leverages the Salesforce codet5-base model to automatically generate summaries for Python code snippets. It extracts functions from the code, obtains their source code, and generates a summary using the pre-trained model.

## Prerequisites
1. Python 3.x installed on your machine.
2. [Git](https://git-scm.com/) installed to clone the repository.
3. [Hugging Face Transformers](https://github.com/huggingface/transformers) library installed. You can install it using:
    ```bash
    pip install transformers
    ```

## Installation
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/your-repo.git
    cd your-repo
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### 1. Modify Code Input
Replace the contents of the `your_code_file.py` with the Python code snippet you want to summarize.

### 2. Run the Application
Run the Python script to summarize the code:
    ```bash
    python summarize_code.py
    ```

### 3. View Summaries
The application will print summaries for each function in the provided Python code.

## Sample Python Code
You can use the provided sample Python code in the `sample_code.py` file for testing the application.

