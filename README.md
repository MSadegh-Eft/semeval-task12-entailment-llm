# SemEval-2026 Task 12: Entailment Recognition

**Competition solution** for SemEval 2026 Task 12 on natural language entailment.
Includes baseline, transformer fine-tuning, and comprehensive error analysis.

Built for an Advanced NLP course assignment.

## What this project covers

- Task 12 dataset loading and preprocessing
- Baseline rule-based classifier
- Fine-tuned transformer models
- Cross-validation and hyperparameter search
- Error analysis and model comparison

## Project layout

| Path | Description |
|------|-------------|
| `main.ipynb` | Complete solution and evaluation |
| `semeval-dataset/` | SemEval Task 12 data |
| `Project.pdf` | Project description |
| `Report.pdf` | Final report |
| `requirements.txt` | Dependencies |

## Quick start

```bash
python -m venv .venv
.venv\\Scripts\\activate          # macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook main.ipynb
```

Notebook outputs are saved and render on GitHub.
