# Neon Drone Dashboard

A futuristic, neon-themed drone telemetry dashboard built with Streamlit. This application visualizes real-time drone data, including flight status, location, and sensor readings, in a sleek and modern interface.

## Features

- **Real-time Telemetry:** Displays live data for battery, signal strength, altitude, temperature, pressure, and more.
- **3D Drone Model:** A 3D representation of the drone, providing a visual reference.
- **Interactive Map:** Shows the drone's current location on a map.
- **Speedometer Gauges:** Visual gauges for speed, altitude, battery, and signal strength.
- **Live Data Trends:** Line charts showing the trends of key telemetry data over time.
- **Customizable Controls:** Simulate different conditions with controls for simulation speed and sensor toggles.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the application, use the following command:

```bash
streamlit run "drone last.py"
```

This will start the Streamlit server and open the application in your default web browser.

## Dependencies

- streamlit
- plotly
- pandas
- numpy
