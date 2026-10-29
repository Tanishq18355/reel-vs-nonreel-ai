# Reel vs Non-Reel AI Traffic Classification

A Python project exploring machine-learning-based classification of network traffic into video-based ("reel") and non-video ("non-reel") categories.

## Overview

The goal of this project is to explore how network traffic characteristics can be used to distinguish video-oriented activity from other browsing or messaging activity. The repository is organized into separate Python modules for the main application, network monitoring, and model management.

The actual classification performance depends on the model, input features, and data used.

## Project Structure

```text
reel-vs-nonreel-ai/
├── app.py                  # Main application entry point
├── model_manager.py        # Model management
├── network_monitor.py      # Network monitoring
├── requirements.txt        # Python dependencies (if present)
├── README.md               # Project documentation
├── .gitignore
└── LICENSE
```

## Technology

- Python
- Machine Learning: Random Forest (as described in the project)
- Network traffic monitoring concepts

The exact dependencies, model artifacts, input features, and runtime behavior should be confirmed against the current source code.

## Getting Started

### Prerequisites

- Python 3.10 or a compatible version supported by the project dependencies
- Git
- The dependencies listed in `requirements.txt`, if available

### Installation

Clone the repository:

```bash
git clone https://github.com/Tanishq18355/reel-vs-nonreel-ai.git
cd reel-vs-nonreel-ai
```

Create and activate a virtual environment:

```bash
python -m venv .venv
```

Windows:

```bash
.venv\Scripts\activate
```

macOS/Linux:

```bash
source .venv/bin/activate
```

If `requirements.txt` exists and is complete, install the dependencies:

```bash
pip install -r requirements.txt
```

### Running the Application

Inspect the configuration and dependencies before running:

```bash
python app.py
```

The available commands, required model files, network permissions, and expected inputs depend on the current implementation.

## Project Modules

### `app.py`

The main application entry point. Its actual responsibilities, available endpoints, and prediction workflow should be documented after reviewing the source code.

### `network_monitor.py`

The module intended to handle network monitoring. The traffic capture method, extracted features, and required permissions need to be verified in the implementation.

### `model_manager.py`

The module intended to manage the machine-learning model. Model loading, saving, training, and versioning capabilities should be documented only if they are implemented.

## Current Limitations

- The availability of a trained model and its training dataset must be verified.
- Classification accuracy has not been stated because a verified evaluation result is not documented here.
- Real-time traffic capture, API endpoints, and adaptive network optimization require implementation-level verification.
- Results depend on the quality and suitability of the input data and model features.

## Future Improvements

- Document the dataset and feature extraction pipeline.
- Add reproducible model training and evaluation.
- Test predictions on representative data and report appropriate evaluation metrics.
- Add automated tests for core functionality.
- Add a dashboard for visualizing predictions if supported by the application.
- Investigate integration with network optimization systems.

## License

This project is distributed under the MIT License. See [LICENSE](LICENSE) for details.

