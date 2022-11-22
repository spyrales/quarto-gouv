# quarto-gouv

[![Licence](https://img.shields.io/badge/Licence-EUPL--1.2-001489)](https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12)
![](https://github.com/spyrales/quarto-gouv/actions/workflows/ci_lettre-gouv-docx.yml/badge.svg)
![](https://github.com/spyrales/quarto-gouv/actions/workflows/ci_presentation-dinum-pptx.yml/badge.svg)

A [Quarto](https://quarto.org) extension for French governmental documents

## Licence

 This work is licenced under the [European Union Public Licence 1.2](https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12).

## Formats

The following formats have been implemented so far.

### Letters

- `lettre-gouv`: this format allows you to create a document with a letter layout compliant with the French Design System. Available extensions:
  - `docx`

### Presentations

- `presentation-dinum`: this format allows you to create a presentation compliant with the [DINUM](https://www.numerique.gouv.fr/dinum/) Design System. Available extensions:
  - `pptx`

### All formats

To use any of the available formats, you can follow these steps:

```bash
quarto use template spyrales/quarto-gouv
```

Then run the following command:

```bash
quarto render <your-file>.qmd
```

You can customise the rendering with [some parameters](https://quarto.org/docs/reference/formats/docx.html).