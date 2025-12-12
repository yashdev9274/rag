# RAG Project

## Setup Local Environment

1. **Activate the environment**:
   ```bash
   source .venv/bin/activate
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run Jupyter**:
   ```bash
   jupyter lab
   ```

## Sync with Colab

**Local to Colab**:
1. Save changes in Jupyter.
2. Commit and push to GitHub:
   ```bash
   git add .
   git commit -m "Update notebook"
   git push origin main
   ```
3. Open the notebook in Colab via the GitHub tab.

**Colab to Local**:
1. In Colab, go to **File > Save a copy in GitHub**.
2. Pull changes locally:
   ```bash
   git pull origin main
   ```
