# Wrangler Enhancement: Byte Size and Time Duration Units Parsers

## Overview
This project extends the CDAP Wrangler library to handle byte size (e.g., `10KB`) and time duration (e.g., `200ms`) values. It also introduces a new directive, `aggregate-stats`, to calculate aggregates on these types.

## Features
- **New Parsers:** `ByteSize` and `TimeDuration`.
- **New Directive:** `aggregate-stats` for aggregating size and time data.
- **Grammar Updates:** Support for `BYTE_SIZE` and `TIME_DURATION` tokens.

## Usage
1. Add the following directive to your recipe:
2. Input: A dataset with columns for size and time.
3. Output: Aggregate values in the specified columns.

## Installation
1. Clone the repository.
2. Build the project:
3. Deploy the library in your Wrangler environment.

## Testing
Run the unit tests:

## Prompts Used
See `prompts.txt` for AI assistance prompts.
Prompt 1: How to define lexer and parser rules in ANTLR?
Prompt 2: How to implement a custom directive in Wrangler?
Prompt 3: Provide example code for parsing byte size strings in Java.




