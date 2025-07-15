# Audio_Emotions_Analyzer
# 🎙️ Audio Analyzer v1.0

**Author**: Mariel Gonzalez  
**Version**: 1.0  
**Project**: Audio Emotions Analyzer  
**Focus**: Tone and Voice Recognition with LLM-Related Audio Analysis

## 📘 Overview

`audio_analyzer_v1.0.ipynb` is a Jupyter Notebook designed to perform small-scale voice and tone recognition using foundational techniques in natural language processing (NLP) and audio signal analysis. This tool aims to extract and analyze vocal features to assess speaker tone, pitch, and other audio characteristics for experimental LLM-enhanced audio recognition pipelines.

## Key Features

- **Audio Preprocessing**: Converts raw audio input into usable formats (e.g., waveform arrays, mel-spectrograms).
- **Feature Extraction**:
  - MFCC (Mel Frequency Cepstral Coefficients)
  - Pitch detection
  - Energy/Amplitude profiling
- **Tone Classification**: Experimental voice tone detection (e.g., calm, angry, excited) using feature patterns.
- **Visualization**: Generates spectrograms and waveform plots for audio inspection.
- **LLM Pipeline Integration (Planned)**: Structures audio data for potential downstream use in multimodal models.

## File Structure

```bash
audio_analyzer_v1.0.ipynb       # Main Jupyter Notebook
/sample_audio/                   # Directory for sample .wav files (if applicable)
/outputs/                        # Directory for plots and extracted features
```

## Dependencies

Make sure to install the following Python packages before running the notebook:

```bash
pip install librosa matplotlib numpy scipy pandas soundfile
```

If tone classification models are included:

```bash
pip install scikit-learn
```

## How to Use

1. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook audio_analyzer_v1.0.ipynb
   ```

2. **Upload or Load Audio File**:
   - The notebook supports `.wav` format.
   - Customize the `AUDIO_FILE_PATH` variable as needed.

3. **Run All Cells**:
   - The notebook will process the audio, extract features, generate plots, and (if implemented) provide tone classification results.

## Example Output

- Waveform and mel-spectrogram plots
- MFCC feature arrays
- Detected pitch over time
- Predicted tone label (if classification is implemented)

## Future Improvements

- Integrate real-time audio input via microphone
- Add support for more emotion/tone classes
- Explore transformer-based audio models for richer feature embeddings
- Export results to a structured JSON or CSV format

## License

This project is for academic and research purposes only.  
© 2025 [Mariel Gonzalez / UMN]
