## What changed
- Briefly summarize the code changes made in this PR.
- Added sanity.py to check Python environment and installed packages.

## Why
- Explain why these changes were necessary.
- To make it easy for reviewers to verify environment setup quickly.

## How to test
1. Activate virtual environment:
   - Windows: `source .venv/Scripts/activate`
2. Install dependencies: `pip install -r requirements-prework.txt`
3. Run script: `python scripts/sanity.py`
4. Confirm the expected output matches Python version, platform, working directory, and installed packages.

## Checklist
- [ ] Tests added or updated if behavior changed
- [ ] README updated if behavior changed
- [ ] No debug code left in
