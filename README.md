# SimpleEQ

A 3-band parametric equalizer and real-time spectrum analyzer plugin built with C++ and the JUCE framework.

![Plugin Screenshot]('https://github.com/user-attachments/assets/4f43a15b-ebbb-4520-897f-6330257772e9')
*(Note: Replace this line with a screenshot of your plugin UI, or remove it)*

## Overview
SimpleEQ is a VST3 audio plugin capable of shaping audio with high-precision filtering while providing visual feedback. It features a modern, vector-based GUI and a thread-safe architecture that separates real-time audio processing from graphical rendering.

## Key Features
* **3-Band Equalization:**
    * **Low Cut & High Cut:** Variable frequency with adjustable slope settings (12dB/oct, 24dB/oct, 36dB/oct, 48dB/oct).
    * **Parametric Peak Band:** Controls for Frequency, Gain, and Quality (Q).
* **Real-Time Visualization:**
    * Fast Fourier Transform (FFT) based spectrum analyzer.
    * Dynamic response curve that updates as parameters change.
* **Modern GUI:** Custom `LookAndFeel` implementation for vector-based rotary sliders and responsive layout.

## Technologies Used
* **Language:** C++ (C++17 standard)
* **Framework:** JUCE (v7+)
* **DSP:** `juce::dsp` module (IIR Filters, Windowing, FFT)
* **IDE:** Visual Studio 2022

## How to Build
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/SimpleEQ.git](https://github.com/YourUsername/SimpleEQ.git)
    ```
2.  **Open the Project:**
    * Open `SimpleEQ.jucer` in the **Projucer** application.
3.  **Configure Exporters:**
    * Ensure your IDE (e.g., Visual Studio 2022 or Xcode) is selected in the "Exporters" tab.
    * Click the "Save and Open in IDE" icon.
4.  **Compile:**
    * Build the solution in **Release** or **Debug** mode.
    * The artifact (VST3) will be located in `Builds/VisualStudio2022/x64/Debug/VST3/` (path varies by OS).

## Acknowledgements
This project was built following the tutorial by **Matkat Music** and **The Audio Programmer** via freeCodeCamp.
src="https://github.com/user-attachments/assets/4f43a15b-ebbb-4520-897f-6330257772e9" />
