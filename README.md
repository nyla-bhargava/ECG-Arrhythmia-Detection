# ECG-Arrhythmia-Detection
A MATLAB-based ECG Arrhythmia Detection that loads ECG signals, detects heartbeats, calculates heart rate, and classifies arrhythmias (Normal, Bradycardia, Tachycardia). Features a clean, modern interface with real-time plotting and analysis.

Features:

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

   ![Detected R peaks](https://github.com/user-attachments/assets/67cf075c-969e-4535-9aef-4d2b443f10fa)

5. Heart Rate Calculation: Intervals between beats are used to calculate bpm.

   ![Instantaneous Heart Rate](https://github.com/user-attachments/assets/e5973d4a-d3c7-4fe7-ad78-a5d1042d2b3d)

6. Arrhythmia Classification: Based on bpm thresholds, the condition is classified.

7. Display: Results (bpm and arrhythmia status) are shown on the GUI, alongside the ECG graph.

   ![GUI](https://github.com/user-attachments/assets/22910f36-f653-4935-95ad-7feacca9be75)








