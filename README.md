# Work Test Project - Setup Instructions

## Prerequisites
Ensure you have Python 3 installed on your system. You can verify by running:
```bash
python3 --version
```
If Python is not installed, download it from the [official Python website](https://www.python.org/downloads/) or use Homebrew to install:
```bash
brew install python
```

## Setting Up the Environment

### Step 1: Clone the Repository
Clone the repository to your local machine:
```bash
git clone https://github.com/chezki770/work-test.git
```
Navigate into the project directory:
```bash
cd work-test
```

### Step 2: Create a Virtual Environment
Use `python3` to create a virtual environment:
```bash
python3 -m venv venv
```

### Step 3: Activate the Virtual Environment
Activate the virtual environment:
```bash
source venv/bin/activate
```
If successful, your terminal prompt will change, showing `(venv)` at the beginning.

### Step 4: Install Dependencies
With the virtual environment activated, install the required Python libraries:
```bash
pip install pandas openpyxl
```

### Step 5: Run the Script
Run the main script to process data:
```bash
python main.py
```

## Troubleshooting

### `python3` Not Found
If `python3` is not recognized, ensure it is installed and check its path:
```bash
which python3
```
The output should display the installation path, such as `/usr/local/bin/python3`.

### `pip` Not Found
If `pip` is missing, install it using:
```bash
python3 -m ensurepip --upgrade
```

### Virtual Environment Activation Issues
If the virtual environment activation fails:
- Ensure the `venv` folder exists.
- Verify the correct activation command is used:
  - macOS/Linux: `source venv/bin/activate`
  - Windows: `venv\Scripts\activate`

## Additional Notes
- Use `python3` consistently if `python` points to an older Python version.
- Deactivate the virtual environment after you're done by running:
  ```bash
  deactivate
  
