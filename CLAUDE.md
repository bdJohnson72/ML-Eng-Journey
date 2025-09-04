# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an AI learning repository focused on following Andrej Karpathy's "Zero to Hero" neural networks course. The project is in early stages and primarily uses Jupyter notebooks for interactive learning.

## Development Environment Setup

**Python Version**: 3.13.5  
**Virtual Environment**: `.venv/`

Always activate the virtual environment before working:
```bash
source .venv/bin/activate
```

## Common Commands

### Environment Management
```bash
# Activate virtual environment
source .venv/bin/activate

# Install common ML dependencies (likely needed as course progresses)
pip install numpy matplotlib torch jupyter jupyterlab pandas
```

### Jupyter Development
```bash
# Start Jupyter Lab for notebook development
jupyter lab

# Start Jupyter Notebook (alternative)
jupyter notebook
```

## Code Architecture

### Directory Structure
- `karpathy/` - Course materials and notebooks following Karpathy's neural networks course
- `.venv/` - Python virtual environment with Python 3.13.5
- `.idea/` - IntelliJ/PyCharm IDE configuration

### Development Approach
- **Primary Development**: Jupyter notebooks in `karpathy/` directory
- **Learning-Focused**: Code is organized by course instructor/curriculum
- **Interactive Development**: Notebooks are used for hands-on neural network implementation

## Important Notes

- This is a learning repository, not a production codebase
- No formal build/test/lint processes are currently configured
- Dependencies will likely expand as the course progresses (expect PyTorch, NumPy, Matplotlib)
- Course materials are organized by instructor in separate directories