# LegacyFixer post-fix tests demo

This repository is used to test LegacyFixer's post-fix test gate.

Expected behavior:

- LegacyFixer detects vulnerable Python dependencies in requirements.txt
- pip-audit creates a dependency fix
- post-fix tests are enabled
- npm ci and npm test pass
- LegacyFixer opens a reviewable pull request
