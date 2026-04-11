# Bandit Level 1 → 2

## Goal
Read a file named '-'

## Approach
The filename '-' is treated as standard input, so it must be accessed differently.

## Commands Used
ls
cat ./-

## Explanation
Using ./- forces the shell to treat '-' as a file instead of stdin.

## Key Learning
Handling special filenames.

## Real World Use
Handling edge-case filenames in systems.
