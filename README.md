# Type Racer — Typing Speed Test

## Overview

Type Racer is a web-based typing speed test application designed to help users measure and improve their typing performance. The application provides real-time feedback on typing speed, accuracy, and errors within a clean and interactive interface. It is lightweight and runs entirely in the browser without requiring any external dependencies.

## Features

* Real-time calculation of Words Per Minute (WPM)
* Accuracy tracking based on keystrokes
* Error and correct character tracking
* Multiple test durations (15s, 30s, 60s)
* Dynamic word generation for each test
* Visual feedback for correct and incorrect inputs
* Timer with circular progress indicator
* Result summary displayed at the end of the test
* Reset and retry functionality

## Technologies Used

* HTML5 for structure
* CSS3 for styling and layout
* JavaScript (Vanilla) for logic and interactivity

## How It Works

1. The application generates a randomized list of words from a predefined dataset.
2. When the user starts typing, the timer begins automatically.
3. Each keystroke is compared with the expected character:

   * Correct inputs are counted and highlighted.
   * Incorrect inputs are recorded as errors.
4. Performance metrics such as WPM and accuracy are calculated in real time.
5. Once the timer ends, the test stops and a results summary is displayed.

## Key Calculations

* **Words Per Minute (WPM):**
  Calculated using the formula:
  WPM = (Correct Characters / 5) / Time (in minutes)

* **Accuracy:**
  Accuracy = (Correct Keystrokes / Total Keystrokes) × 100

## Project Structure

* `index.html` — Main application file containing structure, styles, and scripts
* Embedded CSS — Handles UI design and layout
* Embedded JavaScript — Manages logic, timer, and calculations

## How to Run

1. Download or clone the project files.
2. Open the `index.html` file in any modern web browser.
3. Click on the input box and start typing to begin the test.

## Future Improvements

* Add difficulty levels with longer or more complex words
* Store user performance history
* Add multiplayer or competitive typing mode
* Improve mobile responsiveness
* Integrate backend for user accounts and data tracking

## Conclusion

Type Racer is a simple yet effective application that demonstrates core front-end development concepts such as DOM manipulation, event handling, and real-time data updates. It serves as a practical tool for improving typing skills while showcasing interactive web design.
