# Vibration-Analysis

## What This Project Contains

- **CSV Files Folder**  
  Merged vibration data, with frequency and vibration velocity for each direction in a room.  
  Example: `Room167_MergedVibrationData.csv`

- **Data Folders**  
  Folders named like `113_data/`, `167_data/`, etc.  
  Each contains raw text files (e.g. `169_run22_in_183S.txt`) with vibration readings for that room.

- **Jupyter Notebooks (.ipynb)**  
  These contain Python code to:
  - Read the raw data
  - Merge and organize it
  - Create graphs for analysis

## What the Analysis Shows

- **Line Graphs**: Show how vibration changes with frequency.
- **Bar Charts**: Show the average vibration level in each direction.
- **Spider Charts**: Help visualize which direction has the strongest vibration at a specific frequency (like 20 Hz).
- **Log Graphs**: Show the same data with a better view of small values.

## How the Data Works

- Each `.txt` file has two columns:  
  1. Frequency (Hz)  
  2. Vibration velocity (in/s RMS)

- The direction (e.g., NE, M, S) is in the filename.

- The CSV files organize this data into a table, with one column for frequency and one for each direction.

## How to Use

1. Open a Jupyter notebook (in Google Colab or locally).
2. Upload the `.txt` or `.csv` files.
3. Run the notebook cells to generate the graphs.
4. You can change the room or frequency range if needed.


