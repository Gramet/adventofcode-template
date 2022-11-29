# adventofcode-template
Python template for Advent of Code

# Install

Get your AoC session cookie and put it in a `.env` (session=XXXXX)

## Helpers
- `python src/prepare_year.py 2022`: Will create the directories for each day using the template in `year_template`
- `python src/download.py 1 2022`: Will download the input for problem1 of year 2022 (NB: You need to run `prepare_year`first)
- `python src/submit.py 3 1 2022`: Will submit solution for part 1 of day 3 of year 2022.

## Workflow

- When data become available, run the download script.
- Implement your solution in the `solve_part_1` and `solve_part_2` functions
- Use the `src/submit.py` CLI to submit any part once you are satisfied with it. You'll get any error message from AoC in the terminal.