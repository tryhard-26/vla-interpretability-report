# VLA Interpretability Report

Interactive mechanistic interpretability report for Vision-Language-Action policies (SmolVLA).

## Report Contents

This repository contains the complete standalone interactive evaluation report (`index.html`) along with all physical MuJoCo simulation frames, rollout recordings, cross-modal attribution heatmaps, and Causal Language-Action Jacobians.

## Viewing the Report

You can view the interactive report using either of the methods below:

### Method 1: Direct Browser Opening

Open `index.html` directly in any modern browser:

```bash
open index.html
```

### Method 2: Local HTTP Server

Serve the directory locally using Python:

```bash
python3 -m http.server 8000
```

Then navigate to `http://localhost:8000` in your web browser.

## Sections Included

1. Executive Technical Summary: Pipeline Flow and Empirical Interpretation
2. Empirical MuJoCo Studio: Interactive Scrubber, Token Saliency, Action Gauges, and Causal Jacobians
3. Video Proof Suite: High-Definition Rollout Recordings
4. Paired Quad-Proof Matrix: Visual, Language, Action, and Policy Attributions
5. 6-DoF Tri-Modal Synthesis: Cross-Modal Decomposition
6. Causal Jacobians: Linguistic Motor Sensitivity
7. Temporal Chunk Saliency: 5-Phase Semantic Migration
8. Spatial Cross-Attention: Visual Grounding and Background Leakage
9. Flow Velocity Steering: Linear Latent Trajectory Modulation
10. Adversarial Robustness: Bounded Perturbation and Elevation Collapse
