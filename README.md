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

The CSV file should have columns:

| Subject | Level       | Marks | Question                                         | CO  | CL  | KC  |
|---------|-------------|-------|-------------------------------------------------|-----|-----|-----|
| Physics | Remembering | 1     | What is Newton's First Law?                      | CO1 | CL1 | KC1 |

Levels supported: Remembering, Understanding, Applying, Analyzing, Evaluating, Creating.

## Installation

1. Clone this repository.
2. Install dependencies:

```bash
pip install -r requirements.txt
