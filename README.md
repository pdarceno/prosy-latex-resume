# Prosy Resume Builder

This project builds a PDF resume using LaTeX. It uses a custom `.sty` file for styling (`prosy_resume.sty`) and compiles it automatically via a Python script.

## How it works

The Python script runs `pdflatex` to compile the LaTeX resume template. Make sure `pdflatex` is installed on your system and available in your system's PATH.

### 🛠 Requirements

- Python 3.x
- LaTeX (e.g. TeX Live or MiKTeX)

### 📄 Files

- `prosy_resume.sty` — custom LaTeX style for the resume
- `resume.tex` — main LaTeX file (not included in this snippet but required)
- `build_resume.py` — Python script that compiles the PDF

### 🔧 Build your resume

Run the script:

```bash
python run.py
