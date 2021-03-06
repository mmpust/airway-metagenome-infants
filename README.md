**The human respiratory tract microbial community structures in healthy and cystic fibrosis infants**<br/>
Marie-Madlen Pust<sup>1,2</sup>, Lutz Wiehlmann<sup>3</sup>, Colin Davenport<sup>3</sup>, Isa Rudolf<sup>1,2</sup>, Anna-Maria Dittrich<sup>1,2</sup> and Burkhard Tümmler<sup>1,2*</sup> 
<br/><br/>
<sup>1</sup>Clinic for Paediatric Pneumology, Allergology, and Neonatology, Hannover Medical School, Germany <br/>
<sup>2</sup>Biomedical Research in Endstage and Obstructive Lung Disease Hannover (BREATH), German Center for Lung Research, Hannover Medical School, Germany <br/>
<sup>3</sup>Research Core Unit Genomics, Hannover Medical School, Germany <br/>
<br/>

**Running title** <br/>
Airway metagenome of healthy and CF infants
<br/>
<br/>
**Cite this article** <br/>
Pust, MM., Wiehlmann, L., Davenport, C. et al. The human respiratory tract microbial community structures in healthy and cystic fibrosis infants. npj Biofilms Microbiomes 6, 61 (2020). https://doi.org/10.1038/s41522-020-00171-7
<br/>
<br/>
**Reference database** <br/>
The index of the reference database is available from <br/> https://drive.google.com/open?id=1gl6KiY0gOZiz45ulZaWQCLS6A6Su_hrX. <br/>
The multi-FASTA file can also be obtained (see instructions below).

```bash
https://sync.academiccloud.de/index.php/s/Zx5YDzT9nnblie4/download

# Unzip the reference database 
gunzip complete_bacterialRefSeqs_201910_2.fasta

# Generate an index of the reference fasta depending on the alignment tool of your choice
samtools faidx complete_bacterialRefSeqs_201910_2.fasta
bwa index complete_bacterialRefSeqs_201910_2.fasta
```
