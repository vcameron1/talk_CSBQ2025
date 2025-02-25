# Estimer l'impact du milieu de la finance sur la biodiversité

Les entreprises ont un rôle de premier plan à jouer dans la crise de la biodiversité et doivent également faire partie de la solution. Des cadres internationaux tels que la Taskforce on Nature-related Financial Disclosures (TNFD) émergent avec l'objectif de divulguer les impacts et dépendances des investissements vis-à-vis la biodiversité. 
Dans la foulé de ces initiatives, des consultations ont été menées auprès d'investisseurs québécois et ont révélé l'absence d'indicateurs locaux. En réponse, l'Université de Sherbrooke, la SNAP Québec, Fondaction et la Caisse de dépôt et placement du Québec (CDPQ) se sont alliés pour développer un outil d'évaluation des risques pour la biodiversité spécifique au Québec. 
Guidés par les principes de la science ouverte et une expertise en sciences de la biodiversité, nous avons conçu neufs indicateurs d'impact dont le calcul peut être automatisé. Or, la littératie de la biodiversité s'est avérée parfois limitée chez les utilisateurs, ce qui pose des défis de communication. De plus, l'automatisation de l'évaluation des risques pour la biodiversité repose sur des données souvent peu disponibles. Finalement, les indicateurs de biodiversité globaux déjà établis se sont montrés moins pertinents en contexte local. 
Ces défis ont requis un processus de développement itératif et une collaboration étroite entre les experts en biodiversité et les utilisateurs. 
Pour illustrer notre démarche, nous présentons un exemple fictif où les considérations scientifiques et pratiques sont prises en compte ensemble dans la conception de l'indicateur d'impact sur la perte d'habitat. Dans cet exemple, la réserve naturelle du Mont-Bellevue, appartenant à l'université de Sherbrooke, est convertie en une mine. Nous détaillons la méthodologie de l'indicateur d'impact de la perte d'habitat sur la biodiversité locale, discutons des implications de cette perte et dégageons des perspectives.

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