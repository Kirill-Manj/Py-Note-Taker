# Py-Note-Taker

A Python note-taking app that uses hand tracking instead of a mouse. It's basically digital sticky notes, except I made it way harder than it needed to be.

## What is it?

Py-Note-Taker lets you create sticky notes and draw on a virtual canvas using hand gestures and your webcam. The idea was to make something a little more fun than a normal notes app while also learning how computer vision works.

It's definitely not perfect, but it works well enough that I'm pretty happy with it.

## Features

- Create digital sticky notes
- Draw freely on the canvas
- Hand gesture controls
- Real-time hand tracking with your webcam
- Simple interface
- No mouse required (unless something breaks)

## Built With

- Python
- OpenCV
- MediaPipe
- NumPy

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Py-Note-Taker.git
cd Py-Note-Taker
```

Install the required packages:

```bash
pip install opencv-python mediapipe numpy
```

Run the program:

```bash
python main.py
```

## Why I made this

I wanted to learn more about computer vision and thought making a notes app controlled by hand gestures would be more interesting than another calculator or to-do list.

It also gave me an excuse to mess around with OpenCV and MediaPipe, which was both fun and occasionally really annoying.

## What I learned

- How hand tracking works with MediaPipe
- Real-time image processing with OpenCV
- Gesture detection
- That debugging webcam code takes way longer than expected

## Future ideas

- Better gesture recognition
- Different pen colors and brush sizes
- Saving notes automatically
- Undo/redo
- Making the code look less like I wrote it at 2 AM

## Known Issues

- Hand tracking can be a little inconsistent depending on lighting.
- Occasionally gestures don't register on the first try.
- The code could definitely be cleaner.

## License

This project is open source under the MIT License.

