# Agbabu_Spatial_Data_Analysis
 Agbabu Spatial Variability Modeling
This work is motivated by the need for spatially-coherent geomodels leading to reliable 
volumetric estimates of heavy oil and bitumen resources in the Agbabu deposits. 
An existing database of porosity, depth-to-top and thickness attributes of a section of the 
deposits is the subject of this work.
This work conducted exploratory spatial data analysis (ESDA) as well as empirical variogram estimation,
interpretation and modeling of the attributes. Here, the estimation and interpretation of empirical variogram
faced a number of challenges with potentials to render the estimates uninterpretable, unstable and
inconsistent with geologic information. These include presence of spatial outlier data, clusteredness of
variogram clouds, data paucity, and irregular distribution of point-pairs on variogram clouds. Spatial
outliers were either removed or correlated with existing geologic information. The clusteredness issues were
resolved using a machine-learning – aided variogram estimation technique recently proposed. Variogram
cloud binning approach was deployed to handle irregular distribution of point-pairs. In attempting to
deploy an automatic fitting algorithm, cases of insufficient empirical points leading to lack of convergence
were encountered. Such cases were resolved by adopting a combination of manual and automatic fitting
approaches.
Ultimately, this work presents a three-dimensional anisotropic (zonal) porosity variogram model and 
twodimensional anisotropic (geometric) models for the depth-to-top and thickness variograms. These models
are suitable inputs to spatial interpolation algorithms in generating maps of these volumetric attributes.
