# 🏎️ Formula 1 Driver Performance Analysis

A Python-based data analysis project that compares Formula 1 driver performance using real race session data from the [FastF1 API](https://docs.fastf1.dev/). The project analyzes lap times, calculates average pace, and visualizes performance differences between drivers using Pandas and Matplotlib.

The initial version focuses on comparing drivers such as Max Verstappen and Charles Leclerc during a selected Grand Prix, providing a foundation for more advanced telemetry and race-strategy analysis.

## 📌 Project Overview

This project uses real Formula 1 timing data to explore how driver performance can be analyzed beyond finishing positions and race results.

It retrieves historical session data, processes lap-level timing information, filters valid and representative quick laps, and compares the average lap times of two drivers. Visualizations help identify pace differences and lap-to-lap variations throughout a session.

The analysis is developed in a Jupyter Notebook, with `uv` used for dependency management and FastF1 caching used to reduce repeated data downloads.

## ⚙️ Getting Started

### Prerequisites

- Python
- [uv](https://docs.astral.sh/uv/getting-started/installation/)
- Git

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/f1-driver-performance-analysis.git
cd f1-driver-performance-analysis
```

Replace `YOUR_USERNAME` with your GitHub username.

### 2. Install dependencies

If your project contains a `pyproject.toml` file, install the dependencies using:

```bash
uv sync
```

### 3. Start Jupyter Notebook

```bash
uv run jupyter notebook
```

Open the project notebook and execute the cells in sequence.

## 📊 Example Analysis

The notebook compares two drivers in a selected Grand Prix session.

- **Driver 1:** Max Verstappen
- **Driver 2:** Charles Leclerc
- **Session:** Selected Grand Prix session

The comparison table summarizes average lap times and the number of laps analyzed.

| Driver | Average Lap Time | Laps Analyzed |
|---|---|---|
| Driver 1 | Calculated from session data | Based on filtering |
| Driver 2 | Calculated from session data | Based on filtering |

*Actual values depend on the selected event, session, drivers, and lap-filtering criteria.*

### Lap-Time Visualization

The Matplotlib chart helps identify:

- Differences in average pace.
- Consistency across laps.
- Faster and slower laps.
- Changes in pace throughout the session.
- Potential outliers in lap times.

A lower average lap time indicates faster pace over the analyzed laps. However, tyre strategy, traffic, pit stops, and other race conditions can affect the comparison.

### Improvements will be made in future
