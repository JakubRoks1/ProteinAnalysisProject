# UniProt Protein Analyzer

This tool enables the analysis and visualization of proteins from the `uniprot_receptor.xml.gz` file.

## About:

This project was developed as the second university assignment for the Python programming course. It provides functionalities for analyzing protein data and utilizes the `matplotlib` library for data visualization.

## Dependencies:

Make sure to check the `Pipfile` for detailed dependency information.

## Getting Started:

To utilize the functionalities of this package, follow these simple commands in your terminal:

- `python uniplot.py dump` - Retrieves comprehensive information about all protein chains.
- `python uniplot.py names` - Fetches the names of each protein chain.
- `python uniplot.py average` - Calculates and displays the average length of a protein chain.
- `python uniplot.py plot-bar` - Generates a bar chart representing the average length of protein chains categorized by the highest taxonomic rank.

For further details, utilize `python uniplot.py --help` or `python uniplot.py -h` in your terminal.

## Built With:

- PyCharm - A robust IDE for Python development.
- Pipenv - Simplifying dependency management.
- Matplotlib - A powerful plotting library for Python.
