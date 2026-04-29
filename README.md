# Student HPO Study

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sabri-manai/user-study-cf-hpo-xai/blob/main/user_study_notebook.ipynb)

This repository contains the materials for the HPO user study.

## Repository Contents

- `user_study_notebook.ipynb` - Google Colab notebook.
- `surrogate_ready_dataset/patchcore_surrogate_dataset_xgb.csv` - study dataset used by the notebook.
- `requirements.txt` - Python packages required by the notebook.

## Workflow

Students complete the notebook tasks in order:

1. `task_1` - choose one valid configuration.
2. `task_2` - choose one valid base configuration.
3. `task_3` - choose a what-if alternative based on `task_2`.

The final notebook cell validates the answers and saves the results to:

- `student_baseline_outputs/student_baseline_answers.csv`
- `student_baseline_outputs/student_baseline_answers.json`
