# 🔊 Audio Denoiser — AI-Based Noise Reduction

This project demonstrates an **AI-powered audio denoising system** that cleans noisy audio clips using signal processing and machine learning. It removes background noise from speech or music recordings, making them clearer and more intelligible.

## 🚀 Key Features

✅ Supports WAV/MP3 input files  
✅ Uses noise profile estimation and spectral subtraction techniques  
✅ Visualizes noisy and denoised waveforms for comparison  
✅ Simple to run via Jupyter Notebook  
✅ Can be adapted for real-time or batch audio denoising  

---

## 🛠️ Technologies Used

- Python 3.x
- Librosa
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook
- CNN

---

## 📸 Demo Output

Running the notebook will:
- Plot noisy and denoised waveforms side by side
- Play both audio versions for auditory comparison
- Save cleaned audio files

---

## 🏃‍♀️ How to Run

1️⃣ **Clone the repo:**
```bash
git clone https://github.com/Hina19/Audio-Denoiser.git
cd Audio-Denoiser
2️⃣ Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
(Create requirements.txt with the following if you haven’t yet):

nginx
Copy
Edit
librosa
numpy
scipy
matplotlib
3️⃣ Add audio files:

Place noisy audio clips in audio_samples/ (e.g., audio_samples/noisy_sample.wav).

4️⃣ Run the notebook:

bash
Copy
Edit
jupyter notebook Audio_denoising.ipynb
📚 How it Works
1️⃣ Audio Loading: Reads the noisy audio file.
2️⃣ Noise Estimation: Estimates a noise profile from the quiet parts of the audio.
3️⃣ Spectral Subtraction: Reduces noise by subtracting estimated noise spectrum from the signal spectrum.
4️⃣ Signal Reconstruction: Reconstructs and saves/playback the denoised audio.
5️⃣ Visualization: Compares noisy and cleaned signals through waveform plots.

🌟 Use Cases
✅ Enhancing audio quality for podcasts or interviews
✅ Cleaning up voice recordings for transcription
✅ Improving speech clarity in noisy environments
✅ Audio preprocessing for speech recognition or ML tasks

🙌 Contributing
Contributions are welcome! Feel free to fork the repository, raise issues, or submit pull requests.

⭐ If you find this project useful, please consider giving it a star!
