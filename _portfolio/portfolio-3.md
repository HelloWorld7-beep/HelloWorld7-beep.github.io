---
title: "Forward Scattering for Thin Coated Domains: Numerical Solution Using Generalized Impedance Boundary Conditions"
excerpt: "Undergraduate REU research project on wave scattering and GIBC modeling<br/><img src='/images/scattering_poster.jpg' style='width:350px; height:auto;'>"
collection: portfolio
---

### May 2024 – July 2024

**Principal Investigator:** Dr. Carlos Borges  
**Institution:** University of Central Florida  
**Department:** Mathematics  

---

## Research Focus

This project aimed to develop a more efficient **numerical solver** for the **forward scattering problem** involving objects with thin coatings.  
In this context, *forward scattering* refers to predicting how waves are scattered when they strike an **impenetrable obstacle** covered by a **thin, penetrable layer**.  

Such problems have important practical applications, including:
- **Radar stealth technology** through coating design  
- **Optical engineering**, such as designing thin films for lenses to modify light transmission and reflection  

The goal was to simplify and accelerate the computation of these wave interactions while preserving high accuracy.

---

## Responsibilities

At the start of the research, I conducted a **literature review** to understand the mathematical background of the project and presented my findings to **Dr. Borges** and my REU partner.  
Throughout the program, we also attended **seminars and workshops** in computational mathematics to strengthen our theoretical foundation.

For the core of the project, we modified existing **MATLAB code** that solved the forward scattering problem for impenetrable objects.  
To model thin coatings efficiently, we replaced the complex **transmission problem** with a simplified approach using **Generalized Impedance Boundary Conditions (GIBCs)**.

These GIBCs approximate how waves behave as they pass through thin layers by converting the internal wave equations into simpler boundary conditions on the object’s surface.  
We implemented GIBCs of **orders 1 and 2**, testing their ability to reproduce the results of the true transmission problem.  
Our findings showed that **second-order GIBCs** provided an almost perfect approximation while remaining computationally efficient.

Finally, we presented our results in a **poster symposium at the University of Central Florida**.

---

### My Research Poster

_By me_

![Wave Scattering Research Poster](/images/scattering_poster.jpg)
