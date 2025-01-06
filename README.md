### Arioc:  GPU-accelerated DNA short-read alignment

Download the current release [here](https://github.com/RWilton/Arioc/releases "Arioc releases").

Download the Arioc user guide [here](https://github.com/RWilton/Arioc/blob/master/Arioc.guide.pdf "Arioc user guide") or as part of the current release.

#### Arioc-encoded reference genomes
The Arioc aligners use binary encoded lookup tables as reference genome indexes. For convenience, several Arioc-encoded reference genomes are available for download at [ftp://ftp.ccb.jhu.edu/pub/data/Arioc](https://tinyurl.com/AriocFTP), the FTP server of the [Center for Computational Biology](http://www.ccb.jhu.edu) at Johns Hopkins University:

| genome | subdirectory | content |
|-|-|-|
| H&nbsp;sapiens | H_sapiens | NCBI GRCh38: patch 14 (WGS); patch 13 (WGS, WGBS) |
| M&nbsp;musculus | M_musculus | NCBI GRCm39 |
| S&nbsp;cerevisiae | S_cerevisiae | S288C |
| T&nbsp;aestivum | T_aestivum | NCBI GCA_002220425.3 (Triticum 4.0) |

#### Related publications
Wilton R, Budavari T, Langmead B, Wheelan SJ, Salzberg SL, Szalay AS.  **Arioc: high-throughput read alignment with GPU-accelerated exploration of the seed-and-extend search space.**  *PeerJ*. 2015, **3**:e808. [DOI:10.7717/peerj.808](https://doi.org/10.7717/peerj.808)

Wilton R, Li X, Feinberg AP, Szalay AS.  **Arioc: GPU-accelerated alignment of short bisulfite-treated reads.**  *Bioinformatics*. 2018, **34**(15):2673–2675. [DOI:10.1093/bioinformatics/bty167](https://doi.org/10.1093/bioinformatics/bty167)

Wilton R, Szalay AS.  **Arioc: High-concurrency short-read alignment on multiple GPUs.**  *PLoS Comput Biol*. 2020, **16**(11):e1008383. [DOI:10.1093/10.1371/journal.pcbi.1008383](https://doi.org/10.1371/journal.pcbi.1008383)

Wilton R, Szalay AS.  **Performance optimization in DNA short-read alignment.**  *Bioinformatics*. 2022, **38**(8):2081–2087.  [DOI:10.1093/bioinformatics/btac066](https://doi.org/10.1093/bioinformatics/btac066)

Wilton R, Szalay AS.  **Short-read aligner performance in germline variant identification.**  *Bioinformatics*. 2023, **39**(8):1–11.  [DOI:10.1093/bioinformatics/btad480](https://academic.oup.com/bioinformatics/article/39/8/btad480/7234613)
