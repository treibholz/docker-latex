# docker-latex
for Latex CI

This can be used e.g. for gitlab-ci

## Example
```yaml
buildpdf:
  image: treibholz/latex
  script:
    - latexmk -pdf main.tex
  artifacts:
    paths:
      - main.pdf
```
