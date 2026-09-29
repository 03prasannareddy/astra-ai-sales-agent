
# ASTRA - AI Sales Agent That Never Forgets

> Built for Hindsight x Groq Hackathon - AI Agent that stores 200 deals in long-term memory

## Problem
Traditional AI sales agents forget past deals. Every conversation starts from zero.

## Solution: ASTRA
We built ASTRA with 2 powers:
- **Hindsight Bank `astra-deals`** - Stores 200 deals in long-term memory
- **Groq `openai/gpt-oss-20b`** - Ultra-fast reasoning

## Learning Loop
Retain (save 10 deals at a time) -> Recall (find relevant precedent) -> Personalized Answer (3-step playbook)

## Terminal Proof
## Example
Client: "Price too high"
ASTRA recalls: How we closed similar deal in March with discount + ROI logic
Gives: Personalized 3-step closing playbook

## Links
- Medium: https://medium.com/@03prasannareddy/ai-sales-agent-that-never-forgets-how-i-stored-200-deals-in-long-term-memory-98e13bacff21

## Stack
- Hindsight Memory Bank
- Groq API openai/gpt-oss-20b
- Python

## Team
Built for Hindsight x Groq Hackathon 2026