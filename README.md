# append

`append` is a simple command-line tool that adds a string to the start or end of every line in a text file.

## Installation

Install the package using pip:

```pip install append```

## Usage

Use append from the command line:

    append -s "start_string" -e "end_string" input.txt -o output.txt

    -s, --start: String to add at the start of each line (optional).
    -e, --end: String to add at the end of each line (optional).
    filename: Input file (optional, reads from stdin if omitted).
    -o, --output: Output file (optional, writes to stdout if omitted).

## Example

Add >> to the start and << to the end of each line:

    append -s ">> " -e " <<" example.txt -o result.txt

