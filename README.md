# Flow · Pomodoro Timer

Aesthetic and customizable **Pomodoro Timer** built with HTML, CSS, and JavaScript.

Flow is designed to provide a simple, distraction-free productivity experience with customizable timer presets, tasks, themes, fonts, sounds, and productivity statistics.

## ✨ Features

* ⏱️ Pomodoro timer with multiple presets
* ▶️ Start, pause, and reset controls
* 📚 Study Focus timer
* 💼 Work Session timer
* ☕ Short Break timer
* 🌿 Long Break timer
* 💧 Hydration reminder timer
* 🔊 Custom start, end, and reminder sounds
* 📝 Built-in To-Do List
* 📊 Productivity statistics
* 📈 Weekly progress tracking
* 🎨 Light, Dark, and Solar themes
* 🔤 Multiple font options
* 🌈 Custom accent colors
* 💾 Local storage for saving settings and progress
* ⌨️ Keyboard shortcuts
* 📱 Responsive design for desktop and mobile
* 😀 Native/platform emoji support with Apple Color Emoji preferred on Apple devices

## ⏱️ Timer Presets

The application includes five built-in presets:

| Preset          | Default Duration |
| --------------- | ---------------: |
| 📚 Study Focus  |       25 minutes |
| 💼 Work Session |       45 minutes |
| ☕ Short Break   |        5 minutes |
| 🌿 Long Break   |       15 minutes |
| 💧 Hydration    |       30 minutes |

All preset durations can be customized from the **Customize** panel.

## 🔊 Custom Sounds

Flow uses three custom MP3 files:

```text
start.mp3
end.mp3
reminder.mp3
```

### Sound behavior

* `start.mp3` plays when the timer starts.
* `end.mp3` plays when the timer reaches `00:00`.
* `reminder.mp3` plays for the hydration reminder.

### Important

The MP3 files must remain in the **same folder** as the HTML file.

The project should look like:

```text
flow-pomodoro/
├── flow-pomodoro-final.html
├── start.mp3
├── end.mp3
└── reminder.mp3
```

If the HTML file cannot find these files, the custom sounds will not play.

## 🎨 Customization

The Customize panel provides several options.

### Themes

* Light
* Dark
* Solar

The timer text and interface colors automatically adapt to the selected theme.

### Fonts

Available font choices:

* Poppins
* Montserrat
* Inter
* Serif

The selected font is applied throughout the timer interface.

### Accent Colors

The application includes multiple accent-color choices that affect the timer progress circle, buttons, and other highlighted elements.

## 📝 To-Do List

The built-in To-Do List allows you to:

* Add tasks
* Mark tasks as completed
* Edit tasks
* Delete tasks
* Track completed tasks in statistics

Completed tasks contribute to the weekly productivity progress.

## 📊 Statistics

The Statistics panel tracks:

* Completed sessions
* Completed tasks
* Weekly productivity

Weekly progress is displayed using a simple visual chart.

## 💾 Local Storage

Flow automatically saves application data using the browser's `localStorage`.

This includes:

* Timer settings
* Preset durations
* Theme
* Font
* Accent color
* Sound preference
* To-Do List
* Statistics
* Weekly progress

Your data is stored locally in your browser.

## ⌨️ Keyboard Shortcuts

| Key     | Action              |
| ------- | ------------------- |
| `Space` | Start / Pause timer |
| `R`     | Reset timer         |
| `T`     | Open To-Do List     |
| `S`     | Open Statistics     |

Keyboard shortcuts are disabled while typing in text inputs.

## 📱 Responsive Design

The interface is designed to work across:

* Desktop
* Laptop
* Tablet
* Mobile devices

The layout automatically adapts to smaller screens.

## 🛠️ Technologies

This project is built using:

* HTML5
* CSS3
* Vanilla JavaScript
* SVG
* Web Storage API
* HTML5 Audio API
* Web Audio API

No external JavaScript framework is required.

## 🚀 How to Run

### Option 1 — Open directly

Keep all project files in the same folder:

```text
flow-pomodoro/
├── flow-pomodoro-final.html
├── start.mp3
├── end.mp3
└── reminder.mp3
```

Then double-click:

```text
flow-pomodoro-final.html
```

It will open in your browser.

### Option 2 — Use a local server

For development, you can run the project through a local server.

For example, with VS Code, install **Live Server** and open the HTML file using:

```text
Open with Live Server
```

Using a local server can provide more consistent browser behavior for local assets such as audio files.

## 🌐 Browser Compatibility

Flow is intended for modern browsers that support:

* ES6 JavaScript
* CSS Variables
* CSS Grid/Flexbox
* SVG
* Local Storage
* HTML5 Audio

Recommended browsers include:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

## 🍎 Emoji System

The interface prefers the following emoji font order:

```text
Apple Color Emoji
Segoe UI Emoji
Noto Color Emoji
```

Therefore, Apple devices can use Apple's native emoji appearance while other platforms use their own available emoji system.

## 🔒 Privacy

Flow does not require an account or external database.

Application data is stored locally in the browser using `localStorage`.

The project does not require a backend server.

## 📁 Project Structure

```text
flow-pomodoro/
│
├── flow-pomodoro-final.html   # Main application
├── start.mp3                  # Timer start sound
├── end.mp3                    # Timer completion sound
├── reminder.mp3               # Hydration reminder sound
└── README.md                  # Project documentation
```

## ⚠️ Notes

* Do not rename the MP3 files unless you also update their filenames inside the HTML.
* Keep the three MP3 files beside the HTML file.
* Clearing browser storage will remove locally saved settings, tasks, and statistics.
* Browser audio policies may require the user to interact with the page before audio can play.

## 📄 License

This project is provided for personal and educational use.

You may modify the HTML, CSS, and JavaScript to suit your own requirements.
