## Project Architecture
The system follows a linear pipeline. The "Orchestrator" (Python script) acts as the bridge between the Brain (Ollama) and the Factory (CadQuery).

## Prerequisites & Environment Setup
We need a Python environment that can handle 3D geometry.

1. Install Ollama
2. Python dependencies: *ollama, cadquery*

# Problem: 
There aren't any good LLMs for making CadQuerry code from text. The one I found that were supposed to work best for it gave up on simple task.  