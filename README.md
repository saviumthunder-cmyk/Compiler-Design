# Compiler Design Project

This project implements 6 compiler design topics:

1. Lexical Analyzer
2. First and Follow Sets
3. Left Recursion Removal
4. NFA to DFA Conversion
5. Parsing Table Construction
6. Regex to NFA Conversion

## How to Run

Each topic has its own Python script and input/output files.

- `scripts/lexical_analyzer.py`: Reads `inputs/input_lex.txt`, writes `outputs/output_lex.txt`
- `scripts/first_follow.py`: Reads `inputs/input_first.txt`, writes `outputs/output_first.txt`
- `scripts/left_recursion.py`: Reads `inputs/input_left.txt`, writes `outputs/output_left.txt`
- `scripts/nfa_to_dfa.py`: Reads `inputs/input_nfa.txt`, writes `outputs/output_dfa.txt`
- `scripts/parsing_table.py`: Reads `inputs/input_table.txt`, writes `outputs/output_table.txt`
- `scripts/regex_to_nfa.py`: Reads `inputs/input_regex.txt`, writes `outputs/output_nfa.txt`

Run each with `python scripts/<script>.py`

## Sample Inputs

- `inputs/input_lex.txt`: `if x = 5 + 3`
- `inputs/input_first.txt`: `S -> aB | b\nB -> c | dS`
- `inputs/input_left.txt`: `A -> A b | c`
- `inputs/input_nfa.txt`: `2\na\n1 -1\n1 -1\n0\n1`
- `inputs/input_table.txt`: same as `inputs/input_first.txt`
- `inputs/input_regex.txt`: `a|b`

**GOHUL NANDA**
RA2311003050027