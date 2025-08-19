# LangGraph Projects

A comprehensive collection of example projects and workflows built using LangGraph, demonstrating various applications of sequential workflow processing with Language Models.

## Project Description

This repository contains a collection of Jupyter notebooks and Python scripts that showcase different implementations of LangGraph - a framework for building stateful, multi-step workflows with Language Models. The projects range from simple sequential workflows to complex applications with database integration and streaming capabilities.

## Features

1. **Sequential Workflows**

   - Prompt chaining for blog content generation
   - API integration for data retrieval
   - BMI calculation workflow
   - Quadratic equation solver

2. **Interactive Applications**

   - Batsman performance analysis
   - UPSC essay evaluation system
   - X (Twitter) post generator
   - Review reply workflow
   - Basic chatbot implementation

3. **Full Project Implementation**
   - Database integration with SQLite
   - Streaming capabilities
   - Threading implementation
   - Persistence and fault tolerance
   - Frontend integration with Streamlit

## Installation Instructions

1. Clone the repository:

```bash
git clone https://github.com/Sunny-commit/LangGraph_Projects.git
cd LangGraph_Projects
```

2. Set up a Python virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required dependencies:

```bash
pip install langgraph langchain-openai python-dotenv streamlit
```

4. Create a `.env` file and add your OpenAI API key:

```
OPENAI_API_KEY=your_api_key_here
```

## Usage Instructions

### Jupyter Notebooks

1. Each numbered notebook (4-9) contains standalone examples of different LangGraph implementations
2. The `Sequential_Workflows_Projects` folder contains additional examples focused on specific use cases
3. The `Full Project` folder demonstrates a complete application with frontend and backend integration

### Running the Full Project

1. Navigate to the Full Project directory:

```bash
cd "Full Project"
```

2. Run the Streamlit frontend:

```bash
streamlit run streamlit_frontend.py
```

## Example Projects

1. **Blog Content Generator**

   - Creates outlines and full blog posts from titles
   - Implements a sequential workflow for content creation

2. **UPSC Essay Evaluator**

   - Evaluates essays based on language, analysis, and thought process
   - Provides comprehensive feedback and scoring

3. **X Post Generator**

   - Generates and evaluates social media posts
   - Implements feedback loop for content optimization

4. **Review Reply System**
   - Analyzes sentiment of reviews
   - Generates appropriate responses based on sentiment analysis

## Contributing Guidelines

1. Fork the repository
2. Create a new branch for your feature
3. Implement your changes
4. Write appropriate documentation
5. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact Information

Created by [Sunny-commit](https://github.com/Sunny-commit)

For questions and feedback, please open an issue in the GitHub repository.
