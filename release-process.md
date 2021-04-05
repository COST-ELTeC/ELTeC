This document describes the release process for ELTeC. 

At the time of writing, the release process is performed collaboratively by Lou Burnard and Christof Schöch, with distributed roles. The goal of this document is to enable others to perform this process later on. 

Performing the following steps requires access to all Github repositories in the COST-ELTeC organization on Github.com as well as access to the upload and modify processes for all relevant repositories in the ELTeC community on Zenodo. 

## Steps to take for ELTeC as a whole (Christof)

1. On Zenodo, make sure the automatic Github-Zenodo link is deactivated for all repositories except for the Schema repository. 
2. On Zenodo, start the process of making a new version of the record in order to reserve and recover a new DOI for the umbrella collection. 

## For each collection

1. Make a list of all collections that have been updated or added recently. 
1. If the collection already existst, skip to step #2. If the collection does not exist yet, do the following: 
    1. Create the collection. 
    2. Make a dummy release v0.0.1 just with the readme.md as data. 
	  3. Proceed with the next steps. 
2. On Zenodo, make a new version to reserve a new DOI for the collection. Update the metadata (title, version and version description, in particular).   
3. Ideally, save and keep the tab open. (But new saved releases are kept by Zenodo even when the tab is closed.) 
4. On Github, check readme.md of the collection: update release statement with new publication date, version number and version DOI. 
5. Add the following information to the list: release number, version DOI (and, in the case of new collections: concept DOI)
6. Update the listERM.xml file in the top-level ELTEC repository (Lou)
7. Use Lou's script to update the publication statement of all XML files: new publication date, new version DOI of ELTeC umbrella, new version DOI of corpus (and for new corpora: new concept DOI) (Lou)
8. Make the actual release. Give it a name describing the release, for example: "Release with 100 novels at level 1."
9. Download the ZIP. Naming scheme: "ELTeC-{lang}xxx-{version}.zip", for example "ELTeC-fra-v1.2.0.zip".  
10. In the corresponding Zenodo entry, add and upload new ZIP, delete old ZIP. 
11. Also replace the "readme.md" and "metadata.tsv" files. 
12. Also update the metadata, especially the version number and Github release link (related identifiers)
13. Save and publish. 

## For the ELTeC umbrella collection

1. Add a release statement for the new release, describing it succinctly. 
2. Update ELTeC readme: version, date, DOI, description of each collection that is included.  
3. Update also the schema repository version, if there is a new release there. (Releases of the schema repository are done on Github with the automatic Zenodo link).  

