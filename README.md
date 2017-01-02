# Jena-Fuseki-Reasoner-Inference
A test project enabling inference in Apache Jena Fuseki 2.4.1 with Jena Rules, RDFS (Entailment Regimes) and OWL

modelo.ttl
==========
An ontology model defined in turtle syntax referenced in Apache Jena Fuseki 2.4.1 configuration files:  ElQuijote-JenaRulesReasoner.ttl, ElQuijote-RDFSReasoner.ttl and ElQuijote-OWLReasoner.ttl

datos.ttl
=========
A data (instances) ontology file defined in turtle syntax. This file defines all instances from model modelo.ttl. This file is referenced in Apache Jena Fuseki 2.4.1 configuration files:  ElQuijote-JenaRulesReasoner.ttl, ElQuijote-RDFSReasoner.ttl and ElQuijote-OWLReasoner.ttl

reglas.rules
============
An Apache Jena rules to use with Rule Reasoner in Apache Jena Fuseki 2.4.1. This file is referenced in Apache Jena Fuseki 2.4.1 configuration file: ElQuijote-JenaRulesReasoner.ttl

ElQuijote-JenaRulesReasoner.ttl
===============================
An Apache Jena Fuseki 2.4.1 dataset configuration file to enable Apache Jena rules based reasoner. Requires: modelo.ttl, datos.ttl and reglas.rules files.

ElQuijote-RDFSReasoner.ttl
==========================
An Apache Jena Fuseki 2.4.1 dataset configuration file to enable RDFS reasoner. Requires: modelo.ttl and datos.ttl files.

ElQuijote-OWLReasoner.ttl
=========================
An Apache Jena Fuseki 2.4.1 dataset configuration file to enable OWL reasoner. Requires: modelo.ttl and datos.ttl files.

Brief tutorial and explanations
===============================
http://www.juanfelipe.info/node/181
