# Using Nextflow to calculate molecular descriptor

## Building blocks

- `getSMILES.rq`: SPARQL to list all SMILES (canonical and isomeric) in Wikidata
- `checkSMILES.groovy`: Groovy file to parse and validate each SMILES from an input file
- `simple.nf`: short example Nextflow script to process a TSV file with SMILES strings
