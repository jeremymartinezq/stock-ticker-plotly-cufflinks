# Stock Ticker Analysis: Tata Motors (Plotly & Cufflinks)

## Overview
This script provides visual analysis of Tata Motors' historical stock data using Plotly and Cufflinks. It generates interactive candlestick and area charts to help users visualize stock price movements over time.

## Features
- **Candlestick Chart**: Displays Tata Motors' stock price movements, including open, high, low, and close values.
- **Area Chart**: Illustrates the trend of closing prices over time.

## Requirements
Ensure you have the following Python libraries installed before running the script:

```bash
pip install pandas plotly cufflinks
```

## Usage
1. **Prepare Data**: The script requires a CSV file named `Tata_Motors_Ltd._historical_data.csv` containing Tata Motors' historical stock data.
2. **Run the Script**: Execute the script to generate the visualizations.

## File Structure
- **Tata_Motors_Ltd._historical_data.csv**: Historical stock data file.
- **Script**: Loads data, processes it, and generates charts.

## How It Works
1. **Data Loading**: Reads Tata Motors' historical stock prices from the CSV file.
2. **Data Preprocessing**:
   - Converts the 'Date' column to a datetime format.
   - Sets 'Date' as the index.
   - Renames 'Open', 'High', 'Low', and 'Close' columns.
3. **Visualization**:
   - Generates a **Candlestick Chart** using Plotly.
   - Generates an **Area Chart** using Cufflinks.

## Running the Script
Simply execute the Python script:
```bash
python script.py
```
The interactive charts will be displayed in your browser.

## Example Output
- **Candlestick Chart**: Displays open, high, low, and close prices.
- **Area Chart**: Shows the trend of closing prices over time.
- <img width="462" alt="image" src="https://github.com/user-attachments/assets/eb96ec19-1b1a-481b-abcc-2abce0194bbf" />
- <img width="465" alt="image" src="https://github.com/user-attachments/assets/7d44b47c-a3b9-4aa6-a98f-107e6caf5b18" />


## Notes
- Ensure the CSV file is correctly formatted with columns: `Date, Open, High, Low, Close`.
- The script runs in an offline mode for Plotly, so an internet connection is not required for visualization.

## Author
Developed by Jeremy Martinez-Quinones.

## License
This project is licensed under the MIT License - see LICENSE file for details.

