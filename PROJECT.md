# IS 218 Test 1

**Name:** Momo Sacko

## Purpose

This project is for IS 218 Test 1. The purpose is to set up and test a Python calculator package that supports addition and subtraction.

## Environment

I keep `.venv` local because it contains packages installed specifically for my environment and does not need to be stored in Git. I commit `requirements.txt` so other developers can install the same dependencies and recreate the project environment.

## Setup

Create the virtual environment:

    python3 -m venv .venv

Activate the virtual environment:

    source .venv/bin/activate

Install the required dependencies:

    python -m pip install -r requirements.txt

## Testing

Run all six student tests:

    python -m pytest

Run the student tests and the supplied acceptance checks:

    python -m pytest tests checks -v

## Test Explanation

One of my addition tests uses 2 and 3 as inputs and expects a result of 5. The assertion checks that the value returned by the `add` function is equal to the expected result of 5.

## Issues

- Issue 1: https://github.com/ms543-create/is218_test1_official/issues/1
- Issue 2: https://github.com/ms543-create/is218_test1_official/issues/2
- Issue 3: https://github.com/ms543-create/is218_test1_official/issues/3
- Issue 4: https://github.com/ms543-create/is218_test1_official/issues/4