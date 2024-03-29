[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4271467.svg)](https://doi.org/10.5281/zenodo.4271467)

# ELTeC

## General remarks 

This is the umbrella repository that references the corpora contained in any given release of ELTeC (European Literary Text Collection), a collection of novels in multiple European languages created by the COST Action *Distant Reading for European Literary History* (CA16204). Note that this umbrella repository only *references* the collections but *does not contain* the actual text files. 

ELTeC aims to provide multiple corpora of 100 novels published between 1840 and 1920 in their original language. There are corpora for multiple European languages, but the novels included in them are not translations of each other. Each corpus follows the same criteria for corpus composition, but these criteria allow for some flexibility. The level of compliance with the corpus composition criteria is summarized in the E5C score. The novels are encoded in a common manner according to a specific subset of the Guidelines of the *Text Encoding Initiative* that is documented in a three-tiered schema. More detailed information on ELTeC can be found in the following places: 

* An overview of the current state in ELTeC corpus building can be found here: https://distantreading.github.io/ELTeC/
* ELTeC is described succinctly here: https://www.distant-reading.net/eltec/
* Work on the ELTeC collections is in progress here: https://github.com/COST-ELTeC
* The criteria used for corpus composition can be found here: https://distantreading.github.io/sampling_proposal.html
* The encoding guidelines used for the XML-TEI markup (level 1) can be found here: https://distantreading.github.io/Schema/eltec-1.html 
* The schemas used to validate the XML-TEI files can be found here (and are included in each release): https://github.com/COST-ELTeC/Schemas 
* ELTeC releases are made available on Zenodo in the COST-ELTeC community: https://zenodo.org/communities/eltec/search?page=1&size=25 
* For those interested in element usage statistics, see here: https://distantreading.github.io/ELTeC/tagCounts.html

The concept DOI, covering all releases of this umbrella repository and always resolving to the latest release, is the following: https://doi.org/10.5281/zenodo.3462435. 

## Contacts 

For issues related to this release or individual collections contained in this release, please use the relevant repository's issue tracker here on Github. 

For more general questions, please contact the Working Group lead, Martina Scholger (martina.scholger@uni-graz.at). 

## Release notes

### v1.1.0 (April 11, 2021; DOI: https://doi.org/10.5281/zenodo.4662444)

ELTeC is work in progress and the current release reflects this. This release contains 14 different corpora in total with at least 50 novels each. Collections in this release include: Czech, German, English, French, Hungarian, Norwegian, Polish, Portuguese, Romanian, Slovenian, Spanish, Serbian, Swedish and Ukrainian. There are 8 corpora that are complete, containing 100 novels. There are 3 complete corpora that also provide versions with linguistic annotation. See the section "Corpora included" below for details on each collection. 


### v1.0.0 (November 15, 2020; DOI: https://doi.org/10.5281/zenodo.4274954)

ELTeC is work in progress and the current release reflects this. We aim at 100 novels per language collection, but the current release also includes collections containing less than that, but at least 50 novels. Collections in this release include: German, English, French, Hungarian, Portuguese, Romanian, Slovenian, Spanish, Serbian and Swedish (see details below). Additional collections are in preparation on GitHub and will be included in future releases. Also, there are still improvements to be made, in some cases, to the encoding of the texts, the quality of the transcriptions, or the level of conformance to the sampling criteria.  

Generally speaking, the texts included in the current release are encoded either on a level 0 or level 1 encoding, according to the ELTeC scheme of levels of encoding. Please also take note of the README files included with each collection's release linked below. They describe the current state of each collection and provide further information, e.g. on contributors and text sources, and a citation suggestion.

### v0.5.0 (November 2019)

ELTeC is work in progress and the current release reflects this. We aim at 100 novels per language collection, but the current release also includes collections containing less than that, but at least 20 novels. Also, there are still improvements to be made, in some cases, to the encoding of the texts, the quality of the transcriptions, or the level of conformance to the sampling criteria. 

Generally speaking, the texts included in the current release are encoded either on a level 0 or level 1 encoding, according to the ELTeC scheme of levels of encoding. Please also take note of the README files included with each collection's release linked below. They describe the current state of each collection.  

## Citation suggestion

If you use any ELTeC collection(s) in your teaching or research, please reference ELTeC in manner consistent with academic best practices. Each collection provides its own citation suggestion, but if you would like to reference the entire ELTeC, please use the following reference: 

* *European Literary Text Collection (ELTeC)*, version 1.1.0, April 2021, edited by Carolin Odebrecht, Lou Burnard and Christof Schöch. COST Action *Distant Reading for European Literary History* (CA16204). DOI: doi.org/10.5281/zenodo.4662444. 

```
@collection{odebrecht_ELTeC_2021,
  maintitle = {European Literary Text Collection ({ELTeC})},
  editor = {Odebrecht, Carolin and Burnard, Lou and Schöch, Christof},
  version = {v1.1.0},
  year = {2021},
  month = {4},
  publisher = {COST Action Distant Reading for European Literary History},
  url = {https://github.com/COST-ELTeC/ELTeC},
  doi = {10.5281/zenodo.4662444},
  }
```

In addition, or alternatively, you may cite one of the reference publications about ELTeC: 

* Lou Burnard, Christof Schöch, Carolin Odebrecht (2021): "In Search of Comity: TEI for Distant Reading", in: _Journal of the Text Encoding Initiative_ 14. DOI: https://doi.org/10.4000/jtei.3500. 
* Christof Schöch, Roxana Patraș, Diana Santos, Tomaž Erjavec (2021): "Creating the European Literary Text Collection (ELTeC): Challenges and Perspectives", in: _Modern Languages Open_ 1/25. DOI: http://doi.org/10.3828/mlo.v0i0.364.

## Collections included

The following is a list of the language-specific collections of novels included in the current release, in alphabetical order. For each collection, we indicate the version number and date of this particular release of the collection, a brief description of the release content, the collection editors, the URL where it can be found on Github as well as its DOI. In addition, we indicate the concept DOI of all releases of the collection. 

### v1.1.0 (April 5, 2021, DOI: https://doi.org/10.5281/zenodo.4662444)

* **ELTeC-cze (Czech)**  
  * v1.0.0 (April 5, 2021)
  * Number of novels: 100 (level 1)
  * Collection editors: Institute of the Czech National Corpus
  * URL: https://github.com/COST-ELTeC/ELTeC-cze/releases/tag/v1.0.0
  * version DOI: https://doi.org/10.5281/zenodo.4662721
  * concept DOI: https://doi.org/10.5281/zenodo.4662458

* **ELTeC-deu (German)**  
  * v1.0.0 (April 5, 2021)
  * Number of novels: 100 (level 0)
  * Collection editors: Fotis Jannidis, Leonard Konle, Carolin Odebrecht, an algorithm
  * URL: https://github.com/COST-ELTeC/ELTeC-deu/releases/tag/v1.0.0
  * version DOI: https://doi.org/10.5281/zenodo.4662482
  * concept DOI: https://doi.org/10.5281/zenodo.3543243

* **ELTeC-eng (English)**  
  * v1.0.1 (April 5, 2021)
  * Number of novels: 100 (87 at level 1, 13 at level 0)
  * Collection editor: Lou Burnard
  * URL: https://github.com/COST-ELTeC/ELTeC-eng/tree/v1.0.1
  * version DOI: https://doi.org/10.5281/zenodo.4662490
  * concept DOI: https://doi.org/10.5281/zenodo.3533868

* **ELTeC-fra (French)**  
  * v1.0.1 (April 5, 2021)
  * Number of novels: 100 (at level 1)
  * Collection editors: Christof Schöch and Lou Burnard
  * URL: https://github.com/COST-ELTeC/ELTeC-fra/releases/tag/v1.0.1
  * version DOI: https://doi.org/10.5281/zenodo.4662433
  * concept DOI: https://doi.org/10.5281/zenodo.3462535
  
* **ELTeC-hun (Hungarian)**  
  * v2.0.0 (April 5, 2021)
  * Number of novels: 100 (at level 1 and level 2)
  * Collection editor: Gábor Pálko
  * URL: https://github.com/COST-ELTeC/ELTeC-hun/releases/tag/v2.0.0
  * version DOI: https://doi.org/10.5281/zenodo.4662499
  * concept DOI: https://doi.org/10.5281/zenodo.4271637

* **ELTeC-nor (Norwegian)**  
  * v0.5.0 (April 5, 2021)
  * Number of novels: 50 (at level 1 and level 2)
  * Collection editor: Michael Preminger and Christian Emil Smith Ore
  * URL: https://github.com/COST-ELTeC/ELTeC-nor/releases/tag/v0.5.0
  * version DOI: https://doi.org/10.5281/zenodo.4662724
  * concept DOI: https://doi.org/10.5281/zenodo.4662595

* **ELTeC-pol (Polish)**  
  * v1.0.0 (April 5, 2021)
  * Number of novels: 100 (at level 1)
  * Collection editor: Joanna Byszuk, Jan Rybicki
  * URL: https://github.com/COST-ELTeC/ELTeC-pol/releases/tag/v1.0.0
  * version DOI: https://doi.org/10.5281/zenodo.4662725
  * concept DOI: https://doi.org/10.5281/4662589 

* **ELTeC-por (Portuguese)**  
  * v2.0.0 (April 5, 2021)
  * Number of novels: 100 (at level 1 and level 2)
  * Collection editor: Diana Santos
  * URL: https://github.com/COST-ELTeC/ELTeC-por/releases/tag/v2.0.0
  * version DOI: https://doi.org/10.5281/zenodo.4288235
  * concept DOI: https://doi.org/10.5281/zenodo.3492067

* **ELTeC-rom (Romanian)**  
  * v0.9.0 (April 5, 2021)
  * Number of novels: 95 (at level 1)
  * Collection editor: Roxana Patras
  * URL: https://github.com/COST-ELTeC/ELTeC-rom/releases/tag/v0.9.0
  * version DOI: https://doi.org/10.5281/zenodo.4662599
  * concept DOI: https://doi.org/10.5281/zenodo.3543111

* **ELTeC-slv (Slovenian)**
  * v2.0.0 (April 5, 2021)
  * Number of novels: 100 (at level 1 and 2)
  * Collection editors: Tomaž Erjavec, Miran Hladnik, Marko Juvan, Katja Mihurko Poniž
  * URL: https://github.com/COST-ELTeC/ELTeC-slv/releases/tag/v2.0.0
  * version DOI: https://doi.org/10.5281/zenodo.4662600
  * concept DOI: https://doi.org/10.5281/zenodo.3518108

* **ELTeC-spa (Spanish)**
  * v0.9.1 (April 5, 2021)
  * Number of novels: 83 (at level 1)
  * Collection editor: Borja Navarro Colorado
  * URL: https://github.com/COST-ELTeC/ELTeC-spa/releases/tag/v0.9.1
  * version DOI: https://doi.org/10.5281/zenodo.4662603
  * concept DOI: https://doi.org/10.5281/zenodo.3662758

* **ELTeC-srp (Serbian)**  
  * v0.9.0 (April 5, 2021)
  * Number of novels: 90 (at level 1)
  * Collection editor: Cvetana Krstev
  * URL: https://github.com/COST-ELTeC/ELTeC-srp/releases/tag/v0.9.0
  * version DOI: https://doi.org/10.5281/zenodo.4662604
  * concept DOI: https://doi.org/10.5281/zenodo.3524056

* **ELTeC-swe (Swedish)**
  * v0.7.1 (April 11, 2021)
  * Number of novels: 58 (at level 1)
  * Collection editor: Ljubica Miočević and Cai Alfredson
  * URL: https://github.com/COST-ELTeC/ELTeC-swe/releases/tag/v0.7.1
  * version DOI: https://doi.org/10.5281/zenodo.4679350
  * concept DOI: https://doi.org/10.5281/zenodo.4271663 

* **ELTeC-ukr (Ukrainian)**
  * v0.5.0 (April 5, 2021)
  * Number of novels: 50 (at level 1)
  * Collection editor: Dmytro Yesypenko and Mykhailo Nazarenko
  * URL: https://github.com/COST-ELTeC/ELTeC-ukr/releases/tag/v0.5.0
  * version DOI: https://doi.org/10.5281/zenodo.4662617
  * concept DOI: https://doi.org/10.5281/4662731 


## Schema repository 
  
* **Schemas** 
  * v0.8.1 ("Real April 2021 release")
  * URL: https://github.com/COST-ELTeC/Schemas/releases/tag/v0.8.1
  * version DOI: https://doi.org/10.5281/zenodo.4679363
  * concept DOI: https://doi.org/10.5281/zenodo.3490757

