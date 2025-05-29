# gEVE


Due to a cyberattack on our university’s network, the gEVE database (http://geve.med.u-tokai.ac.jp) is currently unavailable.

To ensure continued access to the data, we have created this git repository temporally as an alternative access point. All data can be accessed through the folders below.

## gEVE version 1.1 raw data

[Nucleotide](./nt_fasta)

[Nucleotide (ATG starts)](./ntm_fasta)

[Amino acid](./aa_fasta)

[Amino acid (M starts)](./aam_fasta)

[GTF](./gtf)

[GTF (ATG starts)](./gtf_m)

[BED](./bed)

[BED (ATG starts)](./bed_m)

[Table (tab-delimited text files)](./table)

## Data summary

| Species    | Scientific name         | Genome ID | Genome, released date    | EVEs (Met)<sup>a</sup>| gag   | pro   | pol (LINE)<sup>b</sup>| env   | others |
|------------|-------------------------|-----------|--------------------------|-----------------------|-------|-------|-----------------------|-------|--------|
| Human      | Homo sapiens            | Hsap38    | GRCh38, Dec 2013         | 33,966 (31,292)       | 1,782 | 1,482 | 29,120 (21,087)       | 1,731 | 11     |
| Chimpanzee | Pan troglodytes         | Ptro214   | CSAC 2.1.4, Feb 2011     | 30,099 (28,136)       | 1,813 | 1,125 | 25,572 (19,043)       | 1,719 | 10     |
| Gorilla    | Gorilla gorilla         | Ggor31    | gorGor3.1, May 2011      | 26,335 (24,409)       | 1,456 | 1,034 | 22,462 (16,140)       | 1,486 | 8      |
| Orangutan	 | Pongo pygmaeus abelii   | Pabe2     | PPYG2, Sep 2007	        | 28,315 (26,716)       | 1,214 | 846   | 24,919 (19,492)       | 1,400 | 14     |
| Baboon     | Papio anubis            | Panu2     | Panu_2.0, Jun 2012	　   　| 27,230 (25,192)       | 2,101 | 1,240 | 22,125 (15,476)       | 1,962 | 5      |
| Macaque    | Macaca mulatta          | Mmul1     | MMUL 1.0, Feb 2006       | 26,941 (25,043)       | 1,980 | 1,130 | 21,968 (15,745)       | 2,020 | 7      |
| Marmoset   | Callithrix jacchus      | Cjac321   | C_jacchus3.2.1, Jan 2010 | 21,802 (20,614)       | 992   | 406   | 19,575 (16,070)       | 888   | 3      |
| Mouse      | Mus musculus            | Mmus38    | GRCm38.p1, Jan 2012      | 61,184 (58,805)       | 7,494 | 5,602 | 46,784 (29,122)       | 3,075 | 16     |
| Rat        | Rattus norvegicus       | Rnor50    | Rnor_5.0, Mar 2012       | 34,861 (32,525)       | 2,570 | 1,491 | 29,258 (21,517)       | 1,771 | 6      |
| Rabbit     | Oryctolagus cuniculus   | Ocun2     | oryCun2, Nov 2009        | 13,214 (12,909)       | 438   | 237   | 12,275 (10,473)       | 292   | 2      |
| Cow        | Bos taurus              | BtauUMD31 | UMD3.1, Dec 2009         | 105,654 (104,674)     | 1,023 | 673   | 103,402 (98,952)      | 648   | 1      |
| Cow        | Bos taurus              | Btau461   | Btau_4.6.1 Nov 2011      | 98,016 (97,150)       | 860   | 641   | 96,065 (92,153)       | 585   | 0      |
| Dog        | Canis lupus familiaris  | Cfam31    | CanFam3.1, Sep 2011      | 11,393 (11,011)       | 399   | 135   | 10,815 (10,019)       | 78    | 0      |
| Cat        | Felis catus             | Fcat62    | Felis_catus_6.2, Sep 2011| 11,132 (10,625)       | 694   | 203   | 9,898 (8,505)         | 391   | 1      |
| Horse      | Equus caballus          | Ecab2     | EquCab2.0, Sep 2007      | 14,391 (13,972)       | 190   | 142   | 13,904 (12,554)       | 167   | 0      |
| Sheep      | Ovis aries              | Oari31    | Oar_v3.1, Sep 2012       | 61,093 (60,184)       | 1,099 | 517   | 58,940 (55,274)       | 628   | 1      |
| Pig        | Sus scrofa              | Sscr102   | Sscrofa10.2, Aug 2011    | 15,210 (14,761)       | 456   | 155   | 14,350 (13,207)       | 285   | 9      |
| Goat       | Capra hircus            | Chir1     | CHIR_1.0, Jan 2013       | 37,003 (36,060)       | 1,106 | 508   | 34,797 (31,146)       | 653   | 0      |
| Opossum    | Monodelphis domestica   | Mdom5     | monDom5, Oct 2006        | 77,190 (73,029)       | 2,546 | 2,723 | 71,821 (46,874)       | 1,134 | 0      |
| Platypus   | Ornithorhynchus anatinus| Oana5     | OANA5, Dec 2005          | 1,742 (1,365)         | 2     | 1     | 1,732 (1,658)         | 7     | 0      |

<sup>a</sup>Number of EVE sequences containing at least an amino acid of Methionine was shown in parentheses. 

<sup>b</sup>Number shown in parentheses indicates pol genes that were thought to be derived from LINEs, which were annotated as “LINE” by RepeatMasker and/or “YP_073558.1” or “NP_048132.1” by BLASTP against the NCBI Viral Genome Database.

##

If you have any questions, please feel free to contact So Nakagawa (so at_sign tokai.ac.jp).

### [Reference](https://academic.oup.com/database/article/doi/10.1093/database/baw087/2630466)
Nakagawa S, Takahashi MU. 
gEVE: a genome-based endogenous viral element database provides comprehensive viral protein-coding sequences in mammalian genomes. 
Database (Oxford). 2016 May 30;2016:baw087. 
doi: 10.1093/database/baw087. PMID: 27242033; PMCID: PMC4885607.
