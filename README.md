### Arioc:  GPU-accelerated DNA short-read alignment

The Arioc software is documented in the user guide.  Download the user guide directly (click [here](https://github.com/RWilton/Arioc/blob/master/Arioc.guide.pdf "Arioc user guide")) or as part of the current release (click [here](https://github.com/RWilton/Arioc/releases "Arioc releases")).

#### Arioc-encoded reference genomes
The Arioc aligners use binary encoded lookup tables as reference genome indexes. For convenience, several interesting Arioc-encoded genomes are available for download from the FTP server of the Center for Computational Biology at Johns Hopkins University ([ftp://ftp.ccb.jhu.edu/pub/data/Arioc](https://tinyurl.com/AriocFTP)).

| genome | subdirectory | content |
|-|-|-|
| H sapiens | H_sapiens | NCBI GRCh38 patch 12 (WGS) |
| H sapiens | H_sapiens | NCBI GRCh38 patch 12 (WGBS) |
| S cerevisiae | S_cerevisiae | S288C |
| T aestivum | T_aestivum | NCBI GCA_002220425.3 (Triticum 4.0) |

#### Related publications
Wilton R, Budavari T, Langmead B, Wheelan SJ, Salzberg SL, Szalay AS.  **Arioc: high-throughput read alignment with GPU-accelerated exploration of the seed-and-extend search space.**  *PeerJ*. 2015, **3**:e808. [DOI:10.7717/peerj.808](https://doi.org/10.7717/peerj.808)

Wilton R, Li X, Feinberg AP, Szalay AS.  **Arioc: GPU-accelerated alignment of short bisulfite-treated reads.**  *Bioinformatics*. 2018, **34**:1-3. [DOI:10.1093/bioinformatics/bty167](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/bty167/4938491?guestAccessKey=72ccdf78-07ee-487c-bf0f-e55da2ed867c)
