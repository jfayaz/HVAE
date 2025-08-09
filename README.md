# Hierarchical Variational Autoencoder-Based Generative Modelling of Earthquake Response Spectra

This presents a geometry-aware generative modelling framework for earthquake response spectra, leveraging a hierarchical variational autoencoder (HVAE) with latent variables embedded in a Poincaré ball manifold. Predicting complete ground motion response spectra is crucial for seismic hazard analysis and structural performance assessment; however, conventional machine learning models struggle to capture multi-scale dependencies and represent predictive uncertainty. The proposed architecture conditions on source and site parameters to generate physically consistent spectral amplitudes, while explicitly modelling inter- and intra-event variability across spectral periods. By exploiting hyperbolic latent geometry, the HVAE encodes hierarchical relationships with improved representational efficiency. Trained on a curated strong-motion dataset, the model achieves high reconstruction fidelity, with a mean coefficient of determination of 0.961 across all periods. Integration into stochastic ground motion simulation and early warning pipelines demonstrates its practical utility. This work bridges geometric deep learning and seismological modelling, offering a principled, domain-aligned approach to real-time seismic risk mitigation.

<img width="2530" height="922" alt="510eb1c38580ec7c295d6c19704cde4ff99db906" src="https://github.com/user-attachments/assets/ca34d720-1107-48cb-8a3c-3bf2be488104" />


Download the model and Jupyter-notebook from the following Dropbox link

    https://www.dropbox.com/scl/fo/u1usb73fxblzi4lb8ilfe/AKOAxNaYZJVTpiTw4BRLNsk?rlkey=fap96why2ex028oswiknpu3z6&dl=0


Reference:

    Alfred Wright and Jawad Fayaz (under review). “Structured Generative Modelling of Earthquake Response Spectra with Hierarchical Latent Variables in Hyperbolic Geometry”
