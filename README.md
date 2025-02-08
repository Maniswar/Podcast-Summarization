# Podcast-Summarization
# Podcast Transcription

## Overview
This project provides an automated way to transcribe podcasts using speech-to-text conversion via API keys from ListenNotes and Assembly AI. It fetches podcast audio using ListenNotes API keys and transcribes it using Assembly AI for accurate text conversion.

## Features
- Retrieves podcast audio using API keys from ListenNotes.
- Converts podcast audio into text using ASR (Automatic Speech Recognition) via Assembly AI.
- Supports multiple audio formats (MP3, WAV, etc.).
- Provides an option to download the transcribed text as a file.
- Runs directly from the command line.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/podcast-transcription.git
   cd podcast-transcription
   ```
2. Create a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage (Command Line)
1. Retrieve podcast audio using ListenNotes API.
2. Run the transcription script using Assembly AI from the command line:
   ```sh
   python transcribe.py --file input/podcast.mp3
   ```
3. The transcribed text will be saved in the `output/` directory.
4. Optionally, run the Streamlit web interface:
   ```sh
   streamlit run app.py
   ```
5. Download the transcribed output from the web interface.

## Configuration
- Modify `config.json` to add your ListenNotes and Assembly AI API keys and adjust transcription settings.

## Dependencies
- Python 3.8+
- `requests` (API integration)
- `streamlit` (Web interface)
- `pydub` (Audio processing)
- `assemblyai` (Speech-to-text processing)

## Roadmap
- [ ] Improve transcription accuracy with enhanced models.
- [ ] Implement multi-language support.
- [ ] Enhance Streamlit UI with additional features.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, feel free to reach out!
