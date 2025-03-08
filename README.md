# Brainwave_matrix_intern
Task 1 
import pandas as pd

try:
    df = pd.read_excel('task1datafinal.xlsx', sheet_name='Sheet1') # Assuming the data is in 'Sheet1', adjust if needed
    display(df.head())
except FileNotFoundError:
    print("Error: 'task1datafinal.xlsx' not found.")
    df = None
except Exception as e:
    print(f"An error occurred: {e}")
    df = None
