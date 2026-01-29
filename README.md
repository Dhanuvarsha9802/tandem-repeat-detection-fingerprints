# Tandem Repeat Detection using Fingerprints

## Overview
This project implements a fingerprint-based approach to identify tandem repeats with mismatches in genomic sequences.  
The method is designed to efficiently detect repeating patterns while allowing a controlled number of mismatches, making it suitable for real-world biological data.

This work is part of my MSc dissertation in Data Science and Analytics at Brunel University London.

---

## Problem Statement
Tandem repeats play a significant role in genomic structure and function.  
However, detecting tandem repeats with mismatches is computationally challenging using traditional exact-matching methods.

This project explores how **fingerprint-based techniques** can be used to efficiently detect such repeats in large genomic sequences.

---

## Methodology (High-level)
- Input genomic sequence
- Generate fingerprints for substrings
- Compare fingerprints to identify repeating regions
- Allow mismatches while preserving detection accuracy

---

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Dhanuvarsha9802/tandem-repeat-detection-fingerprints.git
cd tandem-repeat-detection-fingerprints
python src/fingerprint_tr.py



## Project Structure
