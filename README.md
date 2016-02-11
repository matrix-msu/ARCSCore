## ARCSCore

ARCSCore is a metadata standard developed as part of the Archaeological Resource Cataloging System (ARCS: http://arcs.matrix.msu.edu/) project.  Funded by the National Endowment for the Humanities and developed at Michigan State University’s MATRIX: The Center for Digital Humanities and Social Sciences, ARCS is an open source, web-based platform for organizing and sharing digital versions of non-digital documents created during the course of an archaeological investigation, such as:

* field journals 
* excavation forms
* plans, profiles, and elevations
* hand-drafted representations (maps, illustrations, field sketches, etc)
* photographs
* reports (interim, end-of-season reports, materials research reports, etc)
* written descriptions of individual artifacts (including collection accession records, etc)

ARCSCore recognizes that these types of documents have become “artifacts” in and of themselves and therefore require metadata that is related to, but largely independent of the material culture they describe.  In other words, for any form of archaeological documentation in a legacy archive, there exists (1) the physical document (i.e. the field journal or photograph), (2) the digitized copy of this document and (3) the information about what the document describes  (i.e. the archaeological artifact or structures).  While ARCSCore is designed to standardize the description of the first two items, is also includes fields that identify the “subject of observation” of any particular document. 

ARCSCore organizes metadata concerning archaeological records in a series of cascading groups of fields, from general to specific.  Thus, at its most general, the first tier of fields [(ARCS_1_ProjectSchema)](/ARCS_1_ProjectSchema.csv) concerns the overall archaeological project, followed by fields for each campaign or season [(ARCS_2_SeasonSchema)](/ARCS_2_SeasonSchema.csv). Next, within each season are fields for individual units of study or excavation [(ARCS_3_Excavation-SurveySchema)](/ARCS_3_Excavation-SurveySchema.csv). The next fields concern the archaeological records themselves [(ARCS_4_ResourceSchema)](/ARCS_4_ResourceSchema.csv) and their electronic instances [(ARCS_5_PagesSchema)](/ARCS_5_PagesSchema.csv). Beneath this level are fields describing the “subject of observation” of these records [(ARCS_6_SubjectObservationSchema)](/ARCS_6_SubjectObservationSchema.csv).  ARCSCore contains only those fields that were determined to be of sufficiently universal applicability to a wide range of archaeological subjects.

ARCSCore is a significant adaptation of ArchaeoCore (http://www.ifaresearch.org/archaeocore/), which is itself a simplified adaptation of the CIDOC CRM (http://www.cidoc-crm.org/).  ArchaeoCore is “a discipline-specific metadata framework that preserves site and project information, but is both flexible and practical enough to be used by excavation, library, archive, and museum professionals.”   ARCSCore also draws significantly from Dublin Core (http://dublincore.org/).  At the individual resource level (D-Level), 14 of the 20 ARCSCore fields are drawn directly from Dublin Core.  

For those projects who wish a more robust method of describing physical artifacts, structures, and other material culture, we suggest the following standards for heritage and archaeology:

* ArchaeoCore: http://www.ifaresearch.org/archaeocore/
* ADS: http://guides.archaeologydataservice.ac.uk/g2gp/CreateData_1-2
* tDAR: https://docs.tdar.org//display/TDAR/Data+Dictionary

For more detailed documentation on each level of the metadata scheme (including examples), refer to this repository's wiki
