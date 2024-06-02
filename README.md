Hey There! 
This project demonstrates how to translate the audio from an English video to Hindi and merge the translated audio back into the video. The sample video features Sudha Murty speaking in English, which is translated to Hindi.

## Usage
1. Set the input video path:
   Replace the path to your input video in the script:
            input_video_path = "D:\\video translation\\video.mp4"
2. Extract audio from the video:
   The script extracts the audio from the input video and saves it as output_audio.wav.

3. Transcribe the audio:
   The script uses Google Speech Recognition to transcribe the audio to text.

4. Translate the transcribed text:
   The script translates the transcribed English text to Hindi using Google Translate.

5. Convert translated text to audio:
   The translated Hindi text is converted to speech using the Google Text-to-Speech (gTTS) library, saving it as translated_audio.mp3.

6. Merge translated audio with the original video:
   The script replaces the original audio of the video with the translated Hindi audio and saves the result as translated_video.mp4.

7. Clean up temporary files:
   The script removes the temporary audio files created during the process.

## Requirements

To run this project, you'll need the following libraries:
- `moviepy`
- `speech_recognition`
- `googletrans`
- `gtts`

You can install these libraries using pip:
```bash
pip install moviepy speechrecognition googletrans==4.0.0-rc1 gtts

This `README.md` file provides an overview of the project, the steps involved, and the complete Python code used. Adjust the paths and any specific details according to your setup and preferences.
