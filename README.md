
# 🎙️ Video/Audio to Text with Semantic Search

This project extracts audio from a video, transcribes the audio using Google's Speech Recognition API, and performs advanced natural language processing (NLP) and semantic search using FAISS and Transformers.

---

## 📦 Clone the Repository

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/nchirag/Chat_With_Video.git
cd Chat_With_Video
```

---

## 🛠️ Install Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
```

Additionally, install **FFmpeg** (required by `pydub`):

* [FFmpeg installation guide](https://ffmpeg.org/download.html)

For example, on Ubuntu/Debian:

```bash
sudo apt update
sudo apt install ffmpeg
```

---

## 🚀 Quick Start

1. Place your `.mp4` or `.wav` file in the project directory.
2. Launch the Jupyter Notebook:

   ```bash
   jupyter notebook videoChat.ipynb
   ```

3. Follow the notebook cells to:
   - Extract audio from the video
   - Split audio into 60-second chunks
   - Transcribe audio using Google Speech Recognition
   - Generate embeddings using Sentence Transformers
   - Perform semantic search using FAISS

---

## 🧠 Features

- 🎞️ Convert video to audio using MoviePy
- 🔊 Transcribe audio in chunks using Google's API
- 📌 Generate sentence embeddings
- 🔍 Enable semantic search across the transcript
- ⚙️ Modular and easily extensible

---

## 🧰 Built With

- Python
- Pydub
- SpeechRecognition
- MoviePy
- Sentence Transformers
- Transformers
- FAISS (CPU)
- LangChain
- NumPy

---

## 🧩 Folder Structure

```
videoChat.ipynb       # Main pipeline
requirements.txt      # All required Python libraries
README.md             # Project overview and setup
```

---

## ✅ Future Improvements

- Add real-time audio streaming support
- Improve error handling on long audios
- Wrap as a web app (Streamlit or Flask)

---

## 📬 Contact

For feedback or collaboration:

- **GitHub**: [[your-profile-link](https://github.com/nchirag)]
- **Email**: [chirag.n3012@gmail.com](mailto:chirag.n3012@gmail.com)

