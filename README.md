# 🍂 Autumn Countdown

A beautiful interactive autumn-themed countdown website with falling leaves, background music, live weather, location information, public IP display, sunshine status, and a real-time clock.

## ✨ Features

* 🍁 Countdown to Autumn
* 🕒 Live local clock
* 🌤️ Live weather information
* 🌡️ Current temperature
* ☀️ Daylight and nighttime status
* 📍 Approximate location detection
* 🌐 Public IP address display
* 🎵 Background music using `music.mp3`
* 🍂 Animated falling autumn leaves
* 📱 Responsive design for desktop and mobile
* ✨ Animated loading screen
* 🎨 Glassmorphism-style autumn interface

## 📁 Project Structure

```text
autumn-countdown/
│
├── index.html
├── music.mp3
└── README.md
```

## 🚀 Getting Started

1. Download or clone this repository.
2. Make sure `music.mp3` is in the same folder as `index.html`.
3. Open the project using a local development server or web hosting service.
4. Allow location access if your browser asks for permission.

## 🎵 Background Music

The project loads background music from:

```text
music.mp3
```

You can replace this file with your own MP3. Keep the same filename, or update the following line in `index.html`:

```html
<source src="music.mp3" type="audio/mpeg">
```

## 🌤️ Weather

Weather information is provided using the Open-Meteo API.

The application displays:

* Current weather condition
* Weather icon
* Current temperature
* Daylight or nighttime status

## 📍 Location and IP Address

The project uses IP-based location information to display:

* City
* Country
* Public IP address

Because this uses an external service, location information is approximate and may not always match your exact physical location.

## ⚠️ Important

For the weather, location, and IP features to work correctly, it is recommended to run the project through a local web server or deploy it online.

Opening the project directly with:

```text
file:///
```

may cause browser security restrictions or prevent some API requests from working.

## 🛠️ Running Locally

If you have Python installed, open a terminal inside the project folder and run:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

in your browser.

## 📱 Responsive Design

The website automatically adjusts for different screen sizes.

* Desktop displays countdown and information cards in wider layouts.
* Tablets and smaller screens use fewer columns.
* Mobile devices display a compact responsive interface.

## 🍂 Countdown Date

The current project counts down to:

**September 23, 2026**

You can change the target date inside `index.html`:

```javascript
const targetDate = new Date(
    "September 23, 2026 00:00:00"
).getTime();
```

## 📸 Preview

The website includes:

* A loading screen
* Autumn countdown timer
* Falling leaf animations
* Live time
* Weather and temperature
* Sunshine status
* Location
* Public IP information
* Background music controls

## 📄 License

Feel free to use, modify, and customize this project for personal or educational purposes.
