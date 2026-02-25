# CSV Profiler Usage

Run the CLI to profile a CSV and produce a Markdown report.

Example:

```bash
python -m profiler.cli path/to/data.csv -o profile.md --top 5
```

This will write `profile.md` with per-column metrics including null counts, duplicates, distinct counts, min/max, mean/median/std (for numeric), most frequent values, and inferred data types.

Install requirements first:

```bash
pip install -r requirements.txt
```
