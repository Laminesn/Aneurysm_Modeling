# Aneurysm_3D_Modeling
3D Data Visualization, Polynomial Fitting, and Gaussian RBF Network Modeling of Aneurysm Structures

- Data Loading and Initial Visualization:
  - Loaded aneurysm data from a .npy file and visualized the 3D structure using scatter plots.
  - Conducted 2D visualization by ignoring one coordinate to simplify and identify key data patterns.

- Data Filtering and Polynomial Fitting:
  - Filtered the dataset based on specific criteria, such as y-coordinates and coordinate ranges.
  - Applied polynomial fitting to the filtered data, creating a smooth curve that represents the aneurysm's structure.

- 3D Modeling and RBF Network Implementation:
  - Created a Gaussian RBF network to model and predict the aneurysm surface, training the model with scaled features.
  - Visualized the predicted 3D surface, showing the cylindrical shape derived from the model and comparing it with training data points.
