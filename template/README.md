# Challenge X - Write Your Own X

This challenge can be found here - https://codingchallenges.fyi/challenges/[x]

## Description

This x tool does a,b,c ...

## Usage

You can use `x` to run the tool as follows:

```bash
# Using input file
x [-option] <path/to/input-file>

# Using standard input
cat filename | x [-option] -

# Using output with input file
x [-option] <path/to/input-file> <path/to/output-file>

# Using output with standard input
cat filename | x [-option] - <path/to/output-file>
```

The following options are supported:

- `-c` or `--count`: prefix lines by the number of occurrences
- `-d` or `--repeated`: only print duplicate lines
- `-u`: only print unique lines
- `-`: read from standard input

## Run tests

To run the tests for the uniq tool, go to the root directory of this repository and run the following command:

```bash
cargo test
```