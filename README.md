# Elixir Actions

This repository hosts reusable GitHub Actions workflows for the Elixir language.

## Usage

Add to your existing workflow definition:

```yml
jobs:
  lint:
    name: Code linting
    uses: lexmag/elixir-actions/.github/workflows/lint.yml@v2
    with:
      otp-version: "24"
      elixir-version: "1.14"
```
