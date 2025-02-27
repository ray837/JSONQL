# JSONQL: JSON Query and Path Generator

JSONQL is a Python library that helps you quickly query JSON data and generate JSON paths for debugging and development. It provides functions to locate keys by a given value and recursively generate full paths for nested JSON structures.

## Features

- **keys_by_value(data, target_value):**  
  Search your JSON data for a specific target value and return a list of key names where that value appears.

- **generate_path(data, payload_name="payload"):**  
  Recursively generate JSON paths for each key in your JSON data. Useful for understanding the structure of nested JSON objects.

- **recursive_path_finder(current_path, value, result):**  
  A helper function that traverses the JSON structure to build complete key paths.

## Installation

Clone the repository and install the package locally:

```bash
https://github.com/ray837/JSONQL.git
cd JSONQL
pip install .
