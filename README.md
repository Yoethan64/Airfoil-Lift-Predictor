# Airfoil-Lift-Predictor
Predicts lift coefficient of any handrawn/custom airfoil using a resnet50 model. Mean absolute error of the lift coefficient is 0.1058

How to execute:
1. Open aeroo.ipynb in Googel Colab.
2. Run all the cells in the notebook.
3. After running the second last cell, upload the airfoil which you drew.

Built using Google Colab, UIUC's airfoil database and xfoil for precomputed values of lift coeffiencents.

Dataset: 999 airfoils from UIUC's Airfoil Coordinates Database. (Link: https://m-selig.ae.illinois.edu/ads/coord_database.html)
Model: ResNet50 transfer learning, trained in Google Colab with T4 GPU
