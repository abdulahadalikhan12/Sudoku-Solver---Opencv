# Sudoku Solver 🧩

This project reads a Sudoku puzzle from an image, detects digits using a CNN model, and solves the puzzle using a backtracking algorithm. It then overlays the solution back onto the original image.

## Features

- Load and process Sudoku puzzle from an image
- Detect digits using a trained CNN model (OCR)
- Solve the puzzle using a recursive backtracking algorithm
- Overlay the solution on the original image
- Built with OpenCV, NumPy, and TensorFlow

## How to Run

1. Clone the repository.
2. Place a Sudoku puzzle image in the `Resources/` folder (e.g., `1.jpg`).
3. Run the main script:

```bash
python main.py
