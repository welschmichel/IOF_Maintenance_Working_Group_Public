# How to work with the maintenance ontology

To view these files, you may want to use an ontology editor such as Protege (https://protege.stanford.edu/). Please ensure that this in installed before going further.

To open the maintenance WG ontology, perform the following steps:
1. Clone or download the repository
2. Right click the file named *maintenance_wg_ontology_iofcore.owl*, click "Open With" and choose "Protege".
3. Protege might prompt you to manually find some files that the ontology imports. All relevant files can be found in the repository.

Once the maintenance EG ontology is opened, you will see that the terms created by the Maintenance WG are highligted in bold under the "Classes" tab. By clicking on one of these terms, you will be able to view the definitions for these terms that were created b the maintenance WG.

Please note that this ontology is a work in progress and not all axioms have been included in the file. However, if you do wish to run a reasoner over the ontology. You can do so in Protege by clicking "Start Reasoner". 

# Notes about versions of imported files used in this ontology

At the IOF meeting 4/12/19 a new file was created maintenance_wg_ontology_iofcore.owl file. This file only imports iofcore which is from https://github.com/NCOR-US/IOF-BFO. The previous imports were removed. We suggest you use this *maintenance_wg_ontology_iofcore.owl* moving forward

Prior to the IOF meeting 4/12/19 the file was maintenance_wg_ontology.owl file. This file imported ROImport.owl, bfo.owl. This file is still here as a reference.

Update December 2019:
Since the update of the IOF ontology available at https://github.com/NCOR-US/IOF-BFO in December 2019. We completed a major overhaul of the ontology by the maintenance working group. This work has also been submitted to the I-ESA 2020 conference. 
