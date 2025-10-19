# Modular Insertion System

A flexible, scalable extracellular electrophysiology rig

![Rendering of the insertion system](documentation/source/_static/isometric_render.png)


## Key features

- Insertion angles up to ±75° A/P and ±45° M/L
- Modules for electrophysiology, optogenetics, and microscopes
- 600 mm x 500 mm open area for behavioral platform
- Design files available for noncommercial use

## Contributors

- Mechanical design: Jon Arnold
- Concept and oversight: Josh Siegle, Karel Svoboda
- Validation: Galen Lynch, Yoni Browning, Anna Lakunina, Xinxin Yin, Han Hou, Susu Chen
- Electrical design: Sonya Vasquez


## How to order

In most cases, we recommend purchasing a [complete system](https://newscaletech.com/modular-insertion-system/) from New Scale Technologies. They can work with you to design a custom configuration to suit your experimental needs.

If you would like to manufacture the individual components, we strongly recommend [posting an issue](https://github.com/AllenNeuralDynamics/modular-insertion-system/issues) before getting started so we can provide advice on the best way forward. We offer no guarantees that the system will work as advertised if you assemble it on your own.


## Documentation

We may decide to launch a web-based documentation site at some point. To build the documentation yourself, follow these instructions:

First, make sure [Sphinx](https://www.sphinx-doc.org/en/master/usage/installation.html) is installed on your system.

Then, in a Python virtual environment (e.g. `conda`), run

```
pip install -e .[docs]
```

To create the documentation HTML files, run

```
sphinx-build -b html documentation/source/ documentation/build/html
```

## License

The contents of this repository are covered by the [Creative Commons BY-NC-SA License](LICENSE). Any design files or documentation, or modifications thereof, cannot be used for commercial purposes without prior written consent from the Allen Institute. In other words, you are allowed to build the system for use in your own lab, but you cannot sell the drawings, models, or physical components. Any derivations must be attributed to the Allen Institute and shared with the same licensing terms.

<img src="documentation/source/_static/CC-BY-NC-SA.png" width="200" />
