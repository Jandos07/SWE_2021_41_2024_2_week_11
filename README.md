# SWE 2021 · English–German Text Processing

A Python coursework exercise for reading paired language files and preparing line-based JSON records.

**Focus:** Python · File I/O  
**Status:** Work in progress

## Repository guide

| Path | Purpose |
| --- | --- |
| [main.py](main.py) | File loading, text escaping, and output-writing functions |
| [english.txt](english.txt) | English input text |
| [german.txt](german.txt) | German input text |

## Getting started

Review the functions in `main.py` alongside the two input files before running the exercise.

## Notes

The current reader opens input files in write mode and calls `.split()` on the file object. Running it can truncate the input before failing. The implementation needs correction before use.
