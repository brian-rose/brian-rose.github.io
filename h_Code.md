---
title: Shareables
permalink: code/
profile: true
layout: page
---

If you use my codes or find anything here useful in your own work, I would appreciate hearing about it by email.

## AMS Tools of the Trade presentation: Reproducible workflows with Jupyter notebooks

In January 2018 I gave an invited presentation at the Tools of the Trade session of the AMS Student Conference, where I discussed the use of the Jupyter notebook and other Python-based tools for open and reproducible workflows in atmospheric sciences. All the material is available online:

- Video of the presentation is [available from AMS](https://ams.confex.com/ams/98Annual/videogateway.cgi/id/42749?recordingid=42749)
- The example notebooks are [on github](https://github.com/brian-rose/ToolsOfTheTrade2018_JupyterNotebooks)
- My slides are available [here](https://www.dropbox.com/s/lh9mic4p1vgqb1r/Rose_Jupyter.pptx?dl=0)


## climlab: a Python-based toolbox for process-oriented climate modeling

My code is now hosted on github: <https://github.com/brian-rose/climlab.git>

This is a growing project, funded through my NSF CAREER award and connected to my undergraduate course [A ATM / A ENV 415 Climate Laboratory]({{ site.baseurl }}/classes/ENV415_Spring2018), and my graduate course [A ATM 623 Climate Modeling]({{ site.baseurl }}/clases/ATM623_Spring2017).

A bunch of `climlab`-related resources:

- The [source code on github](https://github.com/brian-rose/climlab)
- The [online documentation](http://climlab.readthedocs.io/en/latest/)
- Lecture notes for ATM 623: Climate Modeling in Jupyter notebook format:
  - [Notebooks hosted on github](https://github.com/brian-rose/ClimateModeling_courseware)
  - [Rendered as static web pages](http://nbviewer.jupyter.org/github/brian-rose/ClimateModeling_courseware/blob/master/index.ipynb) (using nbviewer)
  - [Run interactively in the cloud!](https://mybinder.org/v2/gh/brian-rose/ClimateModeling_courseware/master) (using Binder)
- [Video from a presentation about `climlab`](https://ams.confex.com/ams/98Annual/videogateway.cgi/id/44948?recordingid=44948) at the AMS Python symposium (January 2018)


## Matlab code for an equilibrium Energy Balance Model
The 1D diffusion equation model described in [Rose et al. (2014) GRL]({{ site.baseurl }}/resources/Publications/Rose_etal_GRL2014.pdf), with spatially varying radiative feedback and diffusion of moist static energy. Included data files give fits to the CAM4 aquaplanet GCM simulations. Code is included to reproduce Fig. 4 from Rose et al. (2014).
The code uses [bvp4c.m](http://www.mathworks.com/help/matlab/ref/bvp4c.html) to solve the energy balance boundary value problem.

[MoistEBM.zip]({{ site.baseurl }}/resources/Code/MoistEBM.zip)

## History of climate science
Here are slides for a presentation on the history of climate science that I first gave at MIT in January 2008:
[Looking Back on the Future of Climate Change]({{ site.baseurl }}/resources/LookingBackOnClimate.pdf)

A better and deeper discussion of the history of the CO2-climate connection was given by [Ray Pierrehumbert in his 2012 Tyndall Lecture at AGU](https://youtu.be/RICBu_P8JWI)

And here is an interesting essay on [Gilbert Plass CO2 calculations and the surface budget fallacy](http://www.realclimate.org/index.php/archives/2010/01/plass-and-the-surface-budget-fallacy/) (also by Ray Pierrehumbert):
