# Drone Reconstruction Comparison Viewer

An interactive side-by-side viewer comparing drone flight video with 3D photogrammetry/reconstruction models.

## Setup & Running Locally

1. Place your assets in the respective folders:
   - **Video**: `data/flight.mp4` (or configure path in `index.html`)
   - **3D Model**: `models/reconstruction.glb` (or configure path in `index.html`)
2. Start a local HTTP server (required for loading GLB models via `model-viewer` due to CORS):
   ```bash
   # Using Python:
   python -m http.server 8000
   ```
3. Open `http://localhost:8000/index.html` or `http://localhost:8000/1.html` in your web browser.

## Note on Media & 3D Assets
Due to large file sizes, raw video files and 3D `.glb` model files are ignored from git tracking.
