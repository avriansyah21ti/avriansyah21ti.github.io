# Pengukur Objek Real-time (Real-time Object Measurer)

A web-based application that uses your webcam to detect and measure objects in real-time using OpenCV.js.

## Features

-   **Webcam Integration:** Accesses your device's camera to capture live video.
-   **Real-time Object Detection:** Identifies circular and rectangular objects in the video stream.
-   **Dimension Calculation:**
    -   For circles: Calculates and displays diameter and circumference.
    -   For rectangles: Calculates and displays width and height.
-   **Calibration:** Allows users to calibrate the measurement scale (pixels per centimeter) for accurate results.
-   **User-Friendly Interface:** Simple controls and clear display of measurements, styled with Tailwind CSS.
-   **OpenCV.js Powered:** All image processing is done in the browser using OpenCV.js.

## Technologies Used

-   HTML5
-   CSS3 (Tailwind CSS)
-   JavaScript (ES6+)
-   OpenCV.js

## How to Run / Usage

1.  **Get the code:**
    -   Clone this repository: `git clone <repository-url>`
    -   Or download the `index.html` file.
2.  **Open the application:**
    -   Navigate to the project directory and open the `index.html` file in a modern web browser (e.g., Google Chrome, Mozilla Firefox, Microsoft Edge).
3.  **Allow Camera Access:**
    -   The browser will prompt you for permission to use your webcam. Click "Allow".
4.  **Calibrate:**
    -   Before starting the camera, you'll see a "Kalibrasi (Piksel/cm)" input field.
    -   **Calibration Tip:** Place a physical ruler in front of your webcam. Adjust the "Piksel/cm" value until 1 cm on your physical ruler visually corresponds to the measurements shown by the application (you might need to start the camera briefly to see the measurement overlay, then stop and adjust). A common starting value might be around 30-50, but this depends heavily on your camera and distance to the object.
5.  **Start Measurement:**
    -   Click the "🚀 Mulai Kamera" (Start Camera) button.
6.  **Measure Objects:**
    -   Point your camera towards circular or rectangular objects. The application will draw outlines and display their dimensions in centimeters.
    -   To stop, click the "⏹️ Hentikan Kamera" (Stop Camera) button.

## Screenshot / Demo

*(Consider adding a screenshot or a GIF of the application in action here.)*

## Potential Future Enhancements

-   Save calibration settings locally in the browser (e.g., using `localStorage`).
-   Support for more complex shapes.
-   Improved detection accuracy and robustness under various lighting conditions.
-   Option to select different units of measurement (e.g., inches).
-   Ability to pause the video feed for easier measurement of a static scene.

## License

This project is open-source. Consider adding a specific license file (e.g., MIT License) if you plan to share it widely.
