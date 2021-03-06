# planets
Planning our escape to mars

## Brassica Information Portal

The Brassica Information Portal (BIP) is a web repository for population and trait scoring information related to the Brassica breeding community. Advanced data submission capabilities and APIs enable users to store and publish their own study results in our Portal. 
Release embargos can be placed on datasets to reflect the need for scientists to publish their data in time with associated publications. The repository can be easily browsed thanks to a set of user-friendly query interfaces. Data download can be achieved using the API to feed into downstream analysis tools or via the web-interface.

The portal caters for the growing interest in phenotype data storage, reproducibility, and user controlled data sharing and analysis in integrated genotype-phenotype association studies aimed for crop improvement. 
The use of ontologies and nomenclature will make it easier to make conclusions on genotype-phenotype relationships within and across Brassica species. We currently use [Plant and Trait Ontology] (https://archive.gramene.org/plant_ontology/ontology_browse.html#tax) as reference ontologies for plants. And [GR_tax ontology ](https://archive.gramene.org/plant_ontology/ontology_browse.html#tax)to cover Brassica taxonomy.
Marker sequences are currently cross-referenced with resources such as [Genebank(NCBI)](https://www.ncbi.nlm.nih.gov/genbank/) and [EnsemblPlants](https://plants.ensembl.org/index.html) where possible, which will be expanded in the future

It is a Rails web application and was created by eSpectrum company on a contract with The Genome Analysis Centre but it is released as a free and open source project (see the LICENSE.txt file). The underlying database schema is derived from the CropStoreDB schema ver.7, with the original version developed by <a href="mailto:Graham.King@scu.edu.au">Graham King</a> and Pierre Carion at [Rothamsted Research](https://www.rothamsted.ac.uk/).

Apart from the LICENSE, TGAC explicitly requests any party that wishes to deploy a copy (modified or not) of BIP on their own servers, to contact, and obtain permission to do so. For that, please contact 
<a href="mailto:bip@tgac.ac.uk">bip@tgac.ac.uk</a>. If you are interested in contributing to the project, for example by adding any analytics tools, please contact us, too.
For further contact information on people behind the project or the database itself, please see the [about us](https://bip.tgac.ac.uk/about) section.

Also, follow the BIP on twitter [@BrassicaP](https://twitter.com/BrassicaP).

Currently, the web application is still under development and also changes to the database schema are possible. Despite these ongoing developments, navigation, data submissions and -download from the TGAC-hosted BIP version via the web-interface and the API should be possible.
