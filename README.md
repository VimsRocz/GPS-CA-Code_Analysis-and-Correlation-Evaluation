# GPS C/A Code Analysis and Correlation Functions

[![CI](https://github.com/VimsRocz/GPS-CA-Code_Analysis-and-Correlation-Evaluation/actions/workflows/ci.yml/badge.svg)](https://github.com/VimsRocz/GPS-CA-Code_Analysis-and-Correlation-Evaluation/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

### Task 1:
- Generates C/A codes for three GPS satellites (PRN A, PRN B, PRN C) using specified SV numbers.
- Plots the first 20 chips of each generated C/A code.

### Task 2:
- Calculates auto-correlation function of C/A code for PRN A.
- Plots auto-correlation function over a specified range and identifies characteristics.

### Task 3:
- Calculates cross-correlation functions between C/A code of PRN A and codes of PRN B and PRN C.
- Plots cross-correlation functions for different chip shifts (0 and 132 chips) and analyzes results.

### Task 4:
- Creates accumulated code by adding shifted versions of C/A codes for PRN A, PRN B, and PRN C.
- Calculates cross-correlation function of accumulated code with original code of PRN A and plots it.

### Task 5:
- Adds white noise with specified standard deviation to accumulated code generated in Task 4.
- Calculates cross-correlation function of noisy signal with original code of PRN A and plots it.
- Compares outcome with Task 4 to observe impact of noise on correlation functions.

### Task 6:
- Discusses characteristics of correlation functions concerning GPS receiver tracking performance.
- Examines correlation peak recognition under different levels of noise (specified in two cases).

This repository includes MATLAB functions for generating C/A codes, computing auto-correlation and cross-correlation functions, and visualizing results through plots. Tasks aim to analyze correlation properties of GPS C/A codes and their behavior under noise conditions, providing insights into GPS signal processing and receiver tracking performance.

## License

MIT — see `LICENSE`.
