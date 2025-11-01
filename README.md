🎵 React Audio Visualizer
🧭 Overview

A dynamic, browser-based music visualizer built with React and Butterchurn, the visualization engine behind Winamp.
This project renders real-time visual effects that respond to any audio source — whether it’s songs loaded directly into the app, your computer’s system audio (via BlackHole), or live microphone input.

The goal was to merge audio analysis, creative visualization, and interactive UI design into one smooth, high-performance web app.

✨ Key Features

🎧 Multiple Audio Inputs:
Choose between local audio files, microphone input, or system-level audio via BlackHole
.

🎨 Real-Time Visuals:
Generates smooth, responsive visualizations using Butterchurn’s OpenGL shaders.

🎲 Random Preset Mode:
Automatically cycles through visual presets every 25 seconds, avoiding blacklisted or repetitive ones.

🔀 Shuffle Playlist:
Plays songs in random order without repeats until all tracks have been played.

📋 Preset Copy:
Copy the name of the current visualization preset for later reuse.

🖥️ Fullscreen Mode:
Immersive display mode for visual experiences or music setups.

🚀 Outcomes

Created a fully functional visualizer app that integrates live system audio and file playback.

Demonstrated skills in React state management, Web Audio API, and real-time rendering pipelines.

Designed a modular system where visualization, playback, and audio routing are all independently configurable.

🛠️ Tools / Technologies

Frontend: React, JavaScript, HTML5, CSS

Audio Processing: Web Audio API, Butterchurn, Butterchurn Presets

System Audio Routing: BlackHole (macOS virtual audio device)

Version Control: Git & GitHub

🧠 What I Learned

How to route system audio into web applications using virtual audio interfaces.

Managing asynchronous state in React with refs to avoid stale audio node connections.

Efficiently connecting audio contexts and visual analyzers without causing context mismatches.

Applying modular architecture to handle different audio input types seamlessly.

💻 How to Run

Clone this repository:

git clone https://github.com/yourusername/react-audio-visualizer.git
cd react-audio-visualizer


Install dependencies:

npm install


Run the app:

npm start


(Optional – macOS users)

Install BlackHole
 to route system audio.

Open Audio MIDI Setup → Create Multi-Output Device with both your output and BlackHole.

Select “Multi-Output Device” as your system output, and “BlackHole” as the input in the app.

🖼️ Examples / Screenshots
Mode	Description

	<img width="1710" height="1068" alt="image" src="https://github.com/user-attachments/assets/c8dbec2f-cc46-4a68-8735-541dcadc493d" />
Fullscreen visualization of a playing track

	<img width="962" height="522" alt="image" src="https://github.com/user-attachments/assets/4e73a5ac-1337-4c66-bc92-0dbfce448191" />
Audio input selector and preset controls
