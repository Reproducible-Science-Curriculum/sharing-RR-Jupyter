---
title: Introduction to Binder
teaching: 10
exercises: 10
questions:
- How can we share Jupyter Notebook so they are interactive, can be run, and modified?
- What does it mean for code to "depend" on software?
- How can we explicitly define the dependencies for our code?
objectives:
- Create a shareable interactive binder for your online Jupyter notebooks.
- Create a requirements file listing dependencies for the notebooks in your repository.
keypoints:
- Binder provides an environment that runs and interactively serves your Jupyter notebooks.
- Use `requirements.txt` to specify dependencies beyond the Jupyter notebook execution environment itself. Typically, this will at least be any package you `import` in your Python code.
---

# Sharing an interactive repository with Binder

**Authors: Chris Holdgraf, M Pacer**

* [Slideshow]({{ page.root }}/slides/02-intro_to_binder.slides.html)
* Simple sample notebook:
    - [download](../code/hello_world_binder.ipynb)
    - [on Github]({{ site.repository }}/blob/gh-pages/code/hello_world_binder.ipynb)
* Sample notebook with plotting:
    - [download](../code/plot-gapminder.ipynb)
    - [on Github]({{ site.repository }}/blob/gh-pages/code/plot-gapminder.ipynb)
