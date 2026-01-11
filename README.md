# Shrine Bowl Summer Sports Analytics Competition

Notebooks and data for identifying OL-DL 1v1 reps from Shrine Bowl practice tracking, engineering rep features (including contact onset), and computing evaluation metrics.

## Contents
- `RepIdentification/`: manual and automated rep-detection pipelines + visualization notebooks
- `FeatureEngineering/`: feature engineering, contact onset detection, matchup labeling, diagnostics
- `Metrics/`: metric exploration notebook and example GIFs
- `player_data/`: player metadata and stats
- `ManualTrackingValidation/`: manual labels for validation
- `Output/`: generated rep datasets and features

## Quick start
1. Install deps: `pip install polars numpy matplotlib ipywidgets scipy plotly`
2. Open the notebooks in Jupyter/JupyterLab/VS Code/your chosen fork.
3. Download practice parquets and update any hard-coded paths (some notebooks reference `~/Desktop/ShrineBowlSumerSportsAnalyticsCompetition`).
4. Suggested order: `RepIdentification/` -> `FeatureEngineering/` -> `Metrics/`
