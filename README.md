# Code Optimizer

This app provides a pipeline using CrewAI to generate and optimize code.

### Agent Roles

- **Code Parser**: Understands the problem statement provided and analyzes the constraints.
- **Code Generator**: Generates a code with the help of internet and human input, that would solve the given problem.
- **Complexity Analyzer**: Analyzes the time and space complexity of the code generated.
- **Code Optimizer**: Tries to optimize the code and adjusts the optimized code based on human feedback.
- **Refactoring Agent**: Cleans up the code.

### Requirements

Install dependencies:

```bash
pip install -r requirements.txt
```

Environment variables required:
Set OpenAI API Key, Serper API Key in app.py

### Usage

Run the app using:

```bash
python app.py
```
