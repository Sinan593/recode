# ReCode Documentation

## Introduction

ReCode is a solution that leverages the open-source LLAMA3 framework to easily convert legacy languages like COBOL, Delphi, and VB to modern languages like Python, C, and more. Additionally, ReCode can generate comprehensive documentation for both legacy and modern codebases.

This series of Getting Started guides is tailored to assist you in mastering the ReCode API. Whether you're a seasoned API user or just getting started, these guides are designed to cater to your needs. Explore them in any order; it's like embarking on a choose-your-own-adventure journey where every path leads to success!

## Setting up LLAMA3 on your Local Machine

### install Ollama

## Ollama Official Website:
https://ollama.com/

### for linux

```bash
curl -fsSL https://ollama.com/install.sh | sh
```

## run these commands

```
ollama serve
```

```
ollama pull llama3
```

#### to check all the installed models 
```
ollama list
```
### to run llama3
```
ollama run llama3
```
this command will run llama3 model on your machine and you can interact with it using the CLI

# ReCode API Setup Guide

## 🚀 Setting up ReCode API on your Local Machine

### Forking a Repository

1. Go to the following repository:[ReCode Repository](https://github.com/Sinan593/recode).
2. Click on the "Fork" button on the top right corner to fork the repository to your GitHub account.

### Clone the Repository

```bash
git clone https://github.com/Sinan593/recode.git
```

### move inside the Directory

```
cd recode
```

## Run the Python Scripts

### 1.Create a Virtual Python Environment:

```
python -m venv venv
```

### 2.Activate the Environment:
```
source venv/bin/activate
```
### 3.Install Required Libraries or Modules:
```
pip install -r requirements.txt
```

### 4.Run the Application:
```
python app.py
```

Congratulations! You have successfully set up ReCode API on your local machine. You can now communicate with the API and leverage its powerful features.
    
