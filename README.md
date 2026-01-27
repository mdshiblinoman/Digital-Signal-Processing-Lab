# Digital Signal Processing Lab

A comprehensive collection of Jupyter Notebooks demonstrating fundamental concepts in Digital Signal Processing (DSP) using Python.

## 📋 Prerequisites

- Python 3.8 or higher
- Jupyter Notebook / JupyterLab / VS Code with Jupyter extension

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd Digital-Signal-Processing
   ```

2. **Create a virtual environment (recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   # or
   venv\Scripts\activate     # Windows
   ```

3. **Install required packages:**
   ```bash
   pip install numpy matplotlib scipy
   ```

## 📚 Notebooks Overview

| Notebook | Description |
|----------|-------------|
| [sineWave.ipynb](sineWave.ipynb) | Generation and visualization of sine waves |
| [coseWave.ipynb](coseWave.ipynb) | Generation and visualization of cosine waves |
| [elementary_signals.ipynb](elementary_signals.ipynb) | Unit impulse, unit step, ramp, and exponential signals |
| [sampling.ipynb](sampling.ipynb) | Sampling theorem and signal sampling demonstration |
| [quantization.ipynb](quantization.ipynb) | Quantization levels and quantization error |
| [quantization_sampling.ipynb](quantization_sampling.ipynb) | Combined sampling and quantization process |
| [alaising.ipynb](alaising.ipynb) | Aliasing effect when sampling below Nyquist rate |
| [upsampling-downsampling.ipynb](upsampling-downsampling.ipynb) | Sample rate conversion techniques |
| [convolution_correlation.ipynb](convolution_correlation.ipynb) | Linear convolution and correlation operations |
| [autocorrelation.ipynb](autocorrelation.ipynb) | Autocorrelation function and its properties |
| [crossCorrelation.ipynb](crossCorrelation.ipynb) | Cross-correlation between two signals |
| [dft_all.ipynb](dft_all.ipynb) | DFT, IDFT, magnitude/phase/power spectrum analysis |
| [difference_equation.ipynb](difference_equation.ipynb) | Solving difference equations for LTI systems |
| [system_function_magnitude_phase.ipynb](system_function_magnitude_phase.ipynb) | System function H(z), magnitude and phase response |
| [fir_filter.ipynb](fir_filter.ipynb) | FIR filter design and implementation |

## 🔑 Key Concepts Covered

### 1. Signal Generation
- Continuous and discrete-time signals
- Elementary signals (impulse, step, ramp, exponential)
- Sinusoidal signal generation

### 2. Sampling & Quantization
- Nyquist sampling theorem: $f_s \geq 2f_{max}$
- Aliasing effects and prevention
- Quantization levels and bit depth
- Upsampling and downsampling

### 3. Convolution & Correlation
- Linear convolution: $y[n] = x[n] * h[n]$
- Autocorrelation: $R_{xx}[l] = \sum_{n} x[n] \cdot x[n-l]$
- Cross-correlation for signal similarity

### 4. Frequency Domain Analysis
- **DFT:** $X[m] = \sum_{n=0}^{N-1} x[n] \cdot e^{-j\frac{2\pi mn}{N}}$
- **IDFT:** $x[n] = \frac{1}{N} \sum_{m=0}^{N-1} X[m] \cdot e^{j\frac{2\pi mn}{N}}$
- Magnitude, phase, and power spectrum

### 5. Digital Filters
- FIR filter design using window method
- Filter frequency response analysis

## 🚀 How to Run

1. Open the notebooks in Jupyter or VS Code
2. Run cells sequentially (Shift + Enter)
3. Modify parameters to experiment with different signals

## 📁 Project Structure

```
Digital-Signal-Processing/
├── README.md                         # This file
├── sineWave.ipynb                    # Sine wave generation
├── coseWave.ipynb                    # Cosine wave generation
├── elementary_signals.ipynb          # Basic signal types
├── sampling.ipynb                    # Sampling demonstration
├── quantization.ipynb                # Quantization process
├── quantization_sampling.ipynb       # Combined sampling & quantization
├── alaising.ipynb                    # Aliasing effect
├── upsampling-downsampling.ipynb     # Sample rate conversion
├── convolution_correlation.ipynb     # Convolution & correlation
├── autocorrelation.ipynb             # Autocorrelation
├── crossCorrelation.ipynb            # Cross-correlation
├── dft_all.ipynb                     # DFT analysis
├── difference_equation.ipynb         # Difference equations
├── system_function_magnitude_phase.ipynb  # System analysis
└── fir_filter.ipynb                  # FIR filter design
```

## 📖 References

- Oppenheim, A. V., & Schafer, R. W. - *Discrete-Time Signal Processing*
- Proakis, J. G., & Manolakis, D. G. - *Digital Signal Processing*
- NumPy Documentation: https://numpy.org/doc/
- SciPy Signal Processing: https://docs.scipy.org/doc/scipy/reference/signal.html

## 📝 License

This project is for educational purposes.
