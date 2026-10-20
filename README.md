# Week 3 starter

Practice repository for **Week 3: From Experiments to Observational Studies**.
Full instructions: <https://yoonismo.github.io/causal-computing/week3.html>

## What is in here

| File | Purpose |
|---|---|
| `week3.ipynb` | The code from the Week 3 page, in the same order |
| `requirements.txt` | The packages the automatic check installs |
| `.github/workflows/ci.yml` | The automatic check: runs the notebook on GitHub's computer after every push |

## Before you start

Week 3 uses the same packages as Week 2. If you have not installed them yet, activate the course environment and install them (this works from any folder):

```bash
source ~/ECON481/.venv/bin/activate      # macOS
~\ECON481\.venv\Scripts\activate          # Windows (PowerShell)
uv pip install pandas causaldata statsmodels
```

Run only the `activate` line for your system.

The notebook downloads its data from the internet, so you need a connection.

## Steps

1. Click **Use this template** → **Create a new repository**, then clone your copy to your computer, as in Week 1 Lab 3.
2. Run `week3.ipynb` in order along with the Week 3 page, and answer the questions in it. Each `# TODO` cell has a check cell right after it.
3. Clear all outputs, then `git add`, `git commit` and `git push`. The **Actions** tab should turn green.
