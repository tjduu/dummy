# Lorenz-63 Neural Forecasting

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DZke7qzqYzRJCKwkCp79ziTDwNuirFWu?usp=sharing)

OCES 5303 Assignment 2 investigates whether neural forecasts can reproduce both Lorenz-63 trajectories and the butterfly effect. Parameter-matched CNN and Fourier Neural Operator (FNO) models receive the same initial condition and predict 300 future timesteps.

## Main file

- `ass2_oces5303_20601408.ipynb` — complete PyTorch experiment and discussion

## Run in Google Colab

1. Click **Open in Colab** above.
2. Select **Runtime → Change runtime type → T4 GPU** when available.
3. Confirm that `QUICK_RUN = False` for the reported experiment.
4. Select **Runtime → Run all**.

The notebook automatically uses CUDA when a GPU is available and otherwise falls back to MPS or CPU. A free Colab GPU is recommended for the complete training run.
