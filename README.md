**UPDATE**: The template was made available on the official website of the University's Library: [here](http://bibliotheques.u-bordeaux.fr/Soutien-a-la-recherche/Theses-et-memoires-numeriques/These-de-doctorat/Rediger-sa-these-de-doctorat) and [there](https://bibliotheques.u-bordeaux.fr/Soutien-a-la-recherche/Theses-et-memoires-numeriques/These-de-doctorat/Deposer-sa-these-de-doctorat).

# Unofficial LaTeX template for PhD thesis of the University of Bordeaux

The cover page and the abstract page have a more restricted formatting and can be hard to come up to.
Here are models of these LaTeX pages that comply with the UB recommendations. I wrote them for my own PhD in 2019 in absence of any Latex official templates.
They are compiled with the `pdflatex` command.
These pages, once compiled in PDF, can be included in a PhD thesis manuscript with the following command:
```{latex}
\includepdf[pagecommand={\thispagestyle{empty}}]{page_garde.pdf}
\includepdf[pagecommand={\thispagestyle{empty}}]{page_resume_FR_ENG.pdf}
```

Assuming that the following library has been loaded:
```{latex}
\usepackage{pdfpages}
```


# Modèle LaTeX non officiel pour les thèses de doctorat de l'Université de Bordeaux

La page de couverture et la page du résumé ont un formatage plus restreint et peuvent être difficiles à réaliser. Voici des modèles de ces pages LaTeX conformes aux recommendations de l'UB.  Je les ai écrites pour ma propre thèse de doctorat en 2019 en l'absence de tout modèle officiel en LaTeX.
Elles se compilent avec la commande `pdflatex`.
Ces pages, une fois compilées en PDF, peuvent être inclus dans un manuscrit de thèse avec la commande suivante :

```{latex}
\includepdf[pagecommand={\thispagestyle{empty}}]{page_garde.pdf}
\includepdf[pagecommand={\thispagestyle{empty}}]{page_resume_FR_ENG.pdf}
```

Sous réserve d'avoir chargé la librairie suivante :
```{latex}
\usepackage{pdfpages}
```
