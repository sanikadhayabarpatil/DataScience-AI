# High Parallel AI: Parallel Data Preprocessing

## Project Overview
This project explores **high-performance parallel data preprocessing** for image datasets using **Dask** and **PyTorch**. The goal is to leverage parallel computing techniques to efficiently load, transform, and normalize large-scale image datasets while optimizing memory usage.

## Key Features
- **Parallel Data Loading**: Uses Dask and PyTorch’s `DataLoader` for efficient batch processing.
- **Scalability**: Implements a distributed computing framework with Dask’s `Client`.
- **Image Transformation Pipeline**: Applies resizing, normalization, and augmentation.
- **Performance Optimization**: Balances memory utilization and computational efficiency.

## Installation
Ensure you have the required dependencies installed before running the notebook:

```bash
pip install torch torchvision dask matplotlib pillow
```

## How to Run
1. Clone this repository and navigate to the project folder:
    ```bash
    git clone <repository_url>
    cd <project_folder>
    ```
2. Start a Dask distributed client:
    ```bash
    dask-scheduler &
    dask-worker localhost:8786 &
    ```
3. Open the Jupyter Notebook and run the cells sequentially:
    ```bash
    jupyter notebook High_Parallel_AI.ipynb
    ```

## Implementation Details
- **Dask-Based Preprocessing**: Uses `Dask.array` for batch image transformation.
- **PyTorch DataLoader**: Utilizes multi-threaded loading for fast dataset handling.
- **ResNet Pretrained Model**: Leverages `resnet18` for feature extraction.

## Results
The project demonstrates a **high-speed, parallelized data preprocessing pipeline** capable of handling large-scale datasets efficiently while maintaining memory constraints.

## Author
- **Sanika Dhayabar Patil**

