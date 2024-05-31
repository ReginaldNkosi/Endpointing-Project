# Endpointing-Project
Robust speech endpointing refers to the process of accurately detecting the start and end points of speech segments within an audio signal, even in the presence of noise or other interfering factors. The goal of robust speech endpointing is to accurately identify the boundaries of speech segments.
# Endpointing.m

This MATLAB script is designed for audio recording and processing, specifically for speech endpoint detection. It provides functionalities for recording audio, selecting folders containing WAV files, playing back recorded audio, and analyzing speech signals for endpoint detection using energy and entropy procedures.

## Functionality

### StartRecordingButtonPushed
- Initializes audio recording with user-specified parameters (sampling rate, duration).
- Records audio and saves it as a WAV file.
- Updates the list of available WAV files for further processing.

### SelectFolderButtonPushed
- Prompts the user to select a folder containing WAV files.
- Lists the WAV files in the selected folder for further processing.

### WaveFilesFoundListBoxValueChanged
- Plays back the selected WAV file.
- Performs speech endpoint detection based on the selected mode (Energy Procedure or Entropy Procedure).
- Displays the energy profile or entropy profile depending on the selected mode.
- Highlights speech segments and noise segments based on thresholding.

### ModeSwitchValueChanged
- Updates the selected mode for speech endpoint detection (Energy Procedure or Entropy Procedure).

### BuffersecEditFieldValueChanged
- Updates the buffer size for speech endpoint detection.

### EnergyThresholdEditFieldValueChanged
- Updates the energy threshold for speech endpoint detection.

### EntropyThresholdEditFieldValueChanged
- Updates the entropy threshold for speech endpoint detection.

## Usage
1. Run the script in MATLAB.
2. Interact with the user interface to perform audio recording, file selection, and speech endpoint detection.
3. Adjust parameters as needed for different recording and detection scenarios.

## Dependencies
- MATLAB with Signal Processing Toolbox
- Compatible audio input/output devices

## License
This script is provided under the [MIT License](LICENSE).

## Acknowledgments
Special thanks to the MATLAB community for contributions and support in audio processing and analysis.

