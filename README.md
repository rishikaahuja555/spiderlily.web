# BloomSense

### Interactive 3D Garden Using Real-Time Hand Tracking

BloomSense is an interactive 3D garden that uses real-time hand tracking to let users interact with flowers through simple hand gestures.

The project uses a webcam to detect hand movements and translates specific gestures into visual changes within a Three.js environment.

## Features

* Real-time hand tracking using MediaPipe Hands
* Interactive 3D flower environment
* Three gesture-based interactions
* Multiple flower options
* Real-time interaction mode displayed on screen
* Webcam-based interaction
* 3D rendering using Three.js
* Browser-based application

## Gesture Interaction

BloomSense currently supports three primary hand gestures:

| Gesture     | Interaction              |
| ----------- | ------------------------ |
| Open hand   | Bloom                    |
| Closed hand | Close                    |
| Pinch       | Interact with the flower |

The current interaction mode is displayed on the screen while the user interacts with the garden.

## Flower Collection

The garden supports multiple flower types:

* Rose
* Sunflower
* Orchid

Users can switch between the available flowers and interact with them using the supported hand gestures.

## How It Works

BloomSense uses the webcam to capture the user's hand movements. MediaPipe Hands detects hand landmarks, and JavaScript interprets the detected gestures.

The gesture state is then used to control the visual state of the selected flower within the Three.js environment.

```text
Webcam
   |
   v
MediaPipe Hands
   |
   v
Hand Landmark Detection
   |
   v
Gesture Recognition
   |
   v
JavaScript
   |
   v
Three.js
   |
   v
Interactive Flower
```

## Technology Stack

| Technology      | Purpose                       |
| --------------- | ----------------------------- |
| HTML5           | Application structure         |
| CSS3            | Interface and styling         |
| JavaScript      | Gesture logic and interaction |
| Three.js        | 3D rendering                  |
| MediaPipe Hands | Real-time hand tracking       |
| Web Camera      | Hand input                    |
| GitHub          | Version control               |

## Getting Started

### Prerequisites

* A modern web browser
* Webcam
* Python 3.x

### Run Locally

## Run Locally

Clone the repository:

```bash
git clone https://github.com/rishikaahuja555/BloomSense.git
```

Navigate to the project:

```bash
cd BloomSense
```

Start a local server:

```bash
python -m http.server 8642
```

Open the application in your browser:

```text
http://localhost:8642
```

Allow camera access when prompted.

The application should be served through `localhost` or HTTPS because webcam access requires a secure browser context.


## Project Structure

```text
BloomSense/
│
├── spiderlily-web/
│   └── index.html
│
└── README.md
```

## Interaction Flow

```text
Select Flower
     |
     v
Start Camera
     |
     v
Detect Hand
     |
     v
Recognize Gesture
     |
     v
Update Interaction Mode
     |
     v
Change Flower State
```

## Purpose

BloomSense explores the use of computer vision and 3D graphics to create a simple, natural form of interaction between a user and a virtual environment.

Instead of relying only on traditional mouse and keyboard controls, the project allows users to interact with a digital flower using their hands.

## Author

**Rishika Ahuja**

B.Tech Computer Science and Engineering
