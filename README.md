# ECG-Arrhythmia-Detection
A MATLAB-based ECG Arrhythmia Detection that loads ECG signals, detects heartbeats, calculates heart rate, and classifies arrhythmias (Normal, Bradycardia, Tachycardia). Features a clean, modern interface with real-time plotting and analysis.

Features
-Upload ECG File (.csv format)

-Automatic Heartbeat Detection

-Heart Rate (bpm) Calculation

-Filtered ECG Signal Plot

-Arrhythmia Classification:

      Normal (60–100 bpm)

     Bradycardia (< 60 bpm)

     Tachycardia (> 100 bpm)

How It Works:
1. Load ECG: User uploads a .csv file containing ECG signal values.

2. Preprocessing: Signal is filtered to reduce noise.

3. Peak Detection: R-peaks are detected using signal processing techniques.

4. Heart Rate Calculation: Intervals between beats are used to calculate bpm.

5. Arrhythmia Classification: Based on bpm thresholds, the condition is classified.

6. Display: Results (bpm and arrhythmia status) are shown on the GUI, alongside the ECG graph.

![ECG GUI Screenshot]()



