---
title: "Many-Body Approaches to Quantum Dots"
description: 'Simulating extremely tiny systems which follows the laws of Quantum Theory, with amazing properties and applications at our "macroscopic" scale!'
layout: minimal_publication
school: "University of Oslo"
journal: "Masters Thesis"
academic: true
file: Merlot - MSc - Computational_Physics.pdf
categories: "Academic, Computational Physics, Physics"
tags: "Academic, Computational Physics, Physics, Quantum Dots"
---

### Abstract

This thesis investigates numerically systems consisting of several interacting electrons in two-dimensions, confined to small regions between layers of semiconductors. These artificially fabricated electron systems are called "quantum dots" in the literature.
Quantum dots provide a new challenge to theoretical calculations of their properties using many-body methods. The size of these "artificial atoms" is several orders of magnitude larger than that of atoms, leading to a much greater sensitivity to magnetic fields. The full many-body problem of quantum dots is truly complex and simulating a quantum dot constrained by a magnetic field may be even more complicated.

Of particular interest is the reliability of the Hartree-Fock (HF) method for studies of quantum dots in 2D as a function of the external magnetic field.
An Hartree-Fock code for electrons trapped in a single harmonic oscillator potential in two-dimensions has been developed, as well as a code implementing many-body perturbation theory (MBPT) up to third order either directly applied to the harmonic oscillator basis or as a correction to the Hartree-Fock energy. A discussion of the results compared with large-scale diagonalisation methods indicated a quadractic error growth of HF and MBPT as the interaction strength increases.

The reliability of a single Slater determinant approximation for the ground state of closed shell systems as function of varying interaction strength has been investigated and we found that the Hartree-Fock method, compared with large-scale diagonalization methods, has a limited range of applicability as function of the interaction strength and increasing number of electrons in the dot, indicating a break of the computational technique before entering the limit of validity of the closed-shell model. 

### Presentation

* [pdf format](http://folk.uio.no/patrime/src/slides.pdf)

### C++ Simulator archive

* [QDot](http://folk.uio.no/patrime/src/qdot.tar.gz)

### Citation

    @mastersthesis{
        author = {Merlot, Patrick},
        title = {Many-Body Approaches to Quantum Dots},
        school = {University of Oslo},
        year = {2009},
        keywords = {Hartree-Fock,Many-body methods,Many-body systems,Quantum dots},
        pages = {127},
        url = {http://urn.nb.no/URN:NBN:no-26083}
    }
