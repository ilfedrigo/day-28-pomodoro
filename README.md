# ilfedrigo Pomodoro App

In day 28 of 100 days of code with Python, I've made a simple Pomodoro timer using the Tkinter library. 

The Pomodoro Technique is a time management method that uses a timer to break down work into intervals, traditionally 25 minutes in length, separated by short breaks.

## Features
- Countdown timer for work sessions
- Breaks between work sessions
- Visual indication of work and break sessions
- Reset button to start a new Pomodoro session
- Checkmarks to track completed work sessions

## Dependencies
- Python 3
- Tkinter library

## Usage
1. Ensure you have Python installed on your machine.
2. Run the script in a Python environment.
3. Click the "Start" button to begin a Pomodoro session.
4. Use the "Reset" button to reset the timer and start a new session.

## Configuration
You can customize the Pomodoro session durations by modifying the following constants in the code:
- `WORK_MIN`: Duration of work sessions in minutes
- `SHORT_BREAK_MIN`: Duration of short breaks in minutes
- `LONG_BREAK_MIN`: Duration of long breaks in minutes

## Interface
- The timer is displayed in the center with a tomato image representing the Pomodoro.
- The title label indicates whether it's a work or break session.
- Checkmarks below the timer track completed work sessions.
