# Telescope Control Program

## Overview

This Python program is designed to interface with Stellarium and control a telescope's azimuth and altitude using a serial connection. The program extracts azimuth and altitude information from Stellarium, sends the data to an Arduino through a serial port, and provides options for user configuration.

## Features

- Retrieve azimuth and altitude information from Stellarium API.
- Communicate with an Arduino to control a telescope's movement.
- User-configurable settings for serial communication and Stellarium API URL.

## Prerequisites

- Python 3.x
- Stellarium installed and running with the Remote Control plugin enabled.
- Arduino connected to the computer via a serial port.

## Installation

1. Clone or download the repository to your local machine.
2. Install required Python packages using the following command:

    ```bash
    pip install requests
    ```

## Usage

1. Run the program:

    ```bash
    python telescope_control.py
    ```

2. Choose options from the main menu:

    - **Get Selected Object Info**: Retrieve azimuth and altitude information from Stellarium.
    - **Settings**: Configure communication port and update Stellarium URL.
    - **Test Output**: Simulate telescope data output for testing purposes.
    - **Exit**: Terminate the program.

## Configuration

1. **Establish Communication Port**:

    - Follow the on-screen instructions to select the desired COM port for communication with the Arduino.

2. **Update Stellarium URL**:

    - Access the "Settings" menu and choose the option to update the Stellarium URL. Enter the new URL as prompted.

## Notes

- Make sure Stellarium is running with the Remote Control plugin enabled and configured to listen on the specified API port.

- Adjust the baud rate and other serial communication settings based on your Arduino configuration.

## Contributors

- Inlagd Sill

