 Vertebrate Genome Assembly using Galaxy

 Objective

To perform genome assembly using HiFi and Hi-C data in Galaxy.

 Workflow

1. Uploaded HiFi and Hi-C datasets into Galaxy
2. Created dataset collections
3. Trimmed HiFi reads using Cutadapt
4. Performed genome profiling using Meryl and GenomeScope
5. Assembled genome using Hifiasm
6. Converted GFA to FASTA format
7. Evaluated assembly using gfastats / QUAST

 Results

* Genome Size: (write your value)
* N50: (write your value)
* Number of Contigs: (write your value)

 Notes

* Purge_dups and YaHS steps were skipped due to tool limitations in Galaxy
* Assembly evaluation was performed successfully



 Tools Used

* Galaxy platform
* Cutadapt
* Meryl
* GenomeScope
* Hifiasm
* gfastats / QUAST

  FASTA file is large (>25MB), so not uploaded here.
It can be accessed from Galaxy history.

 Screenshots

![WhatsApp Image 2026-04-03 at 10 57 36 PM](https://github.com/user-attachments/assets/fe7c087e-6bd1-4c9d-8125-6c66ab803a3e)
![WhatsApp Image 2026-04-03 at 11 07 24 PM](https://github.com/user-attachments/assets/efcccf73-91fb-4b4e-b585-23e4338fef4f)
![WhatsApp Image 2026-04-04 at 1 18 53 AM](https://github.com/user-attachments/assets/576838f2-e59c-41cc-919b-09dd12ddf7e9)
![WhatsApp Image 2026-04-04 at 1 29 38 PM](https://github.com/user-attachments/assets/37228df3-3580-4ee5-a6ff-fe2b92ad8561)
![WhatsApp Image 2026-04-04 at 2 02 55 PM](https://github.com/user-attachments/assets/7b025ab2-3359-4874-9106-e80f6b55769a)




