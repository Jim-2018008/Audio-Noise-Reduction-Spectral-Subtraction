# Audio Noise Reduction Using Spectral Subtraction

## About
This project implements spectral subtraction for noise removal in audio files. It processes noisy audio data with corresponding noise data to enhance clean audio output, demonstrating audio preprocessing techniques using Python libraries like Librosa and Soundfile.

## Requirements
- Python 3.x
- librosa
- numpy
- soundfile
- matplotlib

## Usage
1. Place your audio files in the appropriate directories: `clean_train`, `clean_test`, `noise_train`, `noise_test`.
2. Run the script `spectral_subtraction.py` to process the audio.
3. The cleaned audio will be saved in the `export_clean_train` and `export_clean_test` folders.

## How It Works
1. The script applies spectral subtraction to noisy audio signals.
2. It computes the Short-Time Fourier Transform (STFT) of both the noisy and noise signals.
3. Spectral subtraction is performed to reduce noise and output a cleaner version of the audio.

## Contributing
Feel free to open issues and submit pull requests for improvements or bug fixes.

## License
This project is open source and available under the MIT License.
