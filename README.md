# Drone Reconstruction Viewer

An interactive side-by-side comparison viewer between raw drone flight footage and 3D photogrammetry/reconstruction models.

## Live Assets
Assets are hosted on Hugging Face:
- **Video**: [flight.MP4](https://huggingface.co/exoticsuryaa/drone-reconstruction-assets/resolve/main/flight.MP4)
- **3D Model**: [reconstruction.glb](https://huggingface.co/exoticsuryaa/drone-reconstruction-assets/resolve/main/reconstruction.glb)

## Running Locally

```bash
# Start a local static server
python -m http.server 8000
```
Open `http://localhost:8000/index.html` in your web browser.
