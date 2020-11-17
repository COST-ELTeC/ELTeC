[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4271467.svg)](https://doi.org/10.5281/zenodo.4271467)

# ELTeC

## General remarks 

This is the umbrella repository that references the collections contained in any given release of ELTeC (European Literary Text Collection), a collection of novels in multiple European languages created by the COST Action *Distant Reading for European Literary History* (CA16204). Note that this umbrella repository only *references* the collections but *does not contain* the actual text files. 

ELTeC aims to provide multiple collections of 100 novels published between 1840 and 1920 in their original language. There are collections for multiple European languages, but the novels included in them are not translations of each other. Each collection follows the same criteria for corpus composition, but these criteria allow for some flexibility in corpus composition. The level of compliance with the corpus composition criteria is summarized in the E5C score. The novels are encoded in a common manner according to a specific subset of the Guidelines of the *Text Encoding Initiative* that is documented in a three-tiered schema. More detailed information on ELTeC can be found in the following places: 

* An overview of the current state in ELTeC corpus building can be found here: https://distantreading.github.io/ELTeC/
* ELTeC is described succinctly here: https://www.distant-reading.net/eltec/. 
* Work on the ELTeC collections is in progress here: https://github.com/COST-ELTeC
* The criteria used for corpus composition can be found here: https://distantreading.github.io/sampling_proposal.html
* The encoding guidelines used for the XML-TEI markup (level 1) can be found here: https://distantreading.github.io/Schema/eltec-1.html 
* The schemas used to validate the XML-TEI files can be found here (and are included in each release): https://github.com/COST-ELTeC/Schemas 

The concept DOI, covering all releases of this umbrella repository and always resolving to the latest release, is the following: https://doi.org/10.5281/zenodo.3462435. 

## Contacts 

For issues related to this release or individual collections contained in this release, please use the relevant repository's issue tracker here on Github. 

For more general questions, please contact the Working Group lead, Martina Scholger (martina.scholger@uni-graz.at). 

## Release notes

### v1.0.0 (November 15, 2020; DOI: https://doi.org/10.5281/zenodo.4274954)

ELTeC is work in progress and the current release reflects this. We aim at 100 novels per language collection, but the current release also includes collections containing less than that, but at least 50 novels. Additional collections are in preparation on GitHub and will be included in future releases. Also, there are still improvements to be made, in some cases, to the encoding of the texts, the quality of the transcriptions, or the level of conformance to the sampling criteria.  

Generally speaking, the texts included in the current release are encoded either on a level 0 or level 1 encoding, according to the ELTeC scheme of levels of encoding. Please also take note of the README files included with each collection's release linked below. They describe the current state of each collection and provide further information, e.g. on contributors and text sources, and a citation suggestion.

### v0.5.0 (November 2019)

ELTeC is work in progress and the current release reflects this. We aim at 100 novels per language collection, but the current release also includes collections containing less than that, but at least 20 novels. Also, there are still improvements to be made, in some cases, to the encoding of the texts, the quality of the transcriptions, or the level of conformance to the sampling criteria. 

Generally speaking, the texts included in the current release are encoded either on a level 0 or level 1 encoding, according to the ELTeC scheme of levels of encoding. Please also take note of the README files included with each collection's release linked below. They describe the current state of each collection.  

## Citation suggestion

If you use any ELTeC collection(s) in your teaching or research, please reference ELTeC in manner consistent with academic best practices. Each collection provides its own citation suggestion, but if you would like to reference the entire ELTeC, please use the following reference: 

* *European Literary Text Collection (ELTeC)*, version 1.0.0, November 2020, edited by Carolin Odebrecht, Lou Burnard and Christof Schöch. COST Action *Distant Reading for European Literary History* (CA16204). DOI: doi.org/10.5281/zenodo.4274954. 

```
@collection{odebrecht_ELTeC_2020,
  maintitle = {European Literary Text Collection ({ELTeC})},
  editor = {Odebrecht, Carolin and Burnard, Lou and Schöch, Christof},
  version = {v1.0.0},
  year = {2020},
  month = {11},
  publisher = {COST Action Distant Reading for European Literary History},
  url = {https://github.com/COST-ELTeC/ELTeC-fra/},
  doi = {10.5281/zenodo.4274954},
  }
```

## Collections included

The following is a list of the language-specific collections of novels included in the current release, in alphabetical order. For each collection, we indicate the version number and date of this particular release of the collection, a brief description of the release content, the collection editors, the URL where it can be found on Github as well as its DOI. In addition, we indicate the concept DOI of all releases of the collection. 

### v1.0.0 (November 15, 2020, DOI: https://doi.org/10.5281/zenodo.4274954)

* **ELTeC-deu (German)**  
  * v0.9.1 (November 15, 2020)
  * Number of novels: 98 (level 0)
  * Collection editors: Fotis Jannidis, Leonard Konle, Carolin Odebrecht, an algorithm
  * URL: https://github.com/COST-ELTeC/ELTeC-deu/releases/tag/v.0.9.1
  * version DOI: https://doi.org/10.5281/zenodo.4271627
  * concept DOI: https://doi.org/10.5281/zenodo.3543243

* **ELTeC-eng (English)**  
  * v1.1.0 (November 15, 2020)
  * Number of novels: 100 (87 at level 1, 13 at level 0)
  * Collection editors: Lou Burnard
  * URL: https://github.com/COST-ELTeC/ELTeC-eng/tree/v1.0.0
  * version DOI: https://doi.org/10.5281/zenodo.4271630
  * concept DOI: https://doi.org/10.5281/zenodo.3533868

* **ELTeC-fra (French)**  
  * v1.0.0 (November 15, 2020)
  * Number of novels: 100 (at level 1)
  * Collection editors: Christof Schöch and Lou Burnard
  * URL: https://github.com/COST-ELTeC/ELTeC-fra/releases/tag/v1.0.0
  * version DOI: https://doi.org/10.5281/zenodo.4264647
  * concept DOI: https://doi.org/10.5281/zenodo.3462535
  
* **ELTeC-hun (Hungarian)**  
  * v1.0.0 (November 15, 2020)
  * Number of novels: 100 (at level 1)
  * Collection editor: Gábor Pálko
  * URL: https://github.com/COST-ELTeC/ELTeC-hun/releases/tag/v1.0.0
  * version DOI: https://doi.org/10.5281/zenodo.4271643
  * concept DOI: https://doi.org/10.5281/zenodo.4271637

* **ELTeC-por (Portuguese)**  
  * v0.9.0 (November 15, 2020)
  * Number of novels: 100 (at level 1)
  * Collection editor: Diana Santos
  * URL: https://github.com/COST-ELTeC/ELTeC-por/releases/tag/v0.9.0
  * version DOI: https://doi.org/10.5281/zenodo.4271644
  * concept DOI: https://doi.org/10.5281/zenodo.3492067

* **ELTeC-rom (Romanian)**  
  * v0.7.0 (November 15, 2020)
  * Number of novels: 80 (at level 1)
  * Collection editor: Roxana Patras
  * URL: https://github.com/COST-ELTeC/ELTeC-rom/releases/tag/v0.7.0
  * version DOI: https://doi.org/10.5281/zenodo.4271645
  * concept DOI: https://doi.org/10.5281/zenodo.3543111

* **ELTeC-slv (Slovenian)**
  * v0.7.1 (November 15, 2020)
  * Number of novels: 100 (at level 1 and 2)
  * Collection editors: Tomaž Erjavec, Miran Hladnik, Marko Juvan, Katja Mihurko Poniž
  * URL: https://github.com/COST-ELTeC/ELTeC-slv/releases/tag/v0.7.1
  * version DOI: https://doi.org/10.5281/zenodo.4271648
  * concept DOI: https://doi.org/10.5281/zenodo.3518108

* **ELTeC-spa (Spanish)**
  * v0.9.0 (November 15, 2020)
  * Number of novels: 81 (at level 1)
  * Collection editor: Borja Navarro Colorado
  * URL: https://github.com/COST-ELTeC/ELTeC-spa/releases/tag/v0.9.0
  * version DOI: https://doi.org/10.5281/zenodo.4271661
  * concept DOI: https://doi.org/10.5281/zenodo.3662758

* **ELTeC-srp (Serbian)**  
  * v0.7.0 (November 15, 2020)
  * Number of novels: 67 (at level 1)
  * Collection editor: Cvetana Krstev
  * URL: https://github.com/COST-ELTeC/ELTeC-srp/releases/tag/v0.7.0
  * version DOI: https://doi.org/10.5281/zenodo.4271662
  * concept DOI: https://doi.org/10.5281/zenodo.3524056

* **ELTeC-swe (Swedish)**
  * v0.7.0 (November 15, 2020)
  * Number of novels: 58 (at level 1)
  * Collection editor: Ljubica Miočević and Cai Alfredson
  * URL: https://github.com/COST-ELTeC/ELTeC-swe/releases/tag/v0.7.0
  * version DOI: https://doi.org/10.5281/zenodo.4271681
  * concept DOI: https://doi.org/10.5281/zenodo.4271663 


## Schema repository 
  
* **Schemas** 
  * v0.7.0 ("level0 and level1 release")
  * URL: https://github.com/COST-ELTeC/Schemas/releases/tag/v0.7.0
  * version DOI: https://doi.org/10.5281/zenodo.3490758
  * concept DOI: https://doi.org/10.5281/zenodo.3490757

