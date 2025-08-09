# Hierarchical Variational Autoencoder-Based Generative Modelling of Earthquake Response Spectra

This is a generative machine learning framework for modelling earthquake response spectra utilising a hierarchical variational autoencoder within a Poincaré ball manifold. Predicting full ground motion response spectra is central to seismological and engineering analyses, but traditional regression-based approaches often lack flexibility and uncertainty representation. This study incorporates key source and site parameters to condition the generation of physically consistent spectral amplitudes. The formulation captures both inter- and intra-event hierarchies across periods. The model is trained on a curated database of recorded ground motions and demonstrates high reconstruction accuracy, with a mean coefficient of determination ($R^2$) of $0.961$ across all spectral periods. The proposed architecture is successfully implemented within stochastic ground motion simulation and early warning pipelines. This work establishes a mathematically principled and domain-aligned generative modelling framework that unifies modern geometric deep learning with critical tasks in seismology, earthquake engineering, and real-time seismic risk mitigation.

<img width="2530" height="922" alt="510eb1c38580ec7c295d6c19704cde4ff99db906" src="https://github.com/user-attachments/assets/ca34d720-1107-48cb-8a3c-3bf2be488104" />


Download the model and Jupyter-notebook from the following Dropbox link

    https://www.dropbox.com/scl/fo/u1usb73fxblzi4lb8ilfe/AKOAxNaYZJVTpiTw4BRLNsk?rlkey=fap96why2ex028oswiknpu3z6&dl=0


Reference:

    Alfred Wright and Jawad Fayaz (under review). “Structured Generative Modelling of Earthquake Response Spectra with Hierarchical Latent Variables in Hyperbolic Geometry”
