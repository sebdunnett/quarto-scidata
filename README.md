# *Scientific Data* Data Descriptor template

This is a Quarto template that assists you in creating a Data Descriptor for [*Scientific Data*](https://www.nature.com/sdata/). You can learn more about publishing with *Scientific Data* on their [For Authors](https://www.nature.com/sdata/author-instructions) webpage.

## Creating a new article

To start, use the following command:

```bash
quarto use template sebdunnett/quarto-scidata
```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```bash
quarto install extension sebdunnett/quarto-scidata
```

## Usage

To use the format, you can use the format names `scidata-pdf` and `scidata-html`. For example:

```bash
quarto render article.qmd --to scidata-pdf
```

or in your document yaml

```yaml
format:
  html: default
  scidata-pdf:
    keep-tex: true    
```

You can view a preview of the rendered PDF template at <https://sebdunnett.com/quarto-scidata/>.
