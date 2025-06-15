Synthetic Driving Data Simulator (Node.js)

Simulate realistic driving sessions with synthetic GPS, accelerometer, and gyroscope data. This tool generates time-series data for testing, analysis, or visualization purposes.

Features

- Simulates 3–5 driving trips (3–10 minutes each)
- Models realistic driving behaviors:
  - Starting and stopping
  - Acceleration and deceleration
  - Idle phases
  - Turning (rotation)
    
- Outputs files in:
  - `.json` format
  - `.csv` format (for Excel/data analysis)
- Structured with timestamps and sensor values



Tech Stack

- Node.js
- [`fast-csv`](https://www.npmjs.com/package/fast-csv) – CSV export
- Native `fs` module – File writing



Data Structure

Each data point contains:

json
{
  "timestamp": "2025-06-15T10:00:00.000Z",
  "latitude": 37.7745,
  "longitude": -122.4192,
  "acceleration": 1.34,
  "rotation": 15.6
}

Install dependencies
npm install
