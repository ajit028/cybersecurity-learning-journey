# Bandit Level 11 → 12

## Goal
Read data from file encoded with ROT13

## Commands Used
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'

## Explanation
ROT13 shifts letters by 13 positions.
The tr command is used to decode the text.

## Key Learning
Basic text transformation.

## Real World Use
Decoding simple obfuscation techniques.
