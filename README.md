# AI-Powered Wave Frequency Sensor & Network Coverage Area Prototype

An interactive real-time prototype for simulating electromagnetic wave propagation, RF frequency spectrum analysis, base station beamforming, and AI-driven signal diagnostics across network coverage areas.

## Features

- **Spatial RF Wave Simulation**: Real-time log-distance path loss, wave interference, obstacle shadowing, and beamforming models rendered on a 60 FPS HTML5 canvas.
- **Interactive AI Sensor Probe**: Drag-and-drop sensor probe for real-time localized RSSI, SINR, RSRP, and phase measurements.
- **Dynamic Spectral Analyzer**: Live Fast Fourier Transform (FFT) power spectral density visualizer with peak carrier detection and frequency band identification.
- **AI Neural Anomaly Detection**:
  - Broadband RF Jamming detection
  - Rogue base station / carrier spoofing identification
  - Severe multipath fading and dead-zone detection
- **AI Coverage Optimizer**: Heuristic AI algorithm to automatically adjust base station power, frequency allocation, and beam angles to eliminate coverage holes and minimize inter-cell interference.
- **Multi-Preset Environments**: Preconfigured scenarios including 5G Dense Urban mmWave, RF Jamming Attacks, Heterogeneous Multi-Band, and Rural Long-Range setups.

## How to Run

1. Open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari).
2. Or open the generated interactive artifact file directly within the Antigravity preview pane.

## Technologies Used
- HTML5 Canvas 2D Rendering Engine
- Tailwind CSS (gStatic distribution)
- JavaScript (ES6+ Native Wave Physics & Spectrum Math)
