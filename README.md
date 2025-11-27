# OpenCV Camera Capture (Homework 1)

This project demonstrates the configuration and usage of OpenCV with C++ in Visual Studio 2022. The program captures a live video stream from the default webcam and displays it in a window.

## Prerequisites
* **IDE:** Visual Studio 2022 (C++ Desktop Development workflow)
* **Library:** OpenCV 4.x (x64)

## Installation & Setup
1.  **Clone the repository** to your local machine.
2.  Open the solution file (`opencvHM1.sln`) in Visual Studio.
3.  **Configure Paths:**
    * Ensure the project platform is set to **x64**.
    * If your OpenCV installation path differs from `C:\opencv\build`, update the **Include Directories** and **Library Directories** in *Project Properties*.
4.  **Runtime Dependencies:**
    * Ensure the `opencv_world4xxx.dll` file is available in your system PATH or copied into the debug/release output folder next to the executable.

## Usage
1.  Build and Run the project.
2.  A window named "My Camera Feed" will appear showing the webcam stream.
3.  Press **`q`** or **`ESC`** to close the window and exit the program.

## Author
[Your Name]
