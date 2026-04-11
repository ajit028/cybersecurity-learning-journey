# Bandit Level 6 → 7

## Goal
Find a file owned by a specific user

## Approach
Search system-wide with ownership filters.

## Commands Used
find / -type f -user bandit7 -group bandit6 2>/dev/null

## Explanation
Search entire system and ignore permission errors.

## Key Learning
Advanced file searching.

## Real World Use
System auditing.
