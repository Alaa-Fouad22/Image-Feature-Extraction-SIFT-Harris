# 👁️ Computer Vision: Feature Extraction & Matching (C++ / Qt)

## 📌 Project Overview
A C++/Qt Computer Vision application for feature extraction (Harris, SIFT) and matching (SSD, NCC) with real-time performance benchmarking. This desktop application evaluates the performance and computation time of fundamental feature detection algorithms, providing a graphical interface for visual analysis and robotics-related tracking tasks.

## ⚙️ Core Capabilities
* **Feature Detection (Harris Operator):** Identifies unique keypoints using the Harris Corner Detector and $\lambda$ eigenvalue analysis.
* **Feature Description (SIFT):** Generates robust, scale-invariant, and rotation-invariant feature descriptors.
* **Feature Matching Metrics:** Matches features between images using:
  * Sum of Squared Differences (SSD)
  * Normalized Cross-Correlation (NCC)
* **Performance Benchmarking:** Real-time reporting of computation times for each algorithmic stage.

## 🖼️ Example Input
Images like this electronic circuit board are used to test feature detection and matching performance under varying conditions.

![Sample Input Circuit Board](assets/sample_input_circuit.jpg)

## 📸 Application Output
The graphical user interface displaying the extracted features and matching results.

![Qt GUI Application Output](assets/application_output_features.jpg)

## 🛠️ Tech Stack & Architecture
* **Language:** C++ (Object-Oriented Design)
* **GUI Framework:** Qt (Widgets / UI Designer)
* **Build System:** CMake
* **Architecture:** Modular separation of concerns (Core algorithms separated from GUI logic).

## 🚀 Build & Run Instructions

### Prerequisites
* CMake (Version 3.5 or higher)
* Qt Creator / Qt5 or Qt6 libraries
* C++ Compiler (GCC, Clang, or MSVC)

### Steps
1. Clone the repository:
   ```bash
   git clone [https://github.com/YourUsername/YourRepoName.git](https://github.com/YourUsername/YourRepoName.git)