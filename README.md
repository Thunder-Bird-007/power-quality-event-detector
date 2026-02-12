# Power Quality Event Detector (Signal + ML roadmap)

This project starts with signal generation and rule-based detection of power quality events
(sag, swell, harmonics, transient spikes). Later, it will be upgraded to ML-based classification.

## Features
- Signal preprocessing
- Event detection using thresholds / RMS / FFT features
- Plots and summary report

## Tech
Python, NumPy, SciPy, Matplotlib, Pandas

## How to run
1) Install requirements:
```bash
pip install -r requirements.txt 
```
2) Run:
```bash
python src/main.py
```

## Current progress
- [x] Task A: Generate clean sine wave and plot

## Roadmap
1. Signal generation + noise
2. Inject events (sag/swell/spike/harmonics)
3. Windowing + feature extraction
4. Rule-based detector
5. ML upgrade using scikit-learn


## Example output

(Add a screenshot/plot here later)

## Author

Your Name
