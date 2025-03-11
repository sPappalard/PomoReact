# Pomodoro Timer App

A minimalist Pomodoro Timer application built with React to help you boost productivity and maintain focus using the time management technique.
##
  <img src="https://github.com/sPappalard/PomodoroTimerApp/blob/main/img1.gif" alt="GIF">

##

<img src= "https://github.com/sPappalard/PomodoroTimerApp/blob/main/Senza-titolo(1).gif" alt="GIF">



## What is the Pomodoro Technique?

The Pomodoro Technique is a time management method developed by Francesco Cirillo in the late 1980s. It uses a timer to break work into intervals, traditionally 25 minutes in length, separated by short breaks. These intervals are known as "pomodoros", the plural in English of the Italian word pomodoro (tomato), after the tomato-shaped kitchen timer that Cirillo used as a university student.

## Features

- **Customizable Timer Settings**: Set your preferred work and break durations (from 1 to 120 minutes)
- **Visual Progress Indicator**: Circular progress bar shows remaining time at a glance
- **Color-Coded Modes**: Red for work sessions, green for break sessions
- **Simple Controls**: Intuitive play/pause functionality
- **Auto Mode Switch**: Automatically transitions between work and break periods
- **Clean Interface**: Minimalist design with a subtle background

## How It Works

1. **Work Session**: By default, the timer starts with a 45-minute work session (customizable)
2. **Break Time**: After completing a work session, the timer automatically switches to a 15-minute break (customizable)
3. **Repeat**: After the break, the timer switches back to work mode, and the cycle continues



## Components

- **App**: Main component that manages settings state and context
- **Timer**: Displays the timer with progress bar and controls
- **Settings**: Allows users to customize work and break durations
- **Control Buttons**: Play, Pause, Settings, and Back buttons for user interaction
- **Context**: Provides settings data across components

## Technologies Used

- React.js
- React Hooks (useState, useEffect, useContext, useRef)
- react-circular-progressbar
- react-slider
- CSS for styling

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/your-username/pomodoro-timer-app.git
cd pomodoro-timer-app
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open your browser and navigate to `http://localhost:3000`

## Customization

You can easily customize the app by:
- Modifying the CSS variables in `App.css` to change colors
- Adjusting the default work/break times in `App.js`
- Replacing the background image path in `App.css`

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License --->  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


