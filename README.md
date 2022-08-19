

Build:

`sudo singularity build peptide-shaker.sif peptide-shaker.def`

Run:

* PeptideShaker [GUI]: 
  
    `singularity run --app PeptideShaker --writable-tmpfs peptide-shaker.sif`

* SearchGUI [GUI]: 
  
    `singularity run --app SearchGUI --writable-tmpfs peptide-shaker.sif`

* PeptideShakerCLI: 
  
    `singularity run --app PeptideShakerCLI --writable-tmpfs peptide-shaker.sif`

* ReportCLI: 
  
    `singularity run --app ReportCLI --writable-tmpfs peptide-shaker.sif`

* FollowUpCLI: 
  
    `singularity run --app FollowUpCLI --writable-tmpfs peptide-shaker.sif`

* MzidCLI: 
  
    `singularity run --app MzidCLI --writable-tmpfs peptide-shaker.sif`

* StirredCLI: 
  
    `singularity run --app StirredCLI --writable-tmpfs peptide-shaker.sif`

* SearchCLI: 
  
    `singularity run --app SearchCLI --writable-tmpfs peptide-shaker.sif`



