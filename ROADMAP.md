# Roadmap

Task tracking and plan for TranscodeFlow development. Estimated workload ~25h.

## Part 1: Core + Hardware detection
- [ ] Add Hardware encoder detection (such as NVENC, QuickSync...).
- [ ] Implement FFprobe media analysis and passthrough logic.
- [ ] Add VMAF quality probing engine.

## Part 2: Job queue system
- [ ] Create asynchronous job queue with concurrency limit based on hardware allowed usage.
- [ ] Develop rule-based routing engine.
- [ ] Setup telemetry features.

## Part 3: Web Dashboard
- [ ] Setup base UI layout and log viewer
- [ ] Create pipeline editor and some presets.
- [ ] Add history and analytics panel.

## Part 4: Packaging and Deployment
- [ ] Prepare dedicated dockerfile with FFmpeg + GPU acceleration support
- [ ] Create docker template with volume mapping for local/NAS paths, to deploy the app easily.
