# Interactive Stopwatch with Physical Response Tracking ⏱️💙

This is a simple and stylish interactive stopwatch web application that allows users to time events and record physical response timings. It features a countdown before starting, clear controls, and the ability to export the recorded data.

## Features ✨

* **Clear Display:** Shows the elapsed time in hours, minutes, seconds, and milliseconds with a bold, easy-to-read format.
* **Start/Stop Functionality:** Starts the timer with a 5-second countdown and allows pausing.
* **Reset Function:** Resets the timer to the initial state (00:00:05.00) and clears any recorded physical responses.
* **Physical Response Tracking:** Records timestamps of physical responses (start and stop) when the "Space" key is pressed while the timer is running. It also displays the duration between consecutive responses and the local time of the event.
* **Data Export:** Allows users to export the session data, including start time, stop time, total duration, and recorded physical response timings, to a plain text file.
* **Keyboard Shortcuts:**
    * Press **"Enter"** to start or stop the timer.
    * Press **"Space"** to record a physical response timing.
* **Stylish User Interface:** Features a visually appealing design with a gradient background, blurred glass container, and subtle hover effects on buttons.

## How to Use 🚀

1.  Save the provided HTML code as an `.html` file (e.g., `stopwatch.html`).
2.  Open the `.html` file in any modern web browser.
3.  Click the **"Start"** button to begin the countdown and then the stopwatch.
4.  Click the **"Stop"** button to pause the timer.
5.  Click the **"Reset"** button to reset the timer and clear recorded responses.
6.  While the timer is running, press the **"Space"** key to record the start and stop times of a physical response. These timings will appear below the stopwatch.
7.  Click the **"Export Data"** button to download a `.txt` file containing the session information and recorded physical response timings.

## Code Highlights 💡

* **HTML Structure:** Uses a simple structure with a container for the stopwatch elements, a display for the time, buttons for controls, and a section to list recorded physical response timings.
* **CSS Styling:** Provides a clean and modern look with a gradient background, blurred semi-transparent container, and styled buttons for clear interaction.
* **JavaScript Functionality:**
    * `startCountdown()`: Initiates a 5-second countdown before starting the main timer.
    * `updateTime()`: Updates the displayed time every 10 milliseconds.
    * `pauseTimer()`: Stops the timer and records the stop time.
    * `resetTimer()`: Resets all timer variables and clears the displayed time and recorded responses.
    * `recordSplit()`: Records the current time and the time elapsed since the last recorded response, labeling them as "Physical Response Start" and "Physical Response Stop" alternately. It also includes the local time of the recording.
    * `exportData()`: Prompts the user for a filename and then generates and downloads a text file containing the session's start and stop times, total duration, and the list of recorded physical response timings.
* **Keyboard Event Listeners:** Adds event listeners to the "Enter" and "Space" keys for quick control of the stopwatch and recording of physical responses.

## Potential Enhancements 💪

* **Lap Timing:** Add a feature to record lap times without stopping the main timer.
* **More Detailed Export:** Include more granular data in the export, such as individual split durations.
* **Visualizations:** Explore options to visualize the recorded response times.
* **Customizable Countdown:** Allow users to set a custom countdown duration.
* **Improved Styling:** Further refine the user interface and responsiveness.

Enjoy using the Interactive Stopwatch! 💙
