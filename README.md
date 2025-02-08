This is a composition estimator implemented as a standalone MATLAB app. The estimator uses count data of 1, 2, 3 and estimates the overall composition of monomers, dimers, and trimers.

To install the app, open MATLAB, double-click on the attached composition_estimator.mlappinstall file, and follow the instructions. It only takes a few seconds. 

Once the app is successfully installed, the app will be found in MATLAB’s "Apps" tab under "My apps". It will be named "Composition estimator". Just click on it and a new window will open. This will look like the attached screenshot.

On the upper left side, you need to insert the maturation efficiency (by default, the app uses 0.75, but you can change it to any value between 0 and 1). Also, you need to import step counts by clicking "Load step data" and navigate to your file. For an example formatted file, see the attached "demo_count_data.txt".

Once the data are imported, you click "Create MCMC chain", wait a few seconds for the computations to finish, and the estimated compositions of monomers, dimers, and trimers will be displayed on the right side. Estimates are mean values +/- standard deviation.

The app allows for a few more options; these are mostly for code development, so most likely you can ignore them.

For an introduction to the principles and methods used, see
Data Modeling for the Sciences by Pressé and Sgouralis, Cambridge University Press, 2003
https://doi.org/10.1017/9781009089555

For details on the MATLAB app installer files, see https://www.mathworks.com/help/matlab/creating_guis/what-is-an-app.html
