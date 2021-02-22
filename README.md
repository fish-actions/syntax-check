# syntax-check [![license_badge][]][license]

A simple action to run syntax checking on all fish files in your repository.

## Usage

```yml
  syntax-check:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v2

      - uses: fish-actions/install-fish@v1

      - uses: fish-actions/syntax-check@v1
```

[license_badge]: https://img.shields.io/github/license/fish-actions/syntax-check
[license]: LICENSE.md
