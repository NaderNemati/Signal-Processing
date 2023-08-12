# ECG Signal Processing Toolkit

Welcome to the **ECG Signal Processing Toolkit** repository. This project embarks on a journey of harnessing signal processing techniques to enhance the quality and utility of ECG data. By undertaking a series of meticulously designed tasks, this toolkit endeavors to elevate the accuracy and reliability of ECG analysis.

## Task 1: Resampling ECG Signals

A foundational aspect of this project revolves around resampling ECG signals to achieve a desired frequency of 200 Hz. This task is particularly relevant when dealing with ECGs recorded at different frequencies. For instance, ECGs sampled at 125 Hz and 800 Hz are resampled using distinct techniques to ensure uniformity. The up-sampling technique, driven by averaging, enhances the lower frequency ECGs, while the down-sampling technique, also employing averaging, aligns the higher frequency ECGs. The result is a harmonious set of ECG signals uniformly sampled at 200 Hz, facilitating consistent analysis.

## Task 2: Filtering for Enhanced Clarity

Signal quality is paramount in ECG analysis. To mitigate the impact of noise and baseline wander, a meticulously designed filter is employed. By computing parameters such as Nyquist rate, Sampling rate, and cutoff normalize rate, a bandpass filter is designed to effectively remove high-frequency noise and baseline wander. The filter's efficacy is validated through frequency domain analysis, leveraging Fast Fourier Transform (FFT) to visualize noisy frequencies. The filtered ECG signals emerge as a canvas primed for accurate peak detection and insightful analysis.

## Task 3: Robust Peaks Detection

Detecting peaks in ECG signals is pivotal in diagnosing various cardiac conditions. However, challenges arise from low-frequency components caused by patient breathing and other factors. To address this, a robust peaks detection algorithm is implemented, bolstered by threshold-based techniques. By judiciously setting thresholds at 200 and 800, local peaks and low-frequency components are intelligently managed, ensuring the accurate identification of significant R-peaks.

## Engage and Contribute

Delve into the intricacies of ECG Signal Processing. Uncover the methodologies employed in tasks ranging from resampling and filtering to peaks detection. Your active participation in this repository is encouraged and valued. Together, we strive to advance the realm of ECG analysis, enhance diagnostic accuracy, and contribute to a deeper understanding of cardiac health.

For queries, collaborations, or insights, feel free to reach out to [Nader Nemati](mailto:nnevar@utu.fi).

