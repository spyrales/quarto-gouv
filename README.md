# quarto-gouv

[![Licence](https://img.shields.io/badge/Licence-EUPL--1.2-001489)](https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12)

A Quarto extension for French governmental documents

## Licence

 This work is licenced under the [European Union Public Licence 1.2](https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12).

## Formats

The following formats have been implemented so far.

### docx

The format `.docx` allows you to create a document with a letter layout compliant with the French Design System.

To use it, first create a file `<your-file>.qmd`. To help you fill it, you can have a look at the [template.qmd](./template.qmd) file. Then run the following command:

```bash
quarto render <your-file>.qmd --to quarto-gouv-docx
```

You can customise the rendering with [some parameters](https://quarto.org/docs/reference/formats/docx.html).
