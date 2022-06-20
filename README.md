# CsA_FF
The CHARMM force field of unatural amino acids in the cyclic peptide cyclosporin A.
***
The force field file consists of two files: a topology file (CsA_CHARMM.rtf) and a parameter file (CsA_CHARMM.prm).
***
The topology file (CsA_CHARMM.rtf) contains topologies for the following unnatural amino acids.
* NLEU (N-methyl leucine)
* NVAL(N-methyl varine)
* ABU (2-Aminobutanoic acid)
* SAR (Sarcosine, N-methyl glycine)
* BMT (4-METHYL-4-[(E)-2-BUTENYL]-4,N-METHYL-THREONINE)
***
The parameter file (CsA_CHARMM.prm) contains the following potential energy term parameters for the unnatural amino acids.
* bond
* angle
* dihedral angle
* LJ term
* CMAP term (CMAP terms involving N-metyl amino acid)
***
## Requirment
These force fields have to use together with charmm36m force fields.
***
## Notes.
This force field parameter was developed for molecular dynamics simulation calculations of cyclosporin A application to other systems is at your own risk.
