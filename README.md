# Thesis Deepfake Experiment

Research and experiment framework for active defense against deepfake generation (e.g. DFRAP, FaceShield) across social media platforms (Facebook, Instagram).

## Directory Structure

```text
thesis-deepfake-experiment/
├── automation/          # Automation scripts
├── datasets/            # Datasets (pilot & main)
│   ├── main/
│   └── pilot/
├── deepfake/            # Deepfake generation algorithms
│   ├── diffusion/
│   └── gan/
├── logs/                # Execution & experiment logs
├── metrics/             # Evaluation metrics
├── platform/            # Platform roundtrip experiments
│   ├── cross/
│   │   ├── fb_ig/
│   │   └── ig_fb/
│   ├── facebook/
│   │   ├── r1/
│   │   └── r2/
│   └── instagram/
│       ├── r1/
│       └── r2/
├── protected/           # Protected face images
│   ├── dfrap/
│   └── faceshield/
└── results/             # Analysis & visual results
```
