---
title: "Formulation stochastique des matériaux standards généralisés"
collection: talks
type: "Talk"
venue: "[Journées SMAI-MODE 2022](https://indico.math.cnrs.fr/event/6564/)"
date: 2024-05-14
location: "Université de Limoges, France"
slides: "../files/SMAI_MODE_2022.pdf"
excerpt: ""
---

La conception optimale des structures, en particulier l’optimisation topologique de systèmes continus, a connu de nombreux développements théoriques ainsi que numériques qui permettent d’imaginer des structures mécaniquement efficaces dans de nombreuses situations. La majorité de ces développements se sont en revanche concentrés sur la maximisation de la rigidité dans un contexte de matériau élastique. Or, ce type de comportement n’est pas forcément pertinent pour de nombreuses applications en ingénierie. On peut penser par exemple à l’optimisation de structures en maçonnerie ou en pierre pour lesquelles le matériau se déforme peu élastiquement et, surtout, ne supporte que des états de contrainte en compression. Dans d’autre situations telles que l’optimisation des renforts en acier dans les structures en béton armé par exemple, on cherche plutôt à maximiser la résistance maximale de la structure totale de la structure que sa raideur élastique.

Dans cette contribution, nous proposons une formulation de problèmes d’optimisation topologique cherchant à maximiser la résistance maximale de la structure, pour un volume maximal de matière donné. Nous abandonnons ici le comportement élastique au profit d’un domaine convexe correspondant au critère de résistance du matériau. Nous étendons ainsi les concepts de la théorie de l’analyse limite des structures parfaitement plastiques au domaine de l’optimisation topologique. Nous présentons également une formulation à plusieurs matériaux permettant d’optimiser plusieurs phases de propriétés différents (béton et acier par exemple). Nous montrons que le choix du critère de résistance s’avère déterminant et permet de représenter des matériaux n’ayant aucune résistance en compression ou d’induire des directions de renforcement privilégiées. Les développements numériques reposent sur une discrétisation par éléments-finis et une formulation comme problème d’optimisation conique, résolu à l’aide de solveurs de point-intérieur tel que Mosek par exemple.