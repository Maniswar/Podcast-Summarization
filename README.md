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



![Screenshot 2025-02-08 154205](https://github.com/user-attachments/assets/a0f318fd-8550-43f2-acb2-2286dcd13bc7)
![Screenshot 2025-02-08 154158](https://github.com/user-attachments/assets/589f8497-cc14-4366-b667-94bd096d07a9)
![Screenshot 2025-02-08 154139](https://github.com/user-attachments/assets/de220b87-448d-47c3-8537-d92b1334ae75)
![Screenshot 2025-02-08 154130](https://github.com/user-attachments/assets/d131b651-e396-4e8f-9cee-9d1e1c21820e)
![Screenshot 2025-02-08 154108](https://github.com/user-attachments/assets/f9d13e8b-bad9-4c6b-bb91-4a8a6bbaf5a1)
![Screenshot 2025-02-08 154055](https://github.com/user-attachments/assets/aaadbac7-2516-4229-b0bf-1618f0ac4edb)
![Screenshot 2025-02-08 154046](https://github.com/user-attachments/assets/f0197b4d-55f5-4ae0-9886-39a8166ce3d7)


