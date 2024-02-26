link to paper: https://ceur-ws.org/Vol-3352/paper1.pdf

Abstract
The proliferation of applications based on knowledge graphs (KGs) in the recent years has created
increasing demands for high-quality KGs. Completeness is an important quality aspect concerning the
breadth, depth, and scope of data in KGs. In that light, describing and validating completeness over KGs
have become a must go in order to make an informed decision whether or not to use (parts of) KGs. In this
paper, we propose SoCK (short for SHACL on Completeness Knowledge), a pattern-oriented framework
to support the creation and validation of knowledge about completeness in KGs. The framework relies
on SHACL, a W3C recommendation for validating KGs against a collection of constraints. In SoCK,
we first offer a number of patterns capturing how completeness requirements are typically expressed
in a high-level way. Such completeness patterns can then be instantiated in various manners over
different KG domains. These instantiations result in SHACL shapes that can be validated against KGs to
provide a completeness profile of the KGs. As a proof-of-concept, we implement and demonstrate the
SoCK framework as a Python library, creating over 360k SHACL shapes for real-world KGs (in our case,
DBpedia and Wikidata) based on the aforementioned completeness patterns. We also develop a web app
to serve as an information point for anything about SoCK, available at https://sock.cs.ui.ac.id/.
