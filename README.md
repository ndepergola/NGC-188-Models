# NGC-188-Models

Utilizing astropy modeling to provide details of the open cluster NGC 188, including right ascension and declination, parallax, proper motion, and more. 
A Gaia search is performed using the Python package astroquery to obtain the measurements of NGC 188 and astropy is used to create all models.
3 searches were performed in order to refine the models.
The King Model is applied to the third and final search to find the limiting radius of the cluster. 
Membership probabilities are also estimated as the conclusion of this project.

NOTE: These notebooks could be commented better. I have a full article written about this work that is available upon request. 


FILE LIBRARY:

NGC188_models: (ipynb) Jupyter notebook containing first two Gaia searches. Parameters from the first search are used to refine the next search

NGC188_refined_King: (ipynb) Jupyter notebook containing the final search. Outputs King Model and fit, membership probabilities, and a color-magnitude diagram.
