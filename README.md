# bq_markdown_template

Gabarit de présentation RMarkdown qui répond aux exigeances de l'image de marque de Biodiversité Québec

## Installation

Le gabarit peut être installé depuis GitHub en utilisant la commande suivante.

```
git clone https://github.com/BiodiversiteQuebec/bq_markdown_template.git
```

## Utilisation

Pour produire une présentation en format HTML.

```
Rscript -e "rmarkdown::render('bq_markdown_template.Rmd')"
```

Pour produire une présentation en format PDF.

```
Rscript -e "options(pagedown.remote.maxattempts=40); pagedown::chrome_print('presentation.html',output='presentation.pdf')"
```