# fair-assessment

For Dev Cycle 4 we carried out an assessment of the FAIRness of datasets being used in FAIR EASE: see the confluence pages [for the paper](https://fair-ease.atlassian.net/wiki/spaces/FAIREASE/pages/341311604/D4T12+-+Paper+preparation+and+Deliver+on+FAIR+DATA+AND+METHODS) and [for D6.5](https://fair-ease.atlassian.net/wiki/spaces/FAIREASE/pages/347799553/D4T11+-+Writing+the+D6.5).

In this repo you will find
* A spreadsheet of the datasets we are working on. **If you add to this spreadsheet please use the [google spreadsheet](https://docs.google.com/spreadsheets/d/1DmnS8WbHCUK4WFF6qj6JRrHWd9Yla7KjZf13Q-_hxvw/edit?usp=sharing) and not the file here**. Katrina will update the version here in GH every now and then.
* The FUJI results - all the json files. The name of the dataset that they belong to is recorded in the spreadsheet. 

The deeper analysis of the FUIJ results, and running recommendations to be made either to the pilot or the data provider, can be found on a [confluence page](https://fair-ease.atlassian.net/wiki/spaces/FAIREASE/pages/380174344/Deeper+analysis+of+the+FUJI+results). Once this work has completed, we will post a summary here. 

## What do we need from the pilots next (as of July 19 2024)?
As you will see from the spreadsheet ([google spreadsheet](https://docs.google.com/spreadsheets/d/1DmnS8WbHCUK4WFF6qj6JRrHWd9Yla7KjZf13Q-_hxvw/edit?usp=sharing) in the sheet "Datasets analysed"), there are only 10 datasets that have been analysed via FUJI
* for most pilots we have just one unique dataset, tho some with double links (which is good)
* for 5.1.2 ECZ we have no datasets

**So we need the pilots to add more source datasets to the tab "Additional datasets from pilots"**

In the tab "Datasets taken from the IDDAS", please see [this confluence page](https://fair-ease.atlassian.net/wiki/spaces/FAIREASE/pages/409403395/Datasets+obtained+by+the+IDDAS) to know what we may do here: at present this is empty.


## The FUJI tool
The FUJI tests we are using are carried out from https://www.f-uji.net/?action=test, where you input the URL to a dataset. The tool then looks for metadata that cover the different items of F A I R. 

The list of the points it checks can be found on its [Method page](https://www.f-uji.net/index.php?action=methods), together with some more technical detail on how it does its assessment. When analysing the results here, it is worth looking at this page to understand what was looked for and found/not found. More detail can also be found in the tables on https://zenodo.org/records/6461229. 

The code itself can be found on https://github.com/pangaea-data-publisher/fuji.

It uses its own ontology, which can be searched on https://www.f-uji.net/vocab/ although without an overview of all its terms, it is rather awkward to search. In any case, it just defines the terms that it uses in its work, so is the place to go if you e.g. want to know what it means by ["data"](https://www.f-uji.net/vocab//data) or, more usefully, the list of [data formats](https://www.f-uji.net/vocab/data/format) that it includes as "data", or the [type of PIDs](https://www.f-uji.net/vocab/identifier/persistent) it considers, 


