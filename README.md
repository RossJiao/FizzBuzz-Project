# FizzBuzz Project

## Overview
A Python program that prints numbers from 1 to 100, replacing multiples of 3
with "Fizz", multiples of 5 with "Buzz", and multiples of both with "FizzBuzz".

## Rules
- For each multiple of 3: print **Fizz**
- For each multiple of 5: print **Buzz**
- For multiples of both 3 and 5: print **FizzBuzz**
- For all other numbers: print the number itself

## Repository Structure
└── fizzbuzz.py    # Main program

## Setup

### Prerequisites
- Python 3.x (no third-party packages required)

### Clone the repository
```bash
git clone https://github.com/RossJiao/fizzbuzz-project.git
cd fizzbuzz-project
```

## Run
```bash
python3 fizzbuzz.py
```

## Sample Output
1

2

Fizz

4

Buzz

Fizz

7

8

Fizz

Buzz

11

Fizz

13

14

FizzBuzz

...

## Approach
The program uses a `for` loop from 1 to 100 and checks divisibility using
the modulo operator `%`. The order of conditions matters — the FizzBuzz
check must come before the individual Fizz and Buzz checks.
