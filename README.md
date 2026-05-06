# Seismic Data Processor

Seismic Data Processor is a Python/Tkinter desktop application for batch processing earthquake acceleration records. It supports common seismic data formats and provides tools for signal preprocessing, filtering, spectral analysis, intensity-measure calculation, response-spectrum analysis, visualization, and automated export of processed results.

## Key Features

- Batch processing of earthquake acceleration records
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

- AFAD strong-motion record format
- PEER strong-motion record format
- Two-column time–acceleration files
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

This tool was developed to support reproducible earthquake record processing and seismic response analysis. It is intended for research and educational use in earthquake engineering, seismic signal processing, structural dynamics, and data-driven seismic assessment.

## Author

Mohammad Reza Bagerzadeh Karimi  
Assistant Professor, Department of Civil Engineering  
Cyprus International University
