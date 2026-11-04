# TESS-Light-Curve-Anomaly-Detection
An end-to-end pipeline for unsupervised anomaly detection in TESS light curves using Isolation Forest and Dense Autoencoders, with model interpretability and astronomical validation.

This project explores unsupervised anomaly detection in Transiting Exoplanet Survey Satellite (TESS) light curves using two machine learning approaches: Isolation Forest and a Dense Autoencoder.

Using photometric time-series data from TESS Sector 40, the pipeline involves data preprocessing, feature extraction, dimensionality reduction, anomaly detection, and model interpretation. The two approaches are compared to investigate their effectiveness in identifying anomalous stellar light curves, with further examination of potential astrophysical sources.

## Repository Contents

| File / Directory | Description |
|---|---|
| `BRICS_Capstone_Project_GitHub_Version.ipynb` | Main Jupyter notebook containing the complete analysis pipeline, methodology, visualizations, results, and discussion. |
| `data/` | Contains the precomputed feature dataset(s) used in the analysis. |

## How to Run

The analysis can be executed using Google Colab or a local Python environment. Just ensure that the data/ directory is available alongside the notebook.

**Note**: The notebook contains internal navigation links that may not function correctly in GitHub's notebook renderer. You can find the corresponding sections by their headings.

## Acknowledgments
This project was completed as part of the BRICS Astronomy Data Science Training Programme 2026. I acknowledge the NASA Transiting Exoplanet Survey Satellite (TESS) mission for providing the photometric data used in this study.

## Feedback (if you wish to)

If you wish to provide feedback to me regarding this project, please use the Google Form below. It would take less than a minute and would help me a lot!

[Link to the form](https://docs.google.com/forms/d/e/1FAIpQLSf1Pb4-wxfphfmkARyL9RQZC8EZp0pG3jZvmuoKAPBUbOdlDQ/viewform?usp=publish-editor)

## References

Abadi, M., Barham, P., Chen, J., Chen, Z., Davis, A., Dean, J., Devin, M., Ghemawat, S., Irving, G., Isard, M., Kudlur, M., Levenberg, J., Monga, R., Moore, S., Murray, D. G., Steiner, B., Tucker, P., Vasudevan, V., Warden, P., . . . Zheng, X. (2016). TensorFlow: A system for large-scale machine learning. In 12th USENIX Symposium on Operating Systems Design and Implementation (OSDI 16) (pp. 265–283). USENIX Association. https://www.usenix.org/conference/osdi16/technical-sessions/presentation/abadi

Collaboration, A., Price-Whelan, A. M., Lim, P. L., Earl, N., Starkman, N., Bradley, L., Shupe, D. L., Patil, A. A., Corrales, L., Brasseur, C. E., Nöthe, M., Donath, A., Tollerud, E., Morris, B. M., Ginsburg, A., Vaher, E., Weaver, B. A., Tocknell, J., Jamieson, W., . . . Zonca, A. (2022). The Astropy Project: Sustaining and growing a community-oriented open-source project and the latest major release (V5.0) of the Core package. Research Portal (Queen’s University Belfast). https://doi.org/10.3847/1538-4357/ac7c74

Ginsburg, A., Sipőcz, B. M., Brasseur, C. E., Cowperthwaite, P. S., Craig, M. W., Deil, C., Guillochon, J., Guzman, G., Liedtke, S., Lim, P. L., Lockhart, K. E., Mommert, M., Morris, B. M., Norman, H., Parikh, M., Persson, M. V., Robitaille, T. P., Segovia, J., Singer, L. P., . . . Woillez, J. (2019). astroquery: An Astronomical Web-querying Package in Python. The Astronomical Journal, 157(3), 98. https://doi.org/10.3847/1538-3881/aafc33

Jenkins, J. M., Twicken, J. D., McCauliff, S., Campbell, J., Sanderfer, D., Lung, D., Mansouri-Samani, M., Girouard, F., Tenenbaum, P., Klaus, T., Smith, J. C., Caldwell, D. A., Chacon, A. D., Henze, C., Heiges, C., Latham, D. W., Morgan, E., Swade, D., Rinehart, S., & Vanderspek, R. (2016c). The TESS science processing operations center. Proceedings of SPIE, the International Society for Optical Engineering/Proceedings of SPIE, 9913, 99133E. https://doi.org/10.1117/12.2233418

Lundberg, S. M., Erion, G., Chen, H., DeGrave, A., Prutkin, J. M., Nair, B., Katz, R., Himmelfarb, J., Bansal, N., & Lee, S. (2020). From local explanations to global understanding with explainable AI for trees. Nature Machine Intelligence, 2(1), 56–67. https://doi.org/10.1038/s42256-019-0138-9

Liu, F. T., Ting, K. M., & Zhou, Z.-H. (2008). Isolation forest. In 2008 Eighth IEEE International Conference on Data Mining (pp. 413-422). IEEE. https://doi.org/10.1109/ICDM.2008.17

2.0 - Data Product Overview - TESS Archive Documentation - MAST. (n.d.). https://outerspace.stsci.edu/spaces/TESS/pages/14563420/2.0+-+Data+Product+Overview

Crake, D. A., & Martínez-Galarza, J. R. (2023). Linking Anomalous Behaviour with Stellar Properties: An Unsupervised Exploration of TESS Light Curves. arXiv (Cornell University). https://doi.org/10.48550/arxiv.2301.10264

BRICS Astronomy/IDIA Data Analytics Coursebook and Lectures

Tssc. (n.d.). LightCurve objects. TESS. https://heasarc.gsfc.nasa.gov/docs/tess/LightCurve-object-Tutorial.html

List of features — feets 1.0.1 documentation. (n.d.). https://feets.readthedocs.io/en/latest/features.html

This project made use of Lightkurve, a Python package for Kepler and TESS data analysis (Lightkurve Collaboration, 2018).

https://medium.com/data-science/implementing-an-autoencoder-in-tensorflow-2-0-5e86126e9f7

https://www.youtube.com/watch?v=ucgR0E_LXCk


