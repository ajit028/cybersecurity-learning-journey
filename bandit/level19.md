# Bandit Level 19 → 20

## Goal
Use setuid binary to read password

## Approach
Execute binary with elevated privileges.

## Commands Used
./bandit20-do cat /etc/bandit_pass/bandit20

## Explanation
The binary runs with higher privileges and accesses restricted files.

## Key Learning
Setuid concept.

## Real World Use
Privilege escalation.
