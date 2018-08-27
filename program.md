---
layout: page
title: Program
---


## Workshop
* Start: Tuesday August 28th 2018 at 09:50
* Finish: Friday August 31st 2018 15:30

### Tuesday: CAP Symposium with CAP related talks in Room D-212

* 09:50 - 10:00: Welcome
* 10:00 - 12:00: Gutsche/Posur: *Introduction to CAP: Constructive category theory and applications*<br/>
> **Abstract:** In this talk we explain the concept of constructive category theory
> and its implementation in our software project
> CAP - Categories, algorithms, programming.
> Furthermore, we show the benefits of CAP's framework
> for constructive category theory
> by demonstrating
> some applications to homological algebra:
> diagram chasing via generalized morphisms
> and computing the purity filtration via spectral sequences.
* 12:00 - 13:00: Lunch
* 13:00 - 13:40: Skartsæterhagen: *CAP in QPA*
> **Abstract:** QPA ("Quivers and Path Algebras") is a GAP package for doing
> computations related to algebras defined by quivers and relations.  A
> substantial part of QPA's functionality deals with module categories
> over such algebras, and certain functors between these categories.
> The QPA package is currently undergoing a major rewrite where we try
> to make the code better structured and more consistent.  In the new
> version of QPA, we use the structures provided by CAP to represent
> categories and functors, replacing our earlier more ad hoc approaches.
> In this talk, I will give a brief introduction to QPA and show how we
> are using CAP in QPA. 
* 14:00 - 14:40: Bies: *CAP, machine learning and string theory*
> **Abstract:** The holy grail of *string theory* is to prove or disprove that a *string vacuum* furnishes a description of the
> physical universe that we are living in. A minimalistic check to tell if a *string vacuum* could match the
> experimental results from particle accelerators is to compute the *massless spectrum*. For a special class
> of *string vacua* -- the so-called *F-theory vacua* -- I will explain that this eventually leads to *cohomologies of coherent sheaves*.
> 
> The functionality of *CAP* extends far beyond *coherent sheaves*. However, the CAP-framework is perfectly suited
> for a modern implementation of coherent sheaves and their cohomologies.
> Indeed, much progress has been made on this subject during the last few years.
> Despite these successes, the required computations test the boundaries of these implementations
> in terms of computational time and power. To overcome these limitations, we are currently
> investigating if techniques from *machine learning* can help. I will conclude this talk with results on this work in progress.
> 
> (See [pdf]({{ site.baseurl }}/public/Abstract_Bies.pdf) for theoretical background)

* 15:00 - 15:30: Coffee and cake
* 15:30 - 16:10: Juteau: *Motives, algorithms and programming*
> **Abstract:** Following Francis Brown, I will explain why questions in number theory
> (irrationality of zeta values) make it desirable to be able to compute some mixed Tate
> motives of moduli spaces. Then I will explain an algorithm devised by Clément Dupont
> in his PhD thesis for that purpose, and its implementation in the package MotivesForBiarrangements which uses CAP.
* 16:30 - 17:10: Saleh: *Implementation of Quillen model categories*
> **Abstract:** This talk is meant to introduce the Quillen model
> categories. In short, model categories are used to give an effective
> construction of the localization of categories, where, similarly to localization of rings,
> the problem is to convert a class of morphisms, called weak-equivalences, into isomorphisms.
> 
> In the case of a model category, the localized category is identified with a homotopy category, a category
> whose morphism sets consist of equivalence classes of morphisms under a certain
> homotopy relation which is determined by the model structure.
> 
> We demonstrate this by constructing in Gap/CAP the derived category of some categories with finite global projective dimension,
> for example the category of finite left presentations over a polynomial ring or the category of representations of an acyclic
> quiver. 

### Wednesday: CAP Tutorial & Coding Sprint

#### CAP Tutorial in Room D-212

To prepare your computer for the tutorials, follow the instructions [here]({{site.baseurl}}/preparation).

* 10:00 - 13:00: *Computing with CAP*<br/>
In this tutorial we will show how to use CAP for (advanced) computations in homological algebra.
This includes computing with modules in CAP, and using CAP as as a categorical programming language.


* 14:00 - 17:00: *Implementing your own category*<br/>
In this tutorial you will learn how to implement a basic category in CAP.
We will start by using preexistent data structures for finite groups in GAP to implement a CAP category.
Afterwards, we will implement the abelian category of finite dimensional vector spaces over a constructive field
in CAP.

#### Coding Sprint in Room D-201

* 09:30: Stand-up: projects of the day
* 17:00: Stand-up: what did we achieve today?

### Thursday: Coding Sprint in Room D-212

* 09:30: Stand-up: projects of the day
* 17:00: Stand-up: what did we achieve today?

### Friday: Coding sprint in Room D-212

* 09:30: Stand-up: projects of the day
* 15:00: Stand-up: what did we achieve today?