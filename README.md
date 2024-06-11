# EAGLE - Earth and Galactic Locus Evaluator

## Overview

EAGLE (Earth and Galactic Locus Evaluator) is a state-of-the-art software tool designed for the propagation of satellite constellations' orbits and the generation of ground tracks for acquisitions. EAGLE offers precision, reliability, and efficiency, making it an essential tool for satellite operators and researchers in the field of astrodynamics.

## Features

- **Orbit Propagation**: Accurately propagate the orbits of a constellation of satellites.
- **Ground Track Generation**: Generate detailed ground tracks of satellite acquisitions.
- **Constellation Management**: Support for multiple satellites and constellation configurations.
- **Visualization**: Graphical representation of orbits and ground tracks.
- **Data Export**: Export ground tracks and orbital data in various formats for further analysis.

## Installation

### Prerequisites

Before installing EAGLE, ensure you have the following prerequisites installed on your system:

- Python 3.8 or higher
- NumPy
- Matplotlib
- Pandas
- SciPy

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/eagle.git
   cd eagle

2. **Install the required Python packages**:
    ```bash
    pip install -r requirements.txt

## Usage

### Basic Usage

1. **Configure your satellite constellation**:
   Edit the `config/constellation_config.json` file to define the parameters of your satellite constellation.

2. **Run the orbit propagation**:
   ```bash
   python propagate_orbits.py
