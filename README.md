# Thesis Deepfake Experiment

Research and experiment framework for active defense against deepfake generation (e.g., DF-RAP, FaceShield) across social media platforms (Facebook, Instagram).

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
├── frameworks/          # Pinned official repositories (Git Submodules)
│   ├── DF_RAP/          ← https://github.com/ZOMIN28/DF_RAP.git
│   └── iccv25_faceshield/ ← https://github.com/kuai-lab/iccv25_faceshield.git
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
├── results/             # Analysis & visual results
└── scripts/             # Helper & preprocessing scripts
```

## Submodules Setup (Cloning / GPU Server)

If cloning on a new machine or GPU server:
```bash
git clone --recurse-submodules https://github.com/farhanibnmustafa/thesis-deepfake-experiment.git
```
Or if already cloned without submodules:
```bash
git submodule update --init --recursive
```
