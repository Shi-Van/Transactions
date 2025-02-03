# Setting Up Jupyter Notebook with Virtual Environment

## Installation Instructions

### macOS
1. Install Jupyter Notebook:
   ```bash
   brew install jupyter notebook
   ```

2. Verify installation:
   ```bash
   jupyter --version
   ```

### Windows
1. Install Jupyter Notebook using pip:
   ```powershell
   pip install notebook
   ```

2. Verify installation:
   ```powershell
   jupyter --version
   ```

### Linux
1. Install Jupyter Notebook:
   ```bash
   sudo apt update && sudo apt install -y python3-pip
   pip install notebook
   ```

2. Verify installation:
   ```bash
   jupyter --version
   ```

## Creating and Activating a Virtual Environment

### Create a Virtual Environment
Run the following command in the project root directory:
```bash
python -m venv venv
```

### Activate the Virtual Environment

#### macOS & Linux:
```bash
source venv/bin/activate
```

#### Windows (CMD):
```powershell
venv\Scripts\activate
```

#### Windows (PowerShell):
```powershell
.\venv\Scripts\Activate.ps1
```

## Install Dependencies
After activating the virtual environment, install the required packages:
```bash
pip install ipython ipykernel
```

## Running Jupyter Notebook
Start Jupyter Notebook by running:
```bash
jupyter notebook
```

