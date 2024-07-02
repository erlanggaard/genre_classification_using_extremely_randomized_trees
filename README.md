# Genre Classification Using Extremely Randomized Trees

## Introduction

This repository contains code for a Python model that classifies music genres using Extremely Randomized Trees as the classification algorithm. The features extracted for this model are:

- Mel Frequency Cepstrum Coefficients (MFCC)
- Chroma Short-Time Fourier Transform (Chroma STFT)
- Chroma Constant-Q Transform (Chroma CQT)
- Spectral Bandwidth
- Spectral Rolloff
- Spectral Contrast

## Features

1. **Mel Frequency Cepstrum Coefficients (MFCC)**:
   - Captures the power spectrum of a sound.
   - Commonly used for speech and audio processing.

2. **Chroma Short-Time Fourier Transform (Chroma STFT)**:
   - Represents the 12 different pitch classes.
   - Useful for detecting harmonic and melodic characteristics.

3. **Chroma Constant-Q Transform (Chroma CQT)**:
   - Similar to Chroma STFT but uses a logarithmically spaced frequency axis.
   - Better for music signals with varying tempo.

4. **Spectral Bandwidth**:
   - Measures the width of the spectrum.
   - Indicates the range of frequencies present in the signal.

5. **Spectral Rolloff**:
   - The frequency below which a specified percentage of the total spectral energy lies.
   - Helps distinguish between harmonic and percussive elements.

6. **Spectral Contrast**:
   - Measures the difference in amplitude between peaks and valleys in a sound spectrum.
   - Useful for identifying musical timbre.

## Installation

To run this project, ensure you have Python installed. Then, install the necessary dependencies using pip:

```sh
pip install -r requirements.txt
```

## Usage

1. Clone the repository:

```sh
git clone https://github.com/erlanggaard/genre_classification_using_extremely_randomized_trees.git
cd genre_classification_using_extremely_randomized_trees
```

2. Prepare your dataset and place it in the `data` directory.

3. Run the CODE, and lets rock and roll


## Contact

For any questions or inquiries, please contact me at [erlanggaard131@gmail.com](mailto:erlanggaard131@gmail.com).

---

Feel free to modify any sections as needed for your specific project.
