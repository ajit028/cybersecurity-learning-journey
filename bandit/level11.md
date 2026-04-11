# Bandit Level 11 → 12

## Goal
Decode ROT13 encoded data

## Approach
Use character translation to decode the text.

## Commands Used
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'

## Explanation
ROT13 shifts letters by 13 positions. tr is used to decode it.

## Key Learning
Text transformation techniques.

## Real World Use
Understanding simple obfuscation methods.
