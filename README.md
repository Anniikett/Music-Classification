# Music-Classification
Music Classification LSTM


# Music classification using Keras


# What is Sound?
**The sound is represented in an audio signal. It is as a level of electrical voltage for analog signals, and a series of binary number for digital signals.**

**Audio signals have frequencies in the audio frequency range of roughly 20 to 20,000 Hz, which corresponds to the upper and lower limits of human hearing.**

# List of format for a sound file:

1. WMA - Windows Media Audio,

2. WAV - Waveform Audio,

3. MIDI - Music Instrument Digital Interface,

4. AAC - Advanced Audio Coding,

5. Ogg Vorbis - A free, open and un-patented music format,

6. ADPCM - Adaptive Differential Pulse Code Modulation,

7. ASF - Advanced Streaming Format,

8. VQF - Vector Quantization Format,

9. ATRAC - Sony's Adaptive Transform Acoustic Coding 3.


# LIBROSA
**Librosa is a python package for music and audio analysis. It provides the building blocks necessary to create music information retrieval systems.**


**What is the sampling rate?**

*The sample rate is the number of samples of audio carried per second, measured in Hz or kHz*

# Waveform
**A waveform is an image that represents an audio signal or recording. It shows the changes in amplitude over a certain amount of time.**

# Spectrogram
**A spectrogram is a visual representation of the spectrum of frequencies of a signal as it varies with time. When applied to an audio signal, spectrograms are sometimes called sonography, voiceprints, or voicegrams. When the data is represented in a 3D plot they may be called waterfalls.**


# zero-crossing rate
**The zero-crossing rate is the rate of sign-changes along a signal, i.e., the rate at which the signal changes from positive to zero to negative or from negative to zero to positive.**

**This feature has been used heavily in both speech recognition and music information retrieval,
being a key feature to classify percussive sounds like those in metal and rock.**


# Spectral Centroid
**The spectral centroid is a measure used in digital signal processing to characterize a spectrum. It indicates where the "center of mass" of the spectrum is located. Perceptually, it has a robust connection with the impression of "brightness" of a sound.**


# Spectral Rolloff
**It is a measure of the shape of the signal. It represents the frequency below which a specified percentage of the total spectral energy**


# Mel-frequency cepstrum(MFCCs)
**The Mel frequency cepstral coefficients (MFCCs) of a signal are a small set of features (usually about 10–20) which concisely describe the overall shape of a spectral envelope. It models the characteristics of the human voice.**


# Chroma Frequencies
**Chroma features are an interesting and powerful representation for music audio in which the entire spectrum is projected onto 12 bins representing the 12 distinct semitones (or chroma) of the musical octave.**



The dataset consists of 10 genres i.e
 * Blues
 * Classical
 * Country
 * Disco
 * Hiphop
 * Jazz
 * Metal
 * Pop
 * Reggae
 * Rock
 
 Each genre contains 100 songs. Total dataset: 1000 songs

