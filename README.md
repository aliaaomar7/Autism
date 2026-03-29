# Autism
ASD Drug Discovery Pipeline
This project implements a complete in silico drug discovery workflow targeting five Autism Spectrum Disorder-associated synaptic proteins: mTOR, SHANK3, NLGN3, NRXN1, and SYNGAP1.
The four-step pipeline includes target selection with ChEMBL bioactivity data, ADMET filtering for blood-brain barrier penetrant compounds, molecular docking with AutoDock Vina, and publication-quality visualization of results. 
A curated library of twenty compounds is processed through drug-likeness filters based on Lipinski's Rule of Five and CNS penetration criteria. Molecular properties are estimated directly from SMILES strings without requiring external cheminformatics libraries.
The docking module prepares receptor and ligand structures, executes high-throughput virtual screening, and scores binding affinities for all ligand-target combinations.
Four comprehensive figures are generated including ADMET scatter plots, docking heatmaps, top hit rankings, and target distribution analysis.
The entire workflow is designed to run on Google Colab without local installation dependencies. 
Positive controls including rapamycin and everolimus validate the screening performance against known mTOR inhibitors. When AutoDock Vina is unavailable, the pipeline falls back to simulated scoring for algorithm demonstration purposes. 
This computational approach provides a foundation for prioritizing compounds for experimental validation in ASD therapeutic development.

