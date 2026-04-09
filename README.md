# COMPX234 Lab 2: Readers-Writers Problem

## Description
Python implementation of the Readers-Writers synchronization problem using a monitor with threading.Condition.

## Design
- Monitor class controls access to shared resource
- Multiple readers can read simultaneously
- Writers require exclusive access
- Uses condition variables for waiting and signaling

## How to Run
```bash
python readers_writers.py
