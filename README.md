# Hipparcos-EDA
### Exploratory Data Analysis on the Hipparcos catalog

The Hipparcos Main Catalogue contains 118218 stars, which are available to be analyzed from [Vizier](https://vizier.cds.unistra.fr/viz-bin/VizieR-3?-source=I/239/hip_main&-out.max=50&-out.form=HTML%20Table&-out.add=_r&-out.add=_RAJ,_DEJ&-sort=_r&-oc.form=sexa). 

Using Python, we will replicate The Hertzsprung-Russell Diagram to show the relationship between temperature and luminosity or the absolute magnitude and color index of stars from the catalog. 

We produced an initial black-and-white plot;


<img src="https://github.com/LanzLagman/Hipparcos-EDA/blob/611aea3202bfe99389d2ab62d8670c68f9d1ee7d/Data/Outputs/HRD%20BW.png" width=626 height=704>

two colored HRDs, using RdYBu_r

![](https://github.com/LanzLagman/Hipparcos-EDA/blob/5ca4080ee2a12519de302a3dda2ae7efd371e475/Data/Outputs/HRD%20BV.png =250x250)

and with the B-V color index;

![alt text](https://github.com/LanzLagman/Hipparcos-EDA/blob/5ca4080ee2a12519de302a3dda2ae7efd371e475/Data/Outputs/HRD%20RdYBu_r.png)

and subplots for the spectral type of stars.

![alt text](https://github.com/LanzLagman/Hipparcos-EDA/blob/5ca4080ee2a12519de302a3dda2ae7efd371e475/Data/Outputs/Spectral%20Type%20Subplots.png)
