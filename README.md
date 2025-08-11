# UiPath Quicksort Automation

This UiPath project implements the **Quicksort algorithm** to sort an array of integers.  
It demonstrates how recursion and the divide‑and‑conquer approach can be achieved within UiPath Studio.

## Features

- Sorts integer arrays using the **Quicksort** algorithm
- Uses `Main.xaml` to set input values and invoke separate sorting logic
- Contains modular workflow (`SortingArray_Pivot.xaml`) for partition logic and recursion
- Outputs the sorted array directly to UiPath’s Output panel (log messages)

## Project Structure

- **Main.xaml** — Entry point workflow  
  - Initializes the array  
  - Sets `low` and `high` index values  
  - Invokes the sorting workflow  
- **SortingArray_Pivot.xaml** — Contains partition logic and recursive quicksort logic  
- **project.json** — UiPath project configuration and dependencies

## How to Use

1. Clone or download this repository to your local machine.
2. Open the folder in **UiPath Studio**.
3. Open `Main.xaml` as the starting workflow.
4. Run the project to see the array being sorted in the Output panel.

## Requirements

- UiPath Studio (Community or Enterprise)
- Windows OS

---
