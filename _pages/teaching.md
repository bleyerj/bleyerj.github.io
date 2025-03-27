---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
# toc: true
---

{% include base_path %}
{% include toc %}

## At Ecole des Ponts

### PhD level course *Numerical tools for automating non-linear computational mechanics simulations* (3h)

<p><i class="fa fa-person-chalkboard"></i><a href="Bleyer_advanced_computational_methods_2025.pdf"><b> Slides</b></a></p>

This lecture is part of the lecture series on *Advanced computational methods in mechanics* coordinated by Julien Yvonnet (Université Gustave Eiffel) for the SIE doctoral school.

------------------------------------------------

### Finite-element method for civil engineering

I am currently teaching a course on the Finite Element Method with a total of 32 hours. In this class, I aim to foster a critical perspective in interpreting numerical results. For this purpose, I have created a pedagogical finite-element Python package, called `wombat`, which uses an Object-Oriented Programming structure and helps students understand the fundamentals of finite-element formulation (small strain linear elasticity for trusses, beams and solid elements, modal and transient dynamic analysis, linear buckling and material non-linearities).

The class finishes with numerical projects in which students are proposed to implement a new finite-element based on the developments presented during the class. Such projects are also a good occasion for them to approach slightly more advanced concepts of structural mechanics. Typical project topics are:

- quadrangular elements and shear locking issues
- Timoshenko beam elements (shear locking)
- axisymmetric solid elements
- cylindrical shell elements
- planar grid elements (bending/torsion coupling)
- cross-section mechanical characteristics of beams

--------------------------------------------------------------------

### Damage mechanics

Since 2020, I am co-responsible for a class on *Damage mechanics* at the Master 2 level ($\approx$ 80 students), jointly accredited by Sorbonne Université and Ecole des Ponts ParisTech. This course aims at:

- providing the theoretical foundation of damage mechanics for quasi-brittle materials, in particular regarding the formulation of macroscopic constitutive behaviours coupling elasticity and damage;
- studying the problematic of initiation and evolution of damage in a numerical setting in order to investigate the ill-posedness of local damage models;
- proposing an outlook towards regularization methods though gradient damage models.

I share this responsibility with Kim Pham (ENSTA), formerly with Djimédo Kondo (SU), who delivers the first 9 hours on the theoretical basis through the thermodynamical framework of irreversible processes. In the next 9 hours, I introduce the students to the numerical aspects of an isotropic local damage model in the FEniCS environment. The students are then exposed to classical issues such as mesh-dependency in order to illustrate the ill-posed character of such models. I then give an introduction to regularizing formulations using damage gradient (phase-field) approaches. Finally, we study the corresponding numerical implementation and how this strategy succeeds, or not, in regularizing the problem of crack propagation in brittle materials.



## at Ecole Polytechnique

Since 2020, I am an Associate Professor (*Professeur chargé de cours d'exercice incomplet*) at \'Ecole Polytechnique in the Departement of Mechanics. Currently, I am teaching in:

- MEC430: *Structural Mechanics*, coordinated by Basile Audoly (40h, 40 students)
- MEC431: *Solid Mechanics*, coordinated by Patrick Le Tallec, formerly Oscar Lopez-Pamies (40h, 40 students)

Before that, I have also been mentoring experimental project in civil engineering with Gilles Forêt (Navier, ENPC) between 2018 and 2020.

## Executive Master in Digital Twins for Infrastructures & Cities

The [Executive Master in Digital Twins](https://www.digitwin4ciue.eu/master-digital-twins) has been co-funded by the EU and is delivered by [Universidad Politécnica de Madrid](https://www.upm.es/internacional), [École Nationale des Ponts et Chaussées](https://ecoledesponts.fr/en), [Budapesti Műszaki és Gazdaságtudományi Egyetem](https://www.bme.hu/?language=en) and [Istanbul Technical University](https://www.itu.edu.tr/en/homepage).

The program provides comprehensive training in the key digital technologies used in digital twins for infrastructures, the ability to conceive digital twins to address specific challenges in infrastructure planning, design, construction, operation, and management, and the skills to identify business opportunities created by digital twins.

I am involved in the Academic Board and was Acting Scientific Director of the program in 2023. I am now in charge of the Master's Conference Cycle, see our Youtube Channel for past events:

<iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?si=5BmmpN5rYzMW2j33&amp;list=PLH4enoRy_41wDseAUBkjDYuFDdMGSKX-w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## Past teaching activities

In the past, I have also been a teaching assistant for different courses at ENPC:

- 2014--2015 and 2017--2019 : *Solid Mechanics* supervised by L. Dormieux, 1st year engineering degree at ENPC, 85h/year.
- 2011--2015 and 2017--2019 : *Plasticity and Yield design* supervised by P. de Buhan, 2nd year engineering degree at ENPC, Civil Engineering Department, 40h/year.
- 2012--2015 : *Homogenization in yield design* supervised by P. de Buhan, master 2 level, ENPC, 20h/year.
- 2012, 2014, 2015 : *Refresher course in Solid Mechanics*, supervised by P. de Buhan, 2nd year engineering degree at ENPC, Civil Engineering Department, 20h/year.
- 2011 : *Mechanics of materials and structures at finite strains* supervised by P. de Buhan, master 2 level, ENPC, 20h/year.

During my postdoctoral leave in 2016, I was also a teaching assistant for the *Continuum Mechanics* course at EPFL (3rd year Bachelor), supervised by Jean-François Molinari (30h/year).
