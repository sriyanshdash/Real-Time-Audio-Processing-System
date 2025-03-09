# Real-Time Audio Processing System

This project implements a **Real-Time Audio Processing System** using **Verilog** for hardware implementation and **MATLAB** for simulation and visualization. The system includes:
- **Noise Reduction**: Using an FIR filter.
- **Equalization**: Adjustable frequency bands for bass, mid, and treble.

## Contents
1. **Verilog Code**: Hardware implementation of the audio processing system.
2. **MATLAB Code**: Simulation and visualization of the audio processing system.
3. **Documentation**: Instructions for running the project.

---

## Verilog Code

### Files
1. **`audio_processor.v`**: Main module for audio processing.
2. **`audio_processor_tb.v`**: Testbench for simulating the audio processor.

### Simulation Steps
1. Open the project in **Xilinx Vivado**.
2. Add the Verilog files to the project.
3. Run behavioral simulation to verify the functionality.

---

## MATLAB Code

### File
- **`audio_processing.m`**: MATLAB script for simulating and visualizing the audio processing system.

### Steps
1. Open MATLAB and run the script.
2. The script will:
   - Load the `handel.mat` audio file.
   - Add noise to the audio.
   - Apply noise reduction and equalization.
   - Plot the input, noisy, filtered, and equalized signals.
   - Play the processed audio.

---

## How to Use
1. **Verilog**:
   - Simulate the design using Vivado.
   - Verify the functionality using the provided testbench.

2. **MATLAB**:
   - Run the `audio_processing.m` script in MATLAB.
   - Analyze the plots and listen to the processed audio.

---

## Results
- **Input Signal**: Original audio signal.
- **Noisy Signal**: Audio signal with added noise.
- **Filtered Signal**: Audio signal after noise reduction.
- **Equalized Signal**: Audio signal after equalization.

---

## Hosting on GitHub
1. Create a new repository on GitHub.
2. Add the following files to the repository:
   - `audio_processor.v`
   - `audio_processor_tb.v`
   - `audio_processing.m`
   - `README.md`
3. Commit and push the files to GitHub.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
