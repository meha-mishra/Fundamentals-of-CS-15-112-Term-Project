# Fundamentals-of-CS-15-112-Term-Project
🌌 Night Sky Explorer (CMU Graphics)

An interactive constellation exploration and game application built using CMU Graphics. This project combines educational exploration with a timed challenge mode, all within a dynamic, slide-based night sky interface.

🚀 Features

🌠 Learn Mode
Navigate between regions of the night sky using directional controls
Hover over constellations to preview their shapes
Click constellations to view detailed descriptions and visuals
Designed for intuitive, self-guided exploration

🎮 Game Mode
Timed challenge to find specific constellations
Three difficulty levels:
Easy: More time, no penalties
Intermediate: Reduced time, limited lives
Hard: Short time, limited lives, restricted “telescope” vision
Real-time feedback for correct and incorrect selections
Win/lose states based on performance

🧠 Key Concepts & Implementation
State-driven architecture using app variables to manage modes, game flow, and UI
Hover-based interaction system for real-time constellation detection
Custom Button class for reusable UI components and click handling
Slide-based navigation system simulating movement across the night sky
Dynamic difficulty scaling (timer, lives, and visibility constraints)
Telescope vision effect using mouse tracking and layered rendering

🖥️ Technologies Used
Python
CMU Graphics (cmu_graphics)
Standard libraries: math, random

▶️ Running the Project
This project is built specifically for CMU Graphics, so it will not run in a standard Python environment without it.

Steps:
Install CMU Graphics:
Follow instructions from: https://academy.cs.cmu.edu/docs
Make sure cmu_graphics is available in your environment.

🎯 Controls
Mouse
Hover → preview constellations
Click → select constellation / interact with UI
Keyboard (Game shortcuts)
p → pause/unpause
w → trigger win state
l → trigger lose state

📝 Notes
All slide visuals are hand-drawn
Constellation overlays and descriptions are image-based
Designed for both educational use and interactive gameplay
