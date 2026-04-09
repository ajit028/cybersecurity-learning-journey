# Bandit Level 6 → 7

## Goal
Find file with specific owner, group, and size

## Commands Used
find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null

## Explanation
Used find with filters and suppressed errors.

## Key Learning
System-wide search and permission handling.

## Real World Use
Searching for sensitive files across systems.
