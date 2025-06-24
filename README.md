# fair-assessment

For Dev Cycle 4 we carried out an assessment of the FAIRness of datasets being used in FAIR EASE: see the confluence pages [for the paper](https://fair-ease.atlassian.net/wiki/spaces/FAIREASE/pages/341311604/D4T12+-+Paper+preparation+and+Deliver+on+FAIR+DATA+AND+METHODS) and [for D6.5](https://fair-ease.atlassian.net/wiki/spaces/FAIREASE/pages/347799553/D4T11+-+Writing+the+D6.5).

In this repo you will find
* A spreadsheet of the datasets we are working on. **If you add to this spreadsheet please use the [google spreadsheet](https://docs.google.com/spreadsheets/d/1DmnS8WbHCUK4WFF6qj6JRrHWd9Yla7KjZf13Q-_hxvw/edit?usp=sharing) and not the file here**. Katrina will update the version here in GH every now and then.
* A master spreadsheet [FAIRness assessments.xlsx][https://github.com/fair-ease/fairness-assessment/blob/main/FAIRness%20assessments.xlsx]
* The FUJI results - all the json files. The name of the dataset that they belong to is recorded in the spreadsheet. 

The deeper analysis of the FUIJ results, and running recommendations to be made either to the pilot or the data provider, can be found on a [confluence page](https://fair-ease.atlassian.net/wiki/spaces/FAIREASE/pages/380174344/Deeper+analysis+of+the+FUJI+results). This information can be found for the long term in deliverable D6.5 of the FAIR-EASE project, which will be available from the FAIR-EASE collection in Zenodo. 

In addition we have CSV files that contain the software descriptions of a subset of the software (source code, environments, UIs, etc) used in FAIR-EASE. These are all called "FAIR-EASE_software_description-XXXX.csv, with the XXXX being the name of the software. 



## The FUJI tool
The FUJI tests we are using are carried out from https://www.f-uji.net/?action=test, where you input the URL to a dataset. The tool then looks for metadata that cover the different items of F A I R. 

The list of the points it checks can be found on its [Method page](https://www.f-uji.net/index.php?action=methods), together with some more technical detail on how it does its assessment. When analysing the results here, it is worth looking at this page to understand what was looked for and found/not found. More detail can also be found in the tables on https://zenodo.org/records/6461229. 

The code itself can be found on https://github.com/pangaea-data-publisher/fuji.

It uses its own ontology, which can be searched on https://www.f-uji.net/vocab/ although without an overview of all its terms, it is rather awkward to search. In any case, it just defines the terms that it uses in its work, so is the place to go if you e.g. want to know what it means by ["data"](https://www.f-uji.net/vocab//data) or, more usefully, the list of [data formats](https://www.f-uji.net/vocab/data/format) that it includes as "data", or the [type of PIDs](https://www.f-uji.net/vocab/identifier/persistent) it considers, 


