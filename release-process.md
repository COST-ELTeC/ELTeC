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
6. Update the listERM.xml file in the top-level ELTEC repository (Lou). The file listERM.xml is used by the checkUp.xsl script to produce a new <publicationStmt> in each file which is part of the new release (new publication date, new version DOI of ELTeC umbrella, new version DOI of corpus, and for new corpora: new concept DOI).
7. Run the checkUp.xsl script, which also carries out a series of tests on the metadata and structure of each file, beyond simply checking validity against a schema. It produces warning and error messages if anything seems wrong. 
8. If the number of errors is small and easily fixed, it's easiest to just fix them. If however they are more numerous, or require more attention, the editor of the repository concerned must be informed. (A python script (checkRepo.py) may be used to run checkUp.xsl against each file in a repository, saving the validated and ready-for-publication files in a folder called Out. It requires a command line argument to specify the language suffix for the repository to be processed.
9. On Github, make the actual new release of the repository. Give it a succinctly name describing the release, for example: "Release with 100 novels at level 1."
10. Download the ZIP. Naming scheme: "ELTeC-{lang}xxx-{version}.zip", for example "ELTeC-fra-v1.2.0.zip".  
11. Extract the "readme.md" and "metadata.csv" separately. 
12. In the corresponding Zenodo entry: delete old files; add and upload new files (ZIP-archive, readme.md, metadata.csv)
14. Also update the metadata, especially the title, version number, release description, and Github release link (related identifiers). 
15. Save and publish. 

## For the ELTeC umbrella collection

1. Add a release statement for the new release, describing it succinctly. 
2. Update ELTeC readme: version, date, DOI, description of each collection that is included.  
3. Update also the schema repository version, if there is a new release there. (Releases of the schema repository are done on Github with the automatic Zenodo link).  

