---
title: 'A semi-automated tool for ontology assignment of food nutrition study data'
tags:
  - Bioinformatics
  - Food
  - Nutrition
  - Ontology Assignment
authors:
  - name: Jan Stanstrup
    orcid: 0000-0000-0000-0000
    affiliation: 1
  - name: Blanca Lacruz-Pleguezuelos
    orcid: 0000-0000-0000-0000
    affiliation: 2
  - name: Duncan Ng
    orcid: 0000-0000-0000-0000
    affiliation: 3
  - name: Duygu Dede Sener
    orcid: 0000-0000-0000-0000
    affiliation: 4
  - name: Finn Sandø 
    orcid: 0000-0000-0000-0000
    affiliation: 1
affiliations:
 - name:  Department of Plant and Environmental Sciences, University of Copenhagen, Copenhagen, Denmark
   index: 1
 - name: IMDEA Research  Institute on Food&Health Sciences , Madrid, Spain
   index: 2
 - name: Quadram Research  Institute , Norwich, United Kingdom
   index: 3
 - name: Department of Bioinformatics , Maastricht University, Maastricht, Netherlands
   index: 4
date: 11/11/2022
bibliography: paper.bib
authors_short: Last et al. (2021) BioHackrXiv  template
group: BioHackrXiv
event: BioHackathon Europe 2021
---

# Introduction or Background

Ontologies are needed to share common knowledge between researchers in a specific domain. They have influential solutions for representing domain knowledge in a structured way by integrating data from different sources. This leads to the support of the usage of semantic applications. 

Ontology assignment is a significant problem for data providers. There has been a growing number of ontologies available for each scientific domain. Therefore, users struggle with matching the correct ontology with each term in their data. At this point, the user needs support from tools or services providing an assignment process. Ontology Lookup Service (OLS) (ref) is one of the most used services to meet this need. ZOOMA (https://www.ebi.ac.uk/spot/zooma/) is another ontology annotation tool that maps text to ontology based on curated mappings from data sources. Users can provide a list of free text and ZOOMA will assign ontology, with confidence, on the data. However, one of the issues with the current implementation of ZOOMA is the number of results extracted from ontology sources.  

In this study, we developed a semi-automated tool for assigning ontologies to food and nutrition studies. The main strength of this tool is providing annotation in an easy way for the user rather than selecting an ontology for each term manually. With this tool, users can query ontologies by providing metadata, dietary intake data, food diaries, or food consumption data.  This tool includes getting data from users, preparing it to be used in the lookup service and extracting term-ontology mapping from the service via API. The tool is showcased on a dataset DIME (Dietary Bioactives and Microbiome Diversity) https://quadram.ac.uk/dimestudy/  

# Methods

We developed a user interface via RShiny App for getting user queries, getting data from ontology repositories by using an ontology lookup service (ZOOMA) via API. 

# Discussion


# Conclusion

The developed semi-automated tool is useful and efficient for the users for annotation of food, and nutrition study data. 

# Future Work

As a lookup service, ZOOMA has some limitations, so we can use OLS (Ontology Lookup Service) for this purpose.  Exact string matching should work properly. 


# Acknowledgments

This work was done during the BioHackathon 2022 organized by ELIXIR in October 2022 in Paris, France. We thank the organizers for the opportunity and the support via travel grants for some of the authors.

# References

Côté, R., Reisinger, F., Martens, L., Barsnes, H., Vizcaino, J. A., & Hermjakob, H. (2010). The ontology lookup service: bigger and better. Nucleic acids research, 38(suppl_2), W155-W160.
