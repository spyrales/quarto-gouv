# quarto-gouv
A Quarto extension for French governmental documents

The following formats have been implemented so far.

## Format: docx

The format `.docx` allows you to create a document with a letter layout compliant with the French Design System.

To use it, first create a file `<your-file>.qmd`. To help you fill it, you can have a look at the [template.qmd](./template.qmd) file. Then run the following command:

```bash
quarto render <your-file>.qmd --to quarto-gouv-docx
```

You can customise the rendering with [some parameters](https://quarto.org/docs/reference/formats/docx.html).