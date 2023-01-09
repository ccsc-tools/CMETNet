# Predicting CME Arrival Time through Data Integration and Ensemble Learning
[![DOI](https://github.com/ccsc-tools/zenodo_icons/blob/main/icons/cmenet.svg)](https://zenodo.org/record/7320334#.Y3MDt3bMJD8)
<p>Khalid A. Alobaid, Yasser Abduallah, Jason T. L. Wang, Haimin Wang </p>
<p>The Sun constantly releases radiation and plasma into the heliosphere.
Sporadically, the Sun launches solar eruptions such as flares and coronal
mass ejections (CMEs). CMEs carry away a huge amount of mass and
magnetic flux with them. An Earth-directed CME can cause serious
consequences to the human system. It can destroy power grids/pipelines,
satellites, and communications. Therefore, accurately
monitoring and predicting CMEs is important to minimize damages to
the human system. In this study we propose an ensemble learning
approach, named CMETNet, for predicting the arrival time of CMEs from
the Sun to the Earth. We collect and integrate eruptive events from two solar
cycles, #23 and #24, from 1996 to 2021 with a total of 363 geoeffective
CMEs. The data used for making predictions include CME features, solar
wind parameters and CME images obtained from the SOHO/LASCO
C2 coronagraph. Our ensemble learning framework comprises
regression algorithms for numerical data analysis and a convolutional
neural network for image processing. Experimental results show that
CMETNet performs better than existing machine learning methods
reported in the literature, with a Pearson product-moment correlation
coefficient of 0.83 and a mean absolute error of 9.75 h.</p>


Please note that starting Binder might take some time to create and start the image.

Please also note that the execution time in Binder varies based on the availability of resources. The average time to run the notebook is 10-15 minutes, but it could be more.

For the latest updates of the tool refer to https://github.com/deepsuncode/CMETNet

## Installation on local machine
|Library | Version   | Description  |
|---|---|---|
| astropy | 4.0.2| Astronomy in Python for image processing and more|
|numpy| 1.19.1| Array manipulation|
|scikit-learn| 1.0.2| Machine learning|
|scikit-image| 0.19.2 | Image processing|
| pandas|1.2.4| Data loading and manipulation|
| tensorflow| 2.4.1| Deep learning tool|
| tensorflow-gpu| 2.4.1| Deep learning tool for high performance computation |
| xgboost| 1.5.0 | Optimized distributed gradient boosting library |
