# 3Di_2_ArcGISPro
## WIP:
Allows a user to run a 3Di flood model through ArcGIS Pro. The results are automatically imported into the ArcGIS project folder and can be visualised as a singular raster or timeseries.
User must have a API key for both 3Di Managment and Lizard.

### User must add the notebook to a project, add both API keys and search for their proper model:

my_model = api_client.threedimodels_list(name__icontains=***'_assen_pittelo - pittelo_klimaatsom (1) #19_'***)
print(my_model)

my_model = my_model.results[0]

In collaboration with Esri Nederland and Nelen & Schuurmans.
