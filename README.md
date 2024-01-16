
# Essential Matrix Estimation and Non-linear Optimization

## Overview
This project is focused on understanding and applying concepts of Essential Matrix Estimation and Non-linear Optimization in the context of image processing and computer vision.

## Task 1: Essential Matrix Estimation

### Objective
- Estimate the essential matrix for a calibrated camera pair.
- Resolve the ambiguity in the essential matrix.
- Compute and visualize epipolar lines.

### Steps
1. **Calibration Matrix Computation**
   - Use data from Assignment 5, which includes image coordinates and object points.
   - Compute calibration matrices K1 and K2 using a method from the lecture.

2. **Essential Matrix Estimation**
   - Estimate the essential matrix based on the computed calibration matrices.

3. **Ambiguity Resolution**
   - Resolve the fourfold ambiguity of the essential matrix.
   - Select the geometrically plausible solution.

4. **Epipolar Lines Visualization**
   - Compute and plot the epipolar lines derived from the essential matrix.

## Task 2: Non-linear Optimization

### Objective
- Optimize the solution with respect to geometric error.
- Perform non-linear optimization using an indirect optimization method.
- Re-calculate and analyze the geometric error.

### Steps
1. **Geometric Error Computation**
   - Calculate the geometric error based on the solution from Task 1.

2. **Non-linear Optimization**
   - Perform optimization using a method like Levenberg-Marquardt.
   - Optional: Perform indirect parameterization.

3. **Error Analysis**
   - Re-calculate the geometric error after optimization.
   - Report and comment on the results.

## Requirements
List any libraries or dependencies required for this project.

## Installation
Provide instructions on how to set up the project.

## Usage
Describe how to run the tasks and any relevant scripts.

## Contributing
Guidelines for contributing to this project.

## License
Specify the license under which this project is released.
