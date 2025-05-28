# Voice Translation and Cloning in Cartoons

This project demonstrates how to use Generative AI for translating and cloning voices in video content, specifically in old cartoons. The system extracts audio, separates voice and background, transcribes and translates speech, and synthesizes a new voice that mimics the original speaker’s intonation — all while replacing the audio in the original video.

🔧 Technologies Used
	•	Python
	•	MoviePy – for video/audio extraction and merging
	•	Spleeter – for vocal/background audio separation
	•	PyAnnote.audio – speaker diarization
	•	OpenAI Whisper – speech-to-text
	•	GoogleTranslator API – text translation
	•	TTS (Tacotron2-DDC / XTTSv2) – text-to-speech synthesis
	•	Seed-VC – voice cloning with intonation transfer
	•	Google Colab – for running the full pipeline in the cloud

📎 Run the Project

You can test the full pipeline in this [Google Colab notebook](https://colab.research.google.com/drive/1egHqRFH5DPCSPrhP_dOu3d9Vp8eaEaJq#scrollTo=LIpWEMR1_lRK).
Or use attached [file](https://github.com/yakimenko-vin/lms.robotdreams/blob/main/video_translator.ipynb)
