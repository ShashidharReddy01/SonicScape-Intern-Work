# SonicScape-Intern-Work
<details>
  <summary>Signal Processing Techniques for Similarity Checks Between Patterns</summary>
  
# Signal Processing Techniques for Similarity Checks Between Patterns

## Cross Correlation
- Measure of similarity of two series as a function of displacement of one relative to the other.
- Ranges from -1 to +1.

## Dynamic Time Warping (DTW)
- Compares two temporal sequences that don't perfectly sync up through mathematics.
- Uses adaptive time normalization to create a warping path for sequences with different lengths and speeds.
- Requires matching every index from the first sequence with one or more indices from the other sequence.

## Fast Fourier Transform (FFT)
- Decomposes the original sequence of length N into a series of short sequences.
- Transforms signals from the time domain to the frequency domain.
- Frequency components can be used to identify similarity.

## Wavelet Transform
- Efficient method for evaluating small waves.
- Includes two transformation techniques: Continuous Wavelet Transform (CWT) and Discrete Wavelet Transform (DWT).
- Decomposes a signal into a set of basis functions (wavelets) that can analyze at various scales.

## Short Time Fourier Transform (STFT)
- Computes the Fourier transform of short, overlapping windows of the signal to analyze frequency over time.
- Used to determine sinusoidal frequency and phase content of local sections of a signal.
- Provides a smoother and more accurate frequency spectrum compared to FFT.

## Autocorrelation
- Measures the similarity of a signal with a delayed version of itself to identify repeating patterns.
- Not appropriate for comparing two different signals.

## Spectral Coherence
- Measures coherence between two signals in the frequency domain to identify common frequency components.
- Commonly used to estimate power transfer between input and output of a linear system.
- Tests for similar frequency components to determine the degree of linear dependency between signals.

## Singular Value Decomposition (SVD)
- Decomposes the data matrix into its constituent parts to identify common patterns.

## Principal Component Analysis (PCA)
- Reduces the dimensionality of data while preserving information to identify similarity.
- Similar datasets will have similar principal components.

## Dynamic Mode Decomposition (DMD)
- Data-driven analysis decomposes complex, non-linear systems into modes revealing underlying patterns and dynamics through spectral analysis.
- Used for dimensionality reduction, pattern recognition, noise reduction, and anomaly detection.

## Empirical Mode Decomposition (EMD)
- Decomposes signals into a set of oscillatory components called Intrinsic Mode Functions (IMFs) to analyze similarities.
- Useful for non-stationary signals.
- Output remains in the time spectrum and is not based on sine waves like FFT.

## Envelope Analysis
- Targets amplitude variation in vibration signals.
- Steps include shifting the frequency range in the high-frequency band to the base band, filtering the frequency-shifted signal using a low-pass filter, and calculating the envelope signal of the filtered signal.

## Hilbert Transform
- Computes instantaneous frequency and amplitude of a signal to analyze similarity in the time-frequency domain.
- Imparts a phase shift of +90 or -90 degrees to every frequency component of a function.
- Used to remove rapid oscillations from a signal to produce a direct representation of the envelope.

## Cosine Similarity
- Measures similarity between different data points or signals by calculating the cosine of the angle between two signals.
- Measures similarity based on the orientation of the signal.

## Symbolic Aggregate Approximation (SAX)
- Approximates time series data as a sequence of symbols to reduce dimensionality while preserving important characteristics.
- Reduces index dimension by using the boundary distance measure, which is lower than the Euclidean distance.

## Symbolic Bispectra based Lempel Ziv Complexity
- Combines symbolic representation with bispectral analysis, which examines the interaction between different frequency components of data.

</details>


