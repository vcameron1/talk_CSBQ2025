# bq_markdown_template

Gabarit de présentation RMarkdown qui répond aux exigeances de l'image de marque de Biodiversité Québec

## Installation

Le gabarit peut être installé depuis GitHub en utilisant la commande suivante.

```
git clone https://github.com/BiodiversiteQuebec/bq_markdown_template.git
```

## Utilisation

Utiliser le gabarit `bq_markdown_template.Rmd` pour produire une présentation en format HTML ou PDF.

Pour convertir la présentation en format HTML.

```
Rscript -e "rmarkdown::render('bq_markdown_template.Rmd')"
```

Pour convertir la présentation en format PDF.

```
Rscript -e "options(pagedown.remote.maxattempts=40); pagedown::chrome_print('bq_markdown_template.html',output='bq_markdown_template.pdf')"
```

## Signature visuelle

![Exemple de présentation](bq_markdown_template.pdf)