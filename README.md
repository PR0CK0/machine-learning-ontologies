# Machine Learning Ontologies
A dump of ML and ML-related RDF/OWL ontologies because some of them are impossible to find and the semantic web community can't get its links together.

## Summaries
Applicability score / 10: how useful it is for practical work
Coverage score / 10: how complete it seems
Both of these scores are ad-hoc and focused on answering questions about ML work; if the ontology seems like it could not answer such questions, its applicability will suffer

| Name | Applicability / 10 | Coverage / 10 | Comments |
|---|---|---|---|
| AI4EU | 2 | 2 | way too small, uber-simplistic |
| ANNETT-O | 7 | 7 | probably the most focused on ANNs, has a lot of good info there, but of course, no re-use of anything else, all stovepiped |
| ANNO | 7 | 5 | like ANNETT-O but uglier, not as complete, imports a few old ontologies but none related to AI |
| ed-ai | 3 | 3 | very simplistic, seems business-focused, more mid-level, perhaps even high-level, imports nothing, all stovepiped |
| mex (all three) | 7 | 8 | decent ontology suite, all stovepiped except small usage of DOAP |
| ML-Schema | 7 | 10 | we all know ml-schema, very general and technically useful as a high-level binding, but has zero re-use and isn't connected to anything higher
| nno | 5 | 5 | a simpler mex / anno, pretty clean, no re-use of anything |
| Onto-DM | 9 | 9 | probably the best bet if you have the will to understand it, re-uses BFO so it is interoperable but also imports all of OBI which means half of the taxonomy is littered with irrelevant biomedical terms, definitely packed with good knowledge
