### 1) Species Data

| ToLID            | mEleMax1        |
| :--------------- | :-------------- |
| Species          | Elephas maximus |
| Class            | Mammalia        |
| Exp. Genome size |                 |
| Exp. Chromosomes | 27+X+Y          |
| Karyotype        |                 |
| GoaT             | [link](https://goat.genomehubs.org/record?recordId=9783&result=taxon&taxonomy=ncbi#Elephas%20maximus) |

> **Observations:**
```
None
```

---

### 2) Data Profile

| Data           | Total reads (M) | Length (b) | Extra info |
| -------------- | --------------- | ---------- | --- |
| HiFi           | 11.2            | 16000      | {multiqc html link} |
|                |                 |            |     |
| ONT            | NA              |            |     |
| Illumina PE    | NA              |            |     |
|                |                 |            |     |
| HiC: Arima     | 906.6           | 150        | {multiqc html link} |
|                |                 |            |     |
| Other: Bionano |                 |            |     |


```
Tools employed: FastQC v0.11.9; Cutadapt v3.5; Fastp v0.23.2; MultiQC v1.11; SeqKit v2.3.0
```

> **Observations:** Samples obtained from frozen fibroblast cell pellets (-80C) from a deceased male adult Asian elephant (indicus)

---

### 3) Genome Profiling

| Estimation     | Value | Plot                    |
|:-------------- | ----- |:----------------------- |
| Size           |       | {genomescope2 plot}     |
| Heterozygosity |       | {genomescope2 plot log} |
| Ploidy         |       | {smudge plot}           |

> **Observations:**
```
None
```

---

### 4) Contigging/Purging

.checklist

> **Observations:**
```
None
```

---

### 5) Scaffolding

.checklist

> **Observations:**
```
None
```

---

### *) Checklist

| Data       | Y/N | Comments |
| ---------- | --- | -------- |
| HiFi ≥ 25x |     |          |
| N50 ~15 kb |     |          |
|            |     |          |
| ONT ≥ 60x  |     |          |
| N50 ~30 kb |     |          |
|            |     |          |
| HiC ≥ 50x  |     |          |



| Final assembly metrics | Y/N | Comments |
| ---------------------- | --- | -------- |
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



| ASM_ID            | Total Mb | Scaff | Cont | Gaps | Longest Scaff Mb | Scaff N50 | Scaff L50 | Scaff N95 | Scaff L95 | Longest Cont Mb | Cont N50 | Cont L50 | Cont N95 | Cont LG95 |    QV | KCompl | BUSCO-C % | BUSCO-S % | Hap                                  | both Hap                             | shared                               | pretext    |
|:----------------- | --------:| -----:| ----:| ----:| ----------------:| ---------:| ---------:| ---------:| ---------:| ---------------:| --------:| --------:| --------:| ---------:| -----:| ------:| ---------:| ---------:| ------------------------------------ | ------------------------------------ | ------------------------------------ | --- |
| l1_hap1.hap2      |  3,356.46 |  2,195 | 2,195 |    0 |           204.04 |     82.58 |        14 |         1 |       134 |          204.04 |    82.58 |       14 |        1 |       134 | 66.63 |  91.01 |        94 |      92.8 | ![](https://i.imgur.com/9HtzpOO.png) | ![](https://i.imgur.com/z5Fral3.png) | ![](https://i.imgur.com/JixOKp0.png) | -    |
| l1_hap2           |  3,550.68 |   835 |  835 |    0 |           310.11 |     81.09 |        13 |       1.6 |       112 |          310.11 |    81.09 |       13 |      1.6 |       112 | 68.26 |  95.53 |      96.1 |      95.1 | ![](https://i.imgur.com/MDczdrs.png) | -                                    | -                                    | -    |
