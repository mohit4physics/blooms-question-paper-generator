# Bloom's Taxonomy Question Paper Generator

A Python GUI tool designed for educators to automatically generate question papers aligned with **Bloom's Taxonomy**. Load questions from a CSV, customize exam parameters, and export structured papers in **PDF** or **Word** formats.

---

## Repository Contents

`question_paper_generator.py` : Main Python GUI application using Tkinter and ReportLab.
`questions.csv`: Sample question bank with Bloom's levels and metadata.
`LICENSE`: Open-source license (MIT).                                 
`README.md`


## Features

- GUI-based interface using **Tkinter**
- Load questions categorized by:
  - Subject
  - Bloom’s Taxonomy level (Remembering → Creating)
  - CO (Course Outcome), CL (Cognitive Level), KC (Knowledge Category)
- Specify number of questions per level
- Customize exam information (date, time, title, etc.)
- Export question paper as:
  - ✅ PDF (structured table format)
  - ✅ Word document (basic table format)

---

## Requirements

Ensure you have **Python 3.7+** and these libraries installed:

```bash
pip install reportlab python-docx chardet
