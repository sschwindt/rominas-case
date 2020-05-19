# Romina's Case
This repository contains data for the project case study in *Integrated River Engineering and SedimentManagement*.

Find geodata in the zip files of the `geodata` folder:
- DEM (m asl.) – `geodata/dem.zip`
- Land use & cover – `landuse_cover.zip` with cover IDS:
	* 1 = Yungas-cloud forest
	* 2 = Dry forest
	* 3 = Water
	* 4 = Field crop (sugar cane, citrus, blueberry)
	* 4/5 = Grain crop (soybean, maize)
	* 6 = Mountain grassland
- Rivers (Strahler ordered) – `geodata/rivers_strahler.zip` with the following fields in the attribute table:
	* Field: with name of Cuenca (Watershed): it has the acronymics, GAS: Gastona, MAT: is Matazambi and Marapa. In researchgate there is a morphometric paper where I described it.
	* Field: Jerarquia = Strahler order
	* Field: Nombre = river name.
- Annual soil loss rates – `geodata/soil_loss_m_per_year.zip` with pixel values ranging from 0 to 10. Use the classify symbology with 11 classes to visualize it.
- Watershed sub-zones – `geodata/watershed.zip`
- Census (social) data - `geodata/census-data.zip` (refer to README within census data)

Metadata and hydrological data extracts from three stations (provided by Romina):
- 409_Las_canas_Potrero_del_clavillo
- 472_Gastona_Atahona
- 473_Chico_discharge

The project work instructions are in the PDF `class-instructions.pdf`.
