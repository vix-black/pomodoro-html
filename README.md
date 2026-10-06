# 🍅 Pomodoro Timer

A simple, single-page Pomodoro-style timer that runs entirely in the browser.

The timer requires no installation, external libraries, account or database. Notes and completed session history are stored locally in the browser using `localStorage`.

## Features

- Four timer options:
  - ☕ Reset: 5 minutes
  - ⚡ Momentum: 10 minutes
  - 🎯 Quick Win: 15 minutes
  - 🚀 Deep Focus: 30 minutes
- Add a note describing what you are timing
- Start, pause and reset controls
- Start and finish sounds
- Live countdown in the browser tab
- Completed-session counter
- Local session history
- Clear-history option
- Responsive dark interface
- Tomato favicon
- Runs from one self-contained HTML file

## Getting started

### Run locally

1. Download or clone this repository.
2. Open `pomodoro.html` in a modern web browser.
3. Enter what you want to work on.
4. Select a timer length.
5. Select **Start**.

No installation or internet connection is required after downloading the file.

## How session history works

Completed sessions are saved in the browser using `localStorage`.

Each completed session records:

- The note entered at the start
- The selected timer duration
- The completion date and time

The application retains up to 50 completed sessions and displays the 20 most recent sessions.

## Data and privacy

All timer data stays in the browser being used.

The application:

- Does not send data to a server
- Does not require an account
- Does not use analytics or tracking
- Does not use external dependencies

Clearing browser storage may remove the saved session history. History recorded in one browser will not automatically appear in another browser or on another device.

## Browser support

The timer uses standard browser features, including:

- Web Audio API
- `localStorage`
- JavaScript intervals

It should work in current versions of Microsoft Edge, Google Chrome, Safari and Firefox.

Some browsers may require interaction with the page before allowing sounds to play.

## Project structure

```text
pomodoro-timer/
├── pomodoro.html
└── README.md
