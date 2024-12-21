# My Python Project

This project is a Python application that utilizes a virtual environment and supports Jupyter Notebooks for data analysis and visualization.

## Project Structure

```
my-python-project
├── src
│   ├── main.py          # Main entry point of the application
├── notebooks
│   └── example.ipynb    # Jupyter Notebook for analysis and documentation
├── venv                  # Virtual environment for project dependencies
├── requirements.txt      # List of project dependencies
└── README.md             # Project documentation
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd my-python-project
   ```

2. **Create a virtual environment:**
   ```
   python3 -m venv venv
   ```

3. **Activate the virtual environment:**
   ```
   source venv/bin/activate
   ```

4. **Install the required packages:**
   ```
   pip install -r requirements.txt
   ```

5. **Run the application:**
   ```
   python src/main.py
   ```

## Jupyter Notebook

To work with the Jupyter Notebook:

1. Ensure the virtual environment is activated.
2. Install Jupyter if it's not included in `requirements.txt`:
   ```
   pip install jupyter
   ```
3. Launch Jupyter Notebook:
   ```
   jupyter notebook notebooks/example.ipynb
   ```

## Tesseract

Para usar esse notebook, é necessário ter tesseract instalado em seu sistema operacional