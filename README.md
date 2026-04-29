# Student HPO Study Notebook

This folder contains the student-facing version of the HPO study.

## Files to Push

- `user_study_notebook.ipynb`: the notebook students open in Google Colab.
- `surrogate_ready_dataset/patchcore_surrogate_dataset_xgb.csv`: the study dataset.
- `requirements.txt`: Python packages used by the notebook.
- `.gitignore`: excludes local outputs and notebook cache files.

Do not push local virtual environments, generated answer files, or old research notebooks.

## After Pushing to GitHub

1. Open `user_study_notebook.ipynb`.
2. In the setup cell, replace:

```python
YOUR_USERNAME/YOUR_REPO
```

with your real GitHub repo path, for example:

```python
sabrine/my-student-hpo-study
```

3. Add this Colab badge to the top of this README after replacing the repo path:

```markdown
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/user_study_notebook.ipynb)
```

Students can then click the badge and run the notebook directly in Colab.

## Student Flow

Students complete the tasks in this order:

1. `task_1`: choose one valid configuration.
2. `task_2`: choose one valid base configuration.
3. `task_3`: choose a what-if alternative based on `task_2`.

The final notebook cell checks the answers and saves:

- `student_baseline_outputs/student_baseline_answers.csv`
- `student_baseline_outputs/student_baseline_answers.json`
