# Halophilic-Transcription-Initiation-Factor-Project
## Halobacteriales_annotated_full_genomes_list_NEW
NCBI metadata list of all halobacteriales genomes that have completed whole genome sequences. Needed for acquiring genome sequences, and will be good as a filtering tool for any step in this project to only use sequences/organism data from organisms with fully annotated genomes.

* `Assembly_Name` :	Name of assembly file
* `Assembly_Accession` :	RefSeq (NCBI derrived) assembly accesion number 
* `Assembly_Paired_Assembly_Accession` :	GenBank (primary) assemby accession number
* `Organism_Name` :	Whole Organism Name (includes Genus sp. and strain when relevant)
* `Organism_Infraspecific_Names_Strain` :	Strain type used for assembly
* `Annotation_Name` : Combines Assembly_Accession with date genome assembly was annotated
* `Assembly_Level` :	Lists how complete assembly is - should all be "complete" as a sanity check
* `Assembly_Release_Date` :	Release date of the genome assembly
* `WGS_project_accession`	: Whole Genome Sequencing Project accession number
* `Assembly_Stats_Number_of_Scaffolds` :	Number of scaffolds the genome assembly is in

## Approximate_protein_counts_v1
A list of all Halophiles in this project and their number of TFB and TBP proteins. 
* `Organism_cell_line` : Specific Organismal Cell line genome used for phylogenetic data and protein amount information
* `Organism` : Name of the organism - used as a general organism term for the data - you will notice that organisms are not repeated; individual cell line data for each organism was averaged to get TBP and TFB number data
* `TFB Number` : Number of Transcription Initiation Factor IIB (TFB) protein homologs found in an organism's genome.
* `TBP Number` : Number of TATA-Box Binding Protein (TBP) homologs found in an organism's genome

## Halobacteriales_protein_ALL_db_v1
Combined list of all TFB and TBP protein sequences and information for halobacteriales species. All acquired from Uniprot 10/8/26 (tfbs) and 10/9/26 (tbps)
* `Entry` : Name of Entry
* `Reviewed` : Has this protein seqeunce been reviewed?
* `Entry.Name` : Entry and its Gene identifier - Unique identifier for each protein
* `Protein.names` : Full name of protein
* `Gene.Names` : Gene name identifiers - includes standardized name and locus identifier
* `Organism` : Whole Organism Name (includes Genus sp. and strain when relevant)
* `Length` : Amino Acid Length of Protein
* `Gene.Ontology..biological.process.` : Standardized protein description - broader biological goals, modules, or processes protein is involved in
* `Organism..ID.` : ID number of protein for Uniprot
* `Sequence` : Full amino acid sequence of protein
* `Gene.Ontology..molecular.function.` : Standardized protein description: specific biochemical or modular acitvity of protein
* `Gene.Names..ordered.locus.` : Locus identier
* `RefSeq` : RefSeq entry code
* `Gene.Ontology.IDs` : Gene Ontology ID database reference number
* `Gene.Names..primary.` : Primary Gene Names - names protein type, sometimes is more specific to homolog
* `NCBIfam` : NCBI protein family and domain database reference number
* `GeneID` : NCBI Gene ID database reference number
* `organism_name` : Organism name as Genus sp. - NO STRAIN INFO
* 
## TRIAL TFB Database Metadata - OLD
* `Organism Cell Line` : Specific Organismal Cell line genome used for phylogenetic data and protein amount information
* `Organism` : Name of the organism - used as a general organism term for the data - you will notice that organisms are not repeated; individual cell line data for each organism was averaged to get TBP and TFB number data
* `TFB Number` : Number of Transcription Initiation Factor IIB (TFB) protein homologs found in an organism's genome.
* `TBP Number` : Number of TATA-Box Binding Protein (TBP) homologs found in an organism's genome

