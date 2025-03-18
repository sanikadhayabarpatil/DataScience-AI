# Deque Implementation

## Project Overview
This project implements a **deque (double-ended queue)** using a **blocked list approach** to ensure efficient operations. The implementation guarantees **O(1)** time complexity for core operations, making it a memory-efficient and scalable solution.

## Key Features
- **Blocked List Approach**: The deque is divided into fixed-size blocks (e.g., 64 elements per block) to avoid frequent resizing.
- **Strict O(1) Operations**:
  - `append`
  - `appendleft`
  - `pop`
  - `popleft`
  - `deque[i]`
  - `len()`
- **Efficient Memory Usage**: New blocks are allocated only when required, optimizing space utilization.

## Installation
Ensure you have the required dependencies installed before running the notebook:

```bash
pip install num2words
```

## How to Run
1. Clone this repository and navigate to the project folder:
    ```bash
    git clone <repository_url>
    cd <project_folder>
    ```
2. Open the Jupyter Notebook and run the cells sequentially:
    ```bash
    jupyter notebook DequeMidtermSanika.ipynb
    ```

## File Structure
- `DequeMidtermSanika.ipynb` – Main implementation of the deque with performance evaluation.
- `Blocked List Deque` – Core logic for efficient deque operations.

## Author
- **Sanika Dhayabar Patil**

