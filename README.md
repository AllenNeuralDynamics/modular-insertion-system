# Modular Insertion System

A flexible, scalable extracellular electrophysiology rig

![Rendering of the insertion system](documentation/source/_static/isometric_render.png)


## Key features
- Insertion angles up to ±75° A/P and ±45° M/L
- Modules for electrophysiology, optogenetics, and fiber photometry
- 600 mm x 500 mm open area for behavioral platform
- Design files available for noncommercial use


## Building the documentation

First, make sure [Sphinx](https://www.sphinx-doc.org/en/master/usage/installation.html) is installed on your system.

Then, in a Python virtual environment (e.g. `conda`), run

```
pip install -e .[docs]
```

To create the documentation HTML files, run

```
sphinx-build -b html documentation/source/ documentation/build/html
```


