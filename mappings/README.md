# Overview
These mappings specify the correspondence between the relational schemata (tables, attributes) for metadata maintained in the Data Catalog and the classes and properties in the [KLMS ontology](https://github.com/stelar-eu/klms-ontology). They are used to translate SPARQL queries expressed over the Knowledge Graph into SQL queries executed in the relational PostgreSQL database that maintains all metadata. 

This ODBA mapping file contains two blocks. The first block (_PrefixDeclaration_) declares all namespaces of vocabularies employed by the KLMS ontology and utilized in its various classes and properties. The second block (_MappingDeclaration_) actually defines a collection of mappings that retrieve data through SQL queries and expose them as RDF triples according to the KLMS ontology.







