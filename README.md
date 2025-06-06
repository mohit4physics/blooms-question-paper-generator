# Bloom's Taxonomy-Based Question Paper Generator

This is a Python Tkinter application to generate question papers based on Bloom’s Taxonomy levels.

## Features

- Load questions from a CSV file with subject, level, marks, and metadata.
- Specify exam details (institute, exam title, program, course, date, time, total marks).
- Select questions by Bloom’s levels and generate a formatted question paper.
- Export the question paper to PDF or Word format.
- Supports multiple subjects and level-wise question distribution.
- Responsive UI using threading for CSV loading.

## Input CSV Format
Levels supported: Remembering, Understanding, Applying, Analyzing, Evaluating, Creating.

## Output
The current outputs:
PDF: Uses basic tables but lacks structured formatting (e.g., proper headings, spacing, consistent fonts).
Word: Generates tables but without layout control (no column widths, styles, or spacing).

## Installation
1. Clone this repository.
2. Install dependencies:

## requirements
reportlab
python-docx
chardet

## Acknowledgement
ChatGPT greatly help to write the code and advancements.
