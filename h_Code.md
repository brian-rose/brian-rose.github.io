---
title: Shareables
permalink: code/
profile: true
layout: page
---

If you use my codes or find anything here useful in your own work, I would appreciate hearing about it by email.

## climlab: a Python-based toolbox for process-oriented climate modeling

My code is now hosted on github: <https://github.com/brian-rose/climlab.git>

This is a growing project, connected to my undergraduate course [A ATM / A ENV 415 Climate Laboratory]({{ site.baseurl }}/classes/ENV480_Spring2014), and my graduate course [A ATM 623 Climate Modeling]({{ site.baseurl }}/clases/ATM623_Spring2015).

There are currently three major components to this toolkit: code for insolation (including lookup tables for past orbital parameters), 1D column radiative-convective models, and 1D diffusive energy balance models. I expect functionality of the toolkit to increase rapidly, so please check the github page for the latest releases.

A growing collection of tutorials and example scripts in the form of IPython notebooks is distributed with the climlab code.
See also [my course notes for ATM 623](http://nbviewer.ipython.org/github/brian-rose/ClimateModeling_courseware/blob/master/index.ipynb)

## Matlab code for an equilibrium Energy Balance Model
The 1D diffusion equation model described in [Rose et al. (2014) GRL]({{ site.baseurl }}/resources/Publications/Rose_etal_GRL2014.pdf), with spatially varying radiative feedback and diffusion of moist static energy. Included data files give fits to the CAM4 aquaplanet GCM simulations. Code is included to reproduce Fig. 4 from Rose et al. (2014). 
The code uses [bvp4c.m](http://www.mathworks.com/help/matlab/ref/bvp4c.html) to solve the energy balance boundary value problem.

[MoistEBM.zip]({{ site.baseurl }}/resources/Code/MoistEBM.zip)

## History of climate science 
Here are slides for a presentation on the history of climate science that I first gave at MIT in January 2008:
[Looking Back on the Future of Climate Change]({{ site.baseurl }}/resources/LookingBackOnClimate.pdf)

A better and deeper discussion of the history of the CO2-climate connection was given by [Ray Pierrehumbert in his 2012 Tyndall Lecture at AGU](http://fallmeeting.agu.org/2012/events/tyndall-lecture-gc43i-successful-predictions-video-on-demand/)

And here is an interesting essay on [Gilbert Plass’s CO2 calculations and the surface budget fallacy](http://www.realclimate.org/index.php/archives/2010/01/plass-and-the-surface-budget-fallacy/) (also by Ray Pierrehumbert):

