# 10898377
LSTM prediction and Wave generation
All codes need to paste to MATLAB

# MATLAB Scripts for Ocean Wave Prediction using LSTM (MATLAB R2024b)

This repository includes four MATLAB scripts developed and tested using MATLAB R2024b for ocean wave data generation and prediction. The scripts utilize the JONSWAP wave spectrum to simulate realistic sea wave conditions and employ LSTM neural networks for both single-step and multi-step wave forecasting.

## Script Overview:

### 1. **stokes_wave`**  
- **Purpose:**  
Generates wave elevation data based on the JONSWAP spectrum and Stokes fifth-order theory.  
- **Use:**  
Adjust wave parameters (height, period, duration, sampling frequency) and run the script to output wave time series data saved to Excel.

### 2. **jonswap_wave**  
- **Purpose:**  
Generates realistic irregular wave data directly using the JONSWAP spectrum.  
- **Use:**  
Modify significant wave height, period, and sampling settings. Data is visualized and saved into an Excel file for further analysis.

### 3. **Multi-shot**  
- **Purpose:**  
Performs multi-step wave predictions using an LSTM model trained on previously generated JONSWAP spectrum wave data.  
- **Use:**  
Specify input/output lengths, epochs, and sampling frequency. The model predicts wave elevations for multiple future timesteps, plots the predictions, and saves the results into Excel.

### 4. **`single-shot`**  
- **Purpose:**  
Conducts single-step wave forecasting using the LSTM neural network. Each forecast predicts the next immediate wave elevation.  
- **Use:**  
Adjust the input data length, output duration, and training parameters. Results are visualized graphically and exported to Excel files.

## General Instructions for Use:

- **MATLAB Version:** All scripts are compatible and tested with MATLAB R2024b.
- **Dependencies:** Requires MATLAB Deep Learning Toolbox for LSTM functions.
- **Data Preparation:** Ensure data files (Excel format) are correctly formatted, containing timestamps and wave elevation data columns as specified in scripts.
- **Execution:** Open scripts individually in MATLAB, customize parameters (e.g., wave height, input lengths, epochs), and execute directly from MATLAB environment.

## Applications:

- Wave energy resource assessment  
- Offshore structure design and safety analysis  
- Marine weather forecasting and navigation safety  
- Academic and educational demonstrations in marine engineering
