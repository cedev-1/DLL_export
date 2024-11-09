# DLL Exports Extraction

This Python project extracts the names of exported functions from a Windows DLL file using the `pefile` library. The names of the functions are then saved into a JSON file.

## Prerequisites

- Python 3.x
- `pefile` library

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Install the dependencies:
   ```bash
   pip install pefile
   ```

## Usage

1. Modify the DLL file path in the `DLL_exports.py` script:
   ```python
   pe = pefile.PE("C:\\Windows\\System32\\kernel32.dll")
   ```

2. Run the script:
   ```bash
   python DLL_exports.py
   ```

3. The names of the exported functions will be saved in a file called `exports.json`.
ails.