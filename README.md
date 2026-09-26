# zizmor pre-commit hook

pre-commit hook of zizmor with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For zizmor: see [here](https://github.com/danyeaw/pre-commit-mirrors-zizmor)

## Using zizmor with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/danyeaw/pre-commit-mirrors-zizmor
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: zizmor-conda
```
