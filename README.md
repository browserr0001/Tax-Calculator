# Tax Calculator

The **Tax Calculator** is a Python application with a graphical user interface (GUI) built using the `tkinter` library. It allows users to calculate tax and total cost based on the entered cost and selected country or state tax rate.

## Features

- User-friendly interface for entering cost and selecting a country or state.
- Retrieves tax rates from a CSV file for various countries or states.
- Calculates tax and total cost dynamically upon user input.
- Displays the calculated tax and total cost.

## How to Use

1. **Cost Entry**: Enter the cost of the item in the provided field.

2. **Country/State Selection**: Select the country or state from the dropdown menu. This will determine the applicable tax rate.

3. **Calculate**: Click the "Calculate" button to compute the tax and total cost.

4. **Results**: The calculated tax amount and total cost (including tax) will be displayed.

## Dependencies

- Python 3.x
- `tkinter` library for GUI
- `pandas` for data manipulation

## Usage

1. Run the Python script `tax_calculator.py`.

2. The GUI window will appear.

3. Enter the cost and select the country or state.

4. Click "Calculate" to see the results.

## File Structure

- `tax_calculator.py`: Main Python script for the Tax Calculator application.
- `tax.csv`: CSV file containing tax rates for different countries or states.
- `tax.png`: Icon image for the application.

## Notes

- The application uses `tkinter` for the GUI, and `pandas` to read tax rates from the CSV file.
- Ensure that the CSV file `tax.csv` is present in the same directory as the Python script.
- The application icon is set to `tax.png`.
