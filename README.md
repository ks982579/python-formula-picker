# Python Formula Picker

## Summary

> Comming Soon

## Design Process

> Going to track the project step by step.

Begin with the basics, I'll be using Windows WSL with Python 3.11.0rcl to create this project. 

```bash
mkdir formula_picker
cd formula_picker
git init
git branch -m main
echo "# Python Formula Picker" >> README.md
python -m venv venv
source venv/bin/activate
```

You will probably want a useful ".gitignore" list, which can be found on [github.com/github/gitignore](https://github.com/github/gitignore/blob/main/Python.gitignore). 

My idea is the following:
- scope out necessary functions and/or classes and methods for the project in a notebook.
- using test-driven development, creating a full featured program with the notebook functions to accomplish the goal that also tests edge cases.
- Ensure functions, classes, and methods are properly documented. 
- optimize and refactor the program for best performance. 

That brings us to this point. Let's start building the project in a Jupyter Notebook. Create a `main.ipynb` file, and let VisualStudio code download the proper extension. 

```bash
pip install numpy pandas scipy
```