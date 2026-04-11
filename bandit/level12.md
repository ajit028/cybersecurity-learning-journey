# Bandit Level 12 → 13

## Goal
Extract password from multiple compressed files

## Approach
Convert hex to binary and repeatedly decompress.

## Commands Used
xxd -r data.txt > file
file file
mv file file.gz
gunzip file.gz

## Explanation
The file is layered with multiple compressions that must be removed step by step.

## Key Learning
Handling multiple file encodings.

## Real World Use
Forensics and malware analysis.
