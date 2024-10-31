# Prompt Engineering Course Materials

This repository contains materials for a comprehensive prompt engineering course, focusing on practical applications and experimentation with Large Language Models (LLMs).

## Setup

### Using Conda

1. Create environment:

```bash
conda create -n prompt-eng-course python=3.10
```

2. Activate environment:
```bash
conda activate prompt-eng-course
```

3. Install requirements:

```bash
pip install -r requirements/requirements.txt
```

### Jupyter Notebook Setup

To use this environment with Jupyter notebooks:
```bash
python -m ipykernel install --user --name=prompt-eng-course
```

## Course Structure

### Module 1: Introduction to Prompt Engineering
- Basic concepts and components
- Understanding prompt structure
- Components of prompts:
  - Instructions
  - Context
  - Input data
  - Output indicators

### Module 2: Prompt Engineering Framework
1. Define your task clearly
2. Define evaluation metrics
3. Generate candidate prompts
4. Experiment and test
5. Determine when to stop experimenting

### Module 3: Practical Applications
- Text summarization
- Reference extraction
- Question answering
- Knowledge generation

## Notebooks

The repository includes several Jupyter notebooks demonstrating various aspects of prompt engineering:

### Module 1: Foundations
1. `demo-prompt-eng-intro.ipynb` - Introduction to prompt engineering basics with practical examples
2. `1.0-intro-prompt-eng-prompt-basics.ipynb` - Core concepts of prompt engineering
3. `1.1-simple-framework-for-building-prompts.ipynb` - Framework for building effective prompts
4. `1.2-prototyping-prompts.ipynb` - Techniques for prototyping and iterating on prompts

### Module 2: Advanced Techniques
1. `2.2-decomposing-problems-beyond-chain-of-thought.ipynb` - Breaking down complex problems
2. `2.4-problem-solving-tree-of-thoughts.ipynb` - Tree of Thoughts approach for problem-solving
3. `2.5-structured-prompting-openai-function-calling-pydantic.ipynb` - Structured prompting with OpenAI
4. `2.6-retrieval-augmented-generation-qa-over-docs.ipynb` - RAG for question answering
5. `2.7-prompt-engineering-frameworks.ipynb` - Overview of prompt engineering frameworks

### Module 3: Use Cases
1. `3.1-text-summarization-use-case.ipynb` - Text summarization examples and techniques
2. `3.2-code-generation-use-case.ipynb` - Code generation examples
3. `3.3-qa-prompting-to-understand-papers.ipynb` - Question-answering for research papers
4. `3.4-designing-prompt-engineering-workflow.ipynb` - Workflow design for prompt engineering

### Additional Resources
1. `prompts-as-composable-primitives.ipynb` - Understanding prompts as building blocks
2. `prompt-engineering-for-studying.ipynb` - Educational applications
3. `quiz_from_sources.ipynb` - Generating quizzes from source materials

## Tools and Frameworks Covered

- OpenAI GPT models
- LangChain
- Instructor
- Guidance
- Marvin
- LM-Studio
- Outlines
- LLM-CLI
- Fabric
- SGLang

## Contributing

Feel free to submit issues and enhancement requests.

## License

Please refer to the LICENSE file in the repository.

## References

For additional resources on prompt engineering, refer to:
- [OpenAI's Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)