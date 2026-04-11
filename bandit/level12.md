# Bandit Level 12 → 13

## Goal
Extract password from a file with multiple compression layers

## Commands Used
xxd -r data.txt > file
file file
mv file file.gz
gunzip file.gz

## Explanation
Convert hex dump back to binary.
Identify file type and decompress repeatedly.

## Key Learning
Working with encoded and compressed files.

## Real World Use
Used in malware analysis and digital forensics.
