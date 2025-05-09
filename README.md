PANGEA Soundlab
PANGEA Soundlab is a lightweight, browser-based generative audio platform that creates atmospheric soundscapes by randomly triggering audio samples. The application is designed to be modular, portable, and easy to use.

PANGEA Soundlab

Overview
PANGEA Soundlab loads WAV samples from a designated directory and plays them in randomized sequences, creating evolving, ambient soundscapes directly in your browser. No plugins or additional software required - just open the HTML file in a modern browser and explore.

Features
Browser-Based: Run the entire system from any modern web browser
Generative Audio: Randomly triggered samples create unique, never-repeating soundscapes
Customizable Parameters: Control density, pitch, reverb, and volume in real-time
Visual Feedback: Simple visualization shows when samples are triggered
Ultra-Lightweight: Minimal dependencies, designed for portability
Modular Design: Easy to expand with new features
Installation
Clone or download this repository:
git clone https://github.com/your-username/pangea-soundlab.git
No build process or dependencies to install! The system is ready to use.
Usage
Place WAV audio samples in the samples directory

Recommended: ambient sounds, drones, textures, and atmospheric samples
8-bit, 16-bit, or 24-bit WAV files are supported
Shorter samples (1-10 seconds) work best for layering
Open index.html in your web browser

Chrome, Firefox, Safari, and Edge are all supported
For best performance, use Chrome or Firefox
Click the "SCAN SAMPLES" button to load available audio files

Adjust parameters:

DENSITY: Controls how frequently samples are triggered (1-30)
PITCH: Adjusts playback speed/pitch of samples (0.5-2.0)
REVERB: Adds space and ambience to the sound (0-1.0)
VOLUME: Controls overall output level (0-1.0)
Click "START" to begin the generative soundscape

Click "STOP" when you wish to end the session

Folder Structure
pangea-soundlab/
├── index.html      # Main application file
├── README.md       # This documentation
└── samples/        # Directory for WAV audio samples
    ├── ambient1.wav
    ├── drone1.wav
    └── texture1.wav
    └── ... (your audio samples)
Hosting Online
To host PANGEA Soundlab online:

Upload the entire folder structure to any web hosting service
Ensure your audio samples are in the samples directory
Navigate to the URL where you've hosted the project
The application should function exactly as it does locally
Creating Your Own Samples
For the best experience with PANGEA Soundlab, consider these tips for creating samples:

Duration: 1-10 seconds is ideal for most samples
Character: Atmospheric, textural sounds work well for layering
Dynamics: Samples with gentle attacks and releases blend best
Processing: Adding some reverb or delay to samples can enhance the overall soundscape
Variety: Include a mix of high, mid, and low-frequency content
Technical Details
PANGEA Soundlab uses the Web Audio API to process and play audio in the browser. Key components include:

AudioContext: The core audio processing graph
Convolver: For reverb processing
GainNode: For volume control
AudioBufferSourceNode: For sample playback
No external libraries or frameworks are used to keep the project ultra-lightweight.

Browser Compatibility
Chrome 58+
Firefox 53+
Safari 11+
Edge 79+
Limitations
Audio may not play on mobile devices without user interaction
Performance may vary based on the number of samples loaded and system resources
Some browsers may limit audio processing in background tabs
Future Development
Planned features for future versions:

Additional audio effects (delay, filters, etc.)
Sample categorization and layering options
Preset system for saving configurations
Advanced visualization options
MIDI and OSC support for external control
Collaborative sessions
Contributing
Contributions are welcome! If you'd like to improve PANGEA Soundlab, please:

Fork the repository
Create a feature branch
Make your changes
Submit a pull request
License
This project is released under the MIT License.

Credits
PANGEA Soundlab was created as an ultra-lightweight, portable solution for generative ambient audio experiences.

Enjoy creating atmospheric soundscapes with PANGEA Soundlab! For questions, issues, or feature requests, please open an issue on the project repository.
