# A semantic web approach to uplift decentralized household energy data
With the spirit of reproducible research, this repository includes a complete collection of codes required to generate the results and diagrams presented in the paper:

> J. Wu, F. Orlandi, D. O'Sullivan, S. Dev, A semantic web approach to uplift decentralized household energy data, *Sustainable Energy, Grids and Networks*, 2021.

## Details
- `ontoEnergy-extension.ipynb` contains script converting tabular data into the rdf data and the coding work for figures shown in the paper. 
- `datasets/*` contains all the data required by correlation analysis in the paper.
- `triples/individuals.owl` is a complete result of triples created by ontology modeling on CoSSMic dataset data fields. To identify the relationship between individuals implied by the data fields. We manually defined the vocabularies and named the individuals based on the CoSSMic documentation on the data fields. 
- `triples/data.ttl` contains a complete set of triples produced by `ontoEnergy/ontoEnergy.ipynb`.
