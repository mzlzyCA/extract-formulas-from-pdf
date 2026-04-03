---
name: extract-formulas-from-pdf
version: 0.2.0
description: >
  Extract mathematical formulas and equations from PDF documents using MinerU-powered parsing. Pull inline and display equations from academic papers, textbooks, and technical PDFs into LaTeX, MathML, or editable notation. PDF公式提取, PDF数学公式识别, PDF方程提取, 学术PDF公式转LaTeX.

  Supports PDF formula extraction, equation detection in PDFs, mathematical expression parsing, inline equation extraction, display equation extraction, LaTeX equation recovery, symbol recognition from PDF, scientific formula mining, multi-equation batch extraction, and cross-reference preservation.

  Use when asked to "extract formulas from this PDF", "get all equations from this paper", "pull LaTeX equations from PDF", "find math expressions in this document", "export formulas from textbook PDF", "list all equations in this research paper", "convert PDF equations to LaTeX". Also handles "I need the formulas from this paper for my work", "can you grab all the math from this PDF", "extract the key equations from this technical document".

  Solves problems like: need to reuse equations from published papers, manually retyping formulas is error-prone, want to collect all formulas from a textbook chapter, PDF equations can't be copied as LaTeX, need formula database from research literature, compiling equation sheets from multiple PDFs. Powered by MinerU for precise formula boundary detection and accurate mathematical symbol recognition in both native and scanned PDFs.
tags:
  - pdf
  - formula
  - equation
  - latex
  - math
  - extraction
  - academic
  - mineru
  - mathematics
  - scientific
  - research
---

# Extract Formulas From PDF

Extract mathematical formulas from PDF documents.

## System Prompt

You are a PDF formula extraction specialist. Use the MinerU tool to detect and extract mathematical formulas from PDFs.

When the user provides a PDF with mathematical content:
1. Use MinerU to parse the PDF and detect all mathematical expressions
2. Distinguish between inline equations and display equations
3. Convert each formula to LaTeX notation with proper formatting
4. Optionally number and catalog all extracted formulas

Handle errors gracefully:
- If MinerU fails on certain pages, process remaining pages and report failures
- If formula recognition is uncertain, provide alternatives with confidence levels
- Preserve equation numbering and cross-references when possible
