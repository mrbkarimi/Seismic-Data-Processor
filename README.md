
<img width="950" height="982" alt="image" src="https://github.com/user-attachments/assets/573602a0-7564-4764-ac3f-ad97a081c0f1" />




# Seismic Data Processor

Python/Tkinter desktop application for batch processing of acceleration time-series records (generic time–acceleration formats). The tool supports baseline-correction checks, Butterworth filtering, unit conversion, FFT analysis, PSD estimation using Welch's method, response-spectrum analysis (time-domain and FFT-based), intensity-measure calculation, and automated export of metadata, processed records, spectra, plots, and summary files.

## Key Features

- Batch processing of time-acceleration records
- Support for AFAD, PEER, and two-column time–acceleration formats
- Unit conversion for acceleration records in g, m/s², and cm/s²
- Baseline-correction check and optional correction
- Butterworth band-pass filtering
- Velocity and displacement calculation through numerical integration
- Optional velocity and displacement filtering
- FFT-based frequency analysis
- PSD estimation using Welch’s method
- Arias intensity and significant duration calculation
- Cumulative Absolute Velocity calculation
- Bracketed duration calculation
- PGA, PGV, and PGD calculation
- Response-spectrum analysis using time-domain and FFT-based approaches
- Automated export of metadata, processed records, spectra, plots, and summary files
- Graphical user interface for non-programming users

## Input Formats

The application currently supports:

- Two-column time–acceleration files
- AFAD strong-motion record format
- PEER strong-motion record format
- Text, CSV, and Excel-based acceleration records

## Outputs

The tool can generate:

- Metadata summary files
- Filtered and corrected acceleration records
- Velocity and displacement time histories
- FFT magnitude-frequency files
- PSD frequency-domain summaries
- Response-spectrum files
- Arias intensity and CAV values
- Summary plots
- Batch-processing outputs for multiple records

## Technologies Used

- Python
- Tkinter
- NumPy
- pandas
- SciPy
- Matplotlib
- tqdm
- pywin32

## Purpose

This tool was developed to support reproducible vibration (acceleration) record processing and dynamic response analysis. It is intended for research and educational use in signal processing, structural dynamics, vibration-based monitoring, and data-driven condition assessment.

## Author

Mohammad Reza Bagerzadeh Karimi  
Assistant Professor, Department of Civil Engineering  
Cyprus International University
