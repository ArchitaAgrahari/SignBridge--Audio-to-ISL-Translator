# SignBridge: Audio-to-ISL Translator

SignBridge is an innovative application designed to empower individuals with hearing and speech impairments by translating spoken language into Indian Sign Language (ISL). The system leverages real-time audio processing to display corresponding ISL gestures visually, either through animations or letter images.

## Features
- **Real-Time Speech Recognition:** Processes spoken language via a microphone.
- **Sign Language Translation:** Converts recognized speech into ISL gestures (GIFs or alphabet images).
- **Graphical User Interface:** Built using `tkinter` for a user-friendly experience.
- **Extensive ISL Gesture Library:** Supports predefined phrases and alphabetic characters.

## Technologies Used
- **Programming Language:** Python
- **Libraries and Frameworks:**
  - `speech_recognition` for audio input processing.
  - `tkinter` for the graphical user interface.
  - `Pillow` and `matplotlib` for image processing and visualization.
  - `easygui` for dialog boxes.
  - `numpy` for handling images as arrays.
  - `OpenCV` for additional visualization options.

## Prerequisites
1. Install Python 3.x.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<your_username>/<repository_name>.git
   cd <repository_name>
   ```
2. Set up the project directories:
   - `ISL_Gifs/`: Contains ISL gesture GIFs for predefined phrases.
   - `letters/`: Contains images of letters for alphabet visualization.
3. Ensure your microphone is properly configured for audio input.

## Usage
1. **Run the Main Application:**
   ```bash
   python main.py
   ```
2. **Start Live Voice Recognition:**
   - Click "Start Live Voice" in the GUI or use the button provided in the easygui dialog.
   - Speak clearly into the microphone.
3. **Output:**
   - If the recognized phrase matches a predefined ISL phrase, the corresponding GIF will be displayed.
   - For non-predefined phrases, individual letter images will be shown sequentially.

## Project Structure
```
.
|-- main.py                # GUI-based implementation
|-- main1.py               # Console-based implementation
|-- ISL_Gifs/              # Directory containing ISL gesture GIFs
|-- letters/               # Directory containing letter images
|-- requirements.txt       # List of dependencies
|-- README.md              # Project documentation
```

## Future Enhancements
- Add support for additional regional languages.
- Implement bidirectional translation (ISL to audio/text).
- Enhance gesture visualization using 3D animations.

## Contribution
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.
.

## Acknowledgements
- Developers of `speech_recognition`, `tkinter`, and other libraries used.
- Community contributors for promoting inclusivity through technology.


