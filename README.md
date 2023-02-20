# EAR 👂 (ERGA Assembly Report)

Here you will find genome assembly reports approved by the ERGA Sequencing and Assembly Committee.



### EAR template
```
### 1) Species Data

| ToLID            | xSpeNam1       |
|:---------------- |:-------------- |
| Species          | Species name   |
| Class            | Name           |
| Exp. Genome size | 123456789      |
| Exp. Chromosomes | 12+X+Y         |
| GoaT             | [link](www...) |
| Biosample        | [link](www...) |

> **Observations:**
\```
Samples obtained from frozen fibroblast cell pellets (-80C) from a deceased male adult
\```

---

### 2) Data Profile

| Data           | Total reads (M) | Length (b) | Extra info                                        |
| :------------- | --------------: | ---------: | ------------------------------------------------- |
| HiFi           | 12.3            | 12345      | [multiQC](data/xSpeNam1.HiFi_multiqc_report.html) |
|                |                 |            |                                                   |
| ONT            | NA              |            |                                                   |
| Illumina PE    | NA              |            |                                                   |
|                |                 |            |                                                   |
| HiC: OmniC     | 123.4           | 123        | [multiQC](data/xSpeNam1.HiC_multiqc_report.html)  |
|                |                 |            |                                                   |
| Other: Bionano |                 |            |                                                   |

> **Observations:**
\```
Tools employed: Tool1 v0.1.2; Tool2 v3.4.5
\```

---

### 3) Genome Profiling

| Estimation     | Value     | Plot                               |
|:-------------- | --------: |----------------------------------- |
| Size           | 123456789 | ![](data/xSpeNam1.linear_plot.png) |
| Heterozygosity | 0.12      | ![](data/xSpeNam1.log_plot.png)    |
| Ploidy         | 1         | ![](data/xSpeNam1.smudge.png)      |

> **Observations:**
\```
None
\```

---

### 4) Contigging/Purging

| ID                    | Total Mb |    GC | Scaf | Cont | Gaps | Gaps Mb | Longest Scaf | Scaf N50 | Scaff L50 | Scaf N95 | Scaf L95 | Longest Cont | Cont N50 | Cont L50 | Cont N95 | Cont L95 |    QV | Kmer Compl | KCompl both | BUSCO-C | BUSCO-S | Hap                                     | both Hap                                 | shared                                     |
|:--------------------- | --------:| -----:| ----:| ----:| ----:| ------- | ------------:| --------:| ---------:| --------:| --------:| ------------:| --------:| --------:| --------:| --------:| -----:| ----------:| ----------- | -------:| -------:| --------------------------------------- | ---------------------------------------- | ------------------------------------------ |
| xSpeNam1.Hifiasm_hap1 |  1234.56 | 12.34 |   12 |  123 |   12 | 1.23    |       123.45 |   123.45 |         1 |    12.34 |       12 |       123.45 |   123.45 |        1 |     1.23 |       12 | 12.34 |      12.34 | 12.34       |    12.3 |    12.3 | ![](data/xSpeNam1.Hifiasm_hap1.hap.png) | ![](data/xSpeNam1.Hifiasm_hap1.both.png) | ![](data/xSpeNam1.Hifiasm_hap1.shared.png) |
| xSpeNam1.Hifiasm_hap2 |  1234.56 | 12.34 |   12 |  123 |   12 | 1.23    |       123.45 |   123.45 |         1 |    12.34 |       12 |       123.45 |   123.45 |        1 |     1.23 |       12 | 12.34 |      12.34 | 12.34       |    12.3 |    12.3 | ![](data/xSpeNam1.Hifiasm_hap2.hap.png) | ![](data/xSpeNam1.Hifiasm_hap2.both.png) | ![](data/xSpeNam1.Hifiasm_hap2.shared.png) |
|                       |          |       |      |      |      |         |              |          |           |          |          |              |          |          |          |          |       |            |             |         |         |                                         |                                          |                                            |
| xSpeNam1.purged_hap1  |  1234.56 | 12.34 |   12 |  123 |   12 | 1.23    |       123.45 |   123.45 |         1 |    12.34 |       12 |       123.45 |   123.45 |        1 |     1.23 |       12 | 12.34 |      12.34 | 12.34       |    12.3 |    12.3 | ![](data/xSpeNam1.purged_hap1.hap.png)  | ![](data/xSpeNam1.purged_hap1.both.png)  | ![](data/xSpeNam1.purged_hap1.shared.png)  |
| xSpeNam1.purged_hap2  |  1234.56 | 12.34 |   12 |  123 |   12 | 1.23    |       123.45 |   123.45 |         1 |    12.34 |       12 |       123.45 |   123.45 |        1 |     1.23 |       12 | 12.34 |      12.34 | 12.34       |    12.3 |    12.3 | ![](data/xSpeNam1.purged_hap2.hap.png)  | ![](data/xSpeNam1.purged_hap2.both.png)  | ![](data/xSpeNam1.purged_hap2.shared.png)  |

> **Observations:**
\```
None
\```

---

### 5) Scaffolding

| ID                    | Total Mb |    GC | Scaf | Cont | Gaps | Gaps Mb | Longest Scaf | Scaf N50 | Scaff L50 | Scaf N95 | Scaf L95 | Longest Cont | Cont N50 | Cont L50 | Cont N95 | Cont L95 |    QV | Kmer Compl | KCompl both | BUSCO-C | BUSCO-S | Hap                                     | both Hap                                 | shared                                     | HiC contact map                         |
|:--------------------- | --------:| -----:| ----:| ----:| ----:| ------- | ------------:| --------:| ---------:| --------:| --------:| ------------:| --------:| --------:| --------:| --------:| -----:| ----------:| ----------- | -------:| -------:| --------------------------------------- | ---------------------------------------- | ------------------------------------------ | --------------------------------------- |
| xSpeNam1.Bionano_hap1 |  1234.56 | 12.34 |   12 |  123 |   12 | 1.23    |       123.45 |   123.45 |         1 |    12.34 |       12 |       123.45 |   123.45 |        1 |     1.23 |       12 | 12.34 |      12.34 | 12.34       |    12.3 |    12.3 | ![](data/xSpeNam1.Bionano_hap1.hap.png) | ![](data/xSpeNam1.Bionano_hap1.both.png) | ![](data/xSpeNam1.Bionano_hap1.shared.png) | ![](data/xSpeNam1.Bionano_hap1.hic.png) |
| xSpeNam1.Bionano_hap2 |  1234.56 | 12.34 |   12 |  123 |   12 | 1.23    |       123.45 |   123.45 |         1 |    12.34 |       12 |       123.45 |   123.45 |        1 |     1.23 |       12 | 12.34 |      12.34 | 12.34       |    12.3 |    12.3 | ![](data/xSpeNam1.Bionano_hap2.hap.png) | ![](data/xSpeNam1.Bionano_hap2.both.png) | ![](data/xSpeNam1.Bionano_hap2.shared.png) | ![](data/xSpeNam1.Bionano_hap2.hic.png) |
|                       |          |       |      |      |      |         |              |          |           |          |          |              |          |          |          |          |       |            |             |         |         |                                         |                                          |                                            |                                         |
| xSpeNam1.YaHS_hap1    |  1234.56 | 12.34 |   12 |  123 |   12 | 1.23    |       123.45 |   123.45 |         1 |    12.34 |       12 |       123.45 |   123.45 |        1 |     1.23 |       12 | 12.34 |      12.34 | 12.34       |    12.3 |    12.3 | ![](data/xSpeNam1.YaHS_hap1.hap.png)    | ![](data/xSpeNam1.YaHS_hap1.both.png)    | ![](data/xSpeNam1.YaHS_hap1.shared.png)    | ![](data/xSpeNam1.YaHS_hap1.hic.png)    |
| xSpeNam1.YaHS_hap2    |  1234.56 | 12.34 |   12 |  123 |   12 | 1.23    |       123.45 |   123.45 |         1 |    12.34 |       12 |       123.45 |   123.45 |        1 |     1.23 |       12 | 12.34 |      12.34 | 12.34       |    12.3 |    12.3 | ![](data/xSpeNam1.YaHS_hap2.hap.png)    | ![](data/xSpeNam1.YaHS_hap2.both.png)    | ![](data/xSpeNam1.YaHS_hap2.shared.png)    | ![](data/xSpeNam1.YaHS_hap2.hic.png)    |


> **Observations:**
\```
None
\```

---

### *) Checklist

| Data       | Y/N | Comments |
| :--------- | --- | -------- |
| HiFi ≥ 25x |     |          |
| N50 ~15 kb |     |          |
|            |     |          |
| ONT ≥ 60x  |     |          |
| N50 ~30 kb |     |          |
|            |     |          |
| HiC ≥ 50x  |     |          |



| Final assembly metrics | Y/N | Comments |
| :--------------------- | --- | -------- |
| Contig N50 > 1 Mb      |     |          |
| Scaffold N50 > 10 Mb   |     |          |
| Kmer completness > 90% |     |          |
| QV > 40                |     |          |
| BUSCO single > 90%     |     |          |
| BUSCO duplicated < 5%  |     |          |

---

# EAR 👂

### Responsible:
### bla 
### bla
```
