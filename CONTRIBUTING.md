# Contributing

Thanks for your interest in improving this survey and analysis project! Here’s how you can help:

## Ways to contribute
- Improve data cleaning and validation rules
- Add new visualizations or statistical summaries
- Extend sentiment/thematic analysis for open feedback
- Enhance the presentation deck with clearer storytelling
- Improve documentation and reproducibility

## Getting started
1. Fork the repository and create a feature branch.
2. Create a virtual environment and install dependencies:
   - `pip install -r requirements.txt`
3. Run the notebook in `notebooks/analysis.ipynb` or the script `scripts/clean_and_analyze.py`.
4. Add or update tests/notebook assertions where relevant.
5. Open a PR with a clear description and screenshots of key results.

## Code style
- Python: follow PEP8, use type hints where practical.
- Keep notebooks clean (restart + run all before committing).
- Commit meaningful changes; avoid committing huge intermediate artifacts.

## Data ethics
### Data safety
- Do not upload any raw or cleaned survey data to the repository or PRs.
- Keep raw exports (Excel/CSV) local. The `.gitignore` excludes common data formats and the `data/` folder.
- Ensure all visualizations respect respondent anonymity; avoid very small groups that could reveal identities.
- If you accidentally committed sensitive files, contact the maintainer to remove them and consider a history rewrite.

### Tests & examples
- Tests use synthetic in-memory dataframes; no real data is required.
- If you contribute examples, ensure they are fully synthetic.

Thank you for contributing!
