[![DOI](https://zenodo.org/badge/13996/monarch-initiative/SEPIO-ontology.svg)](https://zenodo.org/badge/latestdoi/13996/monarch-initiative/SEPIO-ontology)

>  _**WARNING**: The ontology here is a pre-release draft version that is still evolving, and subject to change.  A first official release of a stable core will likely happen in late 2024.  If you are making use of the ontology and would like to be updated about major changes and releases, please register in the [USERS.md](https://github.com/monarch-initiative/SEPIO-ontology/blob/master/USERS.md) file._ 


-------------------------

The **Scientific Evidence and Provenance Information Ontology** (**SEPIO**) is an OWL ontology developed to support rich, computable representations of the evidence and provenance behind scientific assertions. The core ontology defines a flexible and generic model that can be applied in any domain and extended with domain-specific features. The ontological model is the foundation of a larger **SEPIO Framework** that provides mechanisms to create custom schema for specific applications that leverage modern semantic web standards. The framework is comprised of four main components:

1. **SEPIO Core Ontology**: a computable, 'open-world' domain model encoded in the OWL description logic language.
2. **SEPIO Information Model**: provides an informal specification for how terms and design patterns defined in the ontology can be applied as a 'closed-world' model for structuring data.
3. **SEPIO Profiles**: subsets of the maximal information model that can be customized and extended to support a particular use case, and implemented in a formal schema language (e.g. JSON schema, ShEx).
4. **SEPIO Value Sets**: re-usable collections of terms bound to a particular attribute that can constrain values it can take in a particular Profile.

Data sources or developers interested in using SEPIO should begin by reading the Wiki pages recommended below, and browsing the current version of the SEPIO ontology located [here](https://github.com/monarch-initiative/SEPIO-ontology/blob/master/src/ontology/sepio.owl).  Comments or questions can be sent to Matthew Brush at brushm@ohsu.edu, or posted as tickets in the [SEPIO issue tracker](https://github.com/monarch-initiative/SEPIO-ontology/issues).

### Resources
 The Wiki pages  in this  repository are currently being updated to reflect the current state of the SEPIO Model and Framework. The pages below are recommended starting points for exploration.
1. **[SEPIO Home](https://github.com/monarch-initiative/SEPIO-ontology/wiki)**: Summary level view of most important features and considerations for using SEPIO, with links to deeper dives  into specific topics.
2. **[SEPIO Framework](https://github.com/monarch-initiative/SEPIO-ontology/wiki/The-SEPIO-Framework)**: Overview of the  components of the framework and interactions between them.
3. **[SEPIO  Ontology](https://github.com/monarch-initiative/SEPIO-ontology/wiki/The-SEPIO-Ontology)**: Deeper dive into the foundational SEPIO model as implemented in its  core  ontology. 
4. **[ClinGen-ACMG SEPIO Profile](https://github.com/monarch-initiative/SEPIO-ontology/wiki/The-ClinGen-ACMG-Variant-Interpretation-Profile)**: Detailed look at a Profile created to represent rich evidence and provenance  for clinical variant pathogenicity interpretations.
  
### License
The SEPIO Ontology and Framework is an open source project, free to re-use and re-mix under a [Creative Commons 3.0 BY license](https://creativecommons.org/licenses/by/3.0/).
 
### Development Context / Details:
The ontology is one manifestation of the underlying SEPIO Information Model.  This information model is being developed as part of the GA4GH Variant Annotation (VA) workstream, to support data exchange across GA4GH systems, and has drifted from what is in the current SEPIO ontology found here.  The ontology will be updated to reflect these changes in the near future (likely fall 2023).  A link to documentation for the GA4GH VA Information Model that will the the basis for these updates will be provided here wiht the first release of this model (Summer/Fall 2023).


