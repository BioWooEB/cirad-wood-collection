# CIRAD wood collection dataset


Data is extracted from the index database of the CIRAD wood collection, representing eight thousand identified species and located in Montpellier, France. 
## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
## Introduction
### CIRAD
CIRAD is the French agricultural research and international cooperation organization working for the sustainable development of tropical and Mediterranean regions.
https://www.cirad.fr/en
### Wood collection (xylotheque)
CIRAD's xylotheque is one of the most important wood collections of tropical and temperate species available to date. Initiated in 1937 from several small collections that have been gathered since the end of the 19th century for exhibition and demonstration purposes, it is now regularly updated and enriched, particularly in the context of exchanges of specimens with various scientific partner at an international level. Early 2017, the collection consisted of 34,400 wood samples corresponding to about 8,400 species, 2,155 genera and 247 botanical families. The collection, in the broadest sense, encompasses the collection of wood stricto sensu (standard size board 13 x 6 x 1 cm and specimens of various sizes and shapes), anatomical slides, herbaria and ancillary products (mostly duplicates and falls). It is computerized and managed through a database, which includes all the descriptors of wood samples and anatomical slides.

"Normand, D., Mariaux, A., Détienne, P., & Langbour, P. (2017). CIRAD's wood collection. CIRAD." 
https://doi.org/10.18167/xylotheque
# Description of the dataset
It consists in the following file: `Cirad wood collection index.csv`
### General information
Both files are in Comma Separated Values (CSV) format.
* Encoding: UTF-8
* Separator: ";"
* Delimitor: none
### Data fields
The file has the following column headers:
- `CTFT id`, the main identifier and historical index 
- `Family`
- `Species`
- `Specific gravity`
- `Country` in which was collected the sample
- `Sub-continent`
- `Herbarium occurrence`, indicates if the wood sample has a match in IRD herbarium (Herbier IRD de Guyane) or National herbarium of the Muséum National d'Histoire Naturelle (MNHN - Paris, France). See links below. 
- `Number of samples`
- `Collector's name`
- `Collector's id number`, indicates a classification indentifier in IRD herbarium (Herbier IRD de Guyane) or National herbarium of the Muséum National d'Histoire Naturelle (MNHN - Paris, France). See links below. 
- `Notes on origin`
- `Number of anatomical slide(s)`, could take a value from `0` (no slide available) to `3`
- `Spare samples`, indicates if other pieces of the same sample are available, in any form.

## Appendices
### Herbier IRD de Guyane
http://publish.plantnet-project.org/project/caypub/collection/cay/specimens

### Vascular plants, Muséum national d'Histoire naturelle (MNHN - Paris, France)
https://science.mnhn.fr/institution/mnhn/collection/p/item/search/form