# Qwen Full Report

## 0. Dataset / Run Summary

- dataset_name: `Pan cancer mRNA`
- raw_shape: `(8314, 3217)`
- selected_sources: `{'ChEA': 2, 'MSigDB': 4, 'PanglaoDB': 1, 'Reactome': 6, 'RegNetwork': 3}`
- llm_selected_sources: `{'ChEA': 2, 'MSigDB': 2, 'PanglaoDB': 1, 'Reactome': 3, 'RegNetwork': 2}`
- qwen_model_name: `qwen3.5:9b`

## Cluster-wise Candidate Marker Genes

### cluster_module_0 | size=332
- CDX1
- NOX1
- GPA33
- CDX2

### cluster_module_1 | size=220
- VGLL1
- KRT81
- C5ORF46
- ELF5

### cluster_module_2 | size=505
- RFX4
- CACNG7
- OLIG2
- GFAP

### cluster_module_3 | size=316
- CFHR2
- SERPINC1
- APOC3
- ITIH1

### cluster_module_4 | size=94
- AIM2
- PLA2G2D
- FCRL3
- GZMK

### cluster_module_5 | size=403
- KLK9
- SBSN
- KRT6C
- HEPHL1

### cluster_module_6 | size=436
- SOX17
- SCGB2A1
- KLHL14
- EMX2

### cluster_module_7 | size=164
- CHGA
- CHRNA3
- TH
- SYT4

### cluster_module_8 | size=248
- SLC17A1
- ACSM2A
- SLC3A1
- GLYAT

### cluster_module_9 | size=363
- TG
- TSHR
- ZCCHC12
- NKX2-1

### cluster_module_10 | size=484
- KLK3
- KLK2
- NKX3-1
- KLK4

### cluster_module_11 | size=441
- NAPSA
- SFTPB
- SFTPA1
- SFTA2

### cluster_module_12 | size=257
- UPK2
- PLA2G2F
- UPK1A
- VGLL1

### cluster_module_13 | size=361
- SERPINB13
- SERPINB4
- KRT6A
- GPR87

### cluster_module_14 | size=163
- MPO
- NFE2
- FLT3
- SLC4A1

### cluster_module_15 | size=75
- TMEM213
- CLCNKB
- PVALB
- CLCNKA

### cluster_module_16 | size=137
- COL2A1
- EMILIN3
- FBN2
- DPYSL5

### cluster_module_17 | size=90
- MLANA
- TRPM1
- TYR
- PAX3

### cluster_module_18 | size=224
- EPS8L3
- MUC17
- LGALS4
- PDX1

### cluster_module_19 | size=72
- CRP
- GC
- VTN
- CPB2

### cluster_module_20 | size=477
- GBP6
- ADH7
- TP63
- SERPINB13

### cluster_module_21 | size=270
- GFPT2
- GAS1
- TBX18
- COL5A1

### cluster_module_22 | size=106
- L1TD1
- POU5F1
- NLRP7
- LIN28B

### cluster_module_23 | size=609
- LMX1B
- GATA3
- ANKRD30A
- ESR1

### cluster_module_24 | size=110
- PAX1
- CCL25
- FAM163A
- FOXN1

### cluster_module_25 | size=312
- PAX3
- TYR
- SOX10
- MLANA

### cluster_module_26 | size=292
- EPS8L3
- MUC13
- PDX1
- TRIM31

### cluster_module_27 | size=75
- NR5A1
- STAR
- CYP11A1
- CYP17A1

### cluster_module_28 | size=169
- CHST4
- CASR
- TFF2
- TM4SF4

### cluster_module_29 | size=300
- SLC28A1
- SLC22A2
- SLC3A1
- ENPEP

### cluster_module_30 | size=130
- TPO
- TG
- TSHR
- SLC26A7

### cluster_module_31 | size=79
- JPH2
- LMOD1
- SYNPO2
- HSPB7

## Candidate Genes

- CDX1
- NOX1
- GPA33
- CDX2
- VGLL1
- KRT81
- C5ORF46
- ELF5
- RFX4
- CACNG7
- OLIG2
- GFAP
- CFHR2
- SERPINC1
- APOC3
- ITIH1
- AIM2
- PLA2G2D
- FCRL3
- GZMK
- KLK9
- SBSN
- KRT6C
- HEPHL1
- SOX17
- SCGB2A1
- KLHL14
- EMX2
- CHGA
- CHRNA3
- TH
- SYT4
- SLC17A1
- ACSM2A
- SLC3A1
- GLYAT
- TG
- TSHR
- ZCCHC12
- NKX2-1
- KLK3
- KLK2
- NKX3-1
- KLK4
- NAPSA
- SFTPB
- SFTPA1
- SFTA2
- UPK2
- PLA2G2F
- UPK1A
- SERPINB13
- SERPINB4
- KRT6A
- GPR87
- MPO
- NFE2
- FLT3
- SLC4A1
- TMEM213
- CLCNKB
- PVALB
- CLCNKA
- COL2A1
- EMILIN3
- FBN2
- DPYSL5
- MLANA
- TRPM1
- TYR
- PAX3
- EPS8L3
- MUC17
- LGALS4
- PDX1
- CRP
- GC
- VTN
- CPB2
- GBP6
- ADH7
- TP63
- GFPT2
- GAS1
- TBX18
- COL5A1
- L1TD1
- POU5F1
- NLRP7
- LIN28B
- LMX1B
- GATA3
- ANKRD30A
- ESR1
- PAX1
- CCL25
- FAM163A
- FOXN1
- SOX10
- MUC13
- TRIM31
- NR5A1
- STAR
- CYP11A1
- CYP17A1
- CHST4
- CASR
- TFF2
- TM4SF4
- SLC28A1
- SLC22A2
- ENPEP
- TPO
- SLC26A7
- JPH2
- LMOD1
- SYNPO2
- HSPB7
- COL4A5
- COL4A6
- COL5A2
- TCERG1L
- COL6A3
- COL6A6
- COL7A1
- COL8A1
- COL9A1
- COL9A2


## Retrieved Knowledge Chunks

### Chunk 1
- source: ChEA
- type: tf_target_set
- title: ChEA term SUZ12 20075857 ChIP-Seq MESCs Mouse
- genes: CASR, CDX1, CDX2, CHGA, CHRNA3, COL2A1, COL5A1, COL7A1, COL9A2, DPYSL5, EMILIN3, EMX2, FAM163A, FBN2, FLT3, GAS1, GATA3, GFAP, KLHL14, LMX1B, NKX2-1, NKX3-1, NR5A1, OLIG2, PAX1, PAX3, PDX1, PVALB, RFX4, SOX10, SOX17, SYNPO2, TBX18, TCERG1L, TSHR, VTN

#### text

```
ChEA tf_target_set ChEA term SUZ12 20075857 ChIP-Seq MESCs Mouse 候选基因交集：CASR, CDX1, CDX2, CHGA, CHRNA3, COL2A1, COL5A1, COL7A1, COL9A2, DPYSL5, EMILIN3, EMX2, FAM163A, FBN2, FLT3, 
```


### Chunk 2
- source: ChEA
- type: tf_target_set
- title: ChEA term EGR1 20690147 ChIP-Seq ERYTHROLEUKEMIA Human
- genes: APOC3, CHGA, CLCNKB, COL5A1, COL7A1, COL9A1, DPYSL5, ELF5, EMILIN3, EMX2, ESR1, FOXN1, GFAP, GPA33, KLHL14, KLK4, L1TD1, LMOD1, LMX1B, MPO, MUC17, NAPSA, NKX3-1, NR5A1, OLIG2, RFX4, SBSN, SLC28A1, SLC4A1, TCERG1L, TYR, ZCCHC12

#### text

```
ChEA tf_target_set ChEA term EGR1 20690147 ChIP-Seq ERYTHROLEUKEMIA Human 候选基因交集：APOC3, CHGA, CLCNKB, COL5A1, COL7A1, COL9A1, DPYSL5, ELF5, EMILIN3, EMX2, ESR1, FOXN1, GFAP, GPA33,
```


### Chunk 3
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_POSITIVE_REGULATION_OF_RNA_METABOLIC_PROCESS
- genes: CDX1, CDX2, ELF5, ESR1, FOXN1, GATA3, LIN28B, LMX1B, NFE2, NKX2-1, NKX3-1, NR5A1, OLIG2, PAX3, PDX1, POU5F1, RFX4, SOX10, SOX17, TBX18, TP63, TRIM31, VGLL1

#### text

```
MSigDB gene_set MSigDB gene set GOBP_POSITIVE_REGULATION_OF_RNA_METABOLIC_PROCESS 候选基因交集：CDX1, CDX2, ELF5, ESR1, FOXN1, GATA3, LIN28B, LMX1B, NFE2, NKX2-1, NKX3-1, NR5A1, OLIG2, PA
```


### Chunk 4
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_BIOLOGICAL_PROCESS_INVOLVED_IN_INTERSPECIES_INTERACTION_BETWEEN_ORGANISMS
- genes: ADH7, AIM2, CASR, CCL25, CFHR2, CHGA, CRP, ESR1, FCRL3, GATA3, GBP6, GZMK, KLK3, KRT6A, LGALS4, MPO, NLRP7, PLA2G2F, SERPINB4, TRIM31

#### text

```
MSigDB gene_set MSigDB gene set GOBP_BIOLOGICAL_PROCESS_INVOLVED_IN_INTERSPECIES_INTERACTION_BETWEEN_ORGANISMS 候选基因交集：ADH7, AIM2, CASR, CCL25, CFHR2, CHGA, CRP, ESR1, FCRL3, GATA3,
```


### Chunk 5
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_ANIMAL_ORGAN_MORPHOGENESIS
- genes: CDX1, CDX2, COL2A1, COL5A1, COL5A2, COL8A1, COL9A1, EMX2, ESR1, FBN2, FOXN1, GATA3, KLK4, NKX2-1, NKX3-1, PAX3, PDX1, POU5F1, SFTPB, SOX17, TBX18, TH

#### text

```
MSigDB gene_set MSigDB gene set GOBP_ANIMAL_ORGAN_MORPHOGENESIS 候选基因交集：CDX1, CDX2, COL2A1, COL5A1, COL5A2, COL8A1, COL9A1, EMX2, ESR1, FBN2, FOXN1, GATA3, KLK4, NKX2-1, NKX3-1, PAX3, PDX1, POU5F1, SFTPB, SOX17, TBX18, TH
```


### Chunk 6
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_POSITIVE_REGULATION_OF_MULTICELLULAR_ORGANISMAL_PROCESS
- genes: AIM2, CASR, CHGA, FBN2, FCRL3, FOXN1, GATA3, GFAP, NKX3-1, NLRP7, NOX1, NR5A1, OLIG2, POU5F1, SOX10, TP63, TSHR, VTN

#### text

```
MSigDB gene_set MSigDB gene set GOBP_POSITIVE_REGULATION_OF_MULTICELLULAR_ORGANISMAL_PROCESS 候选基因交集：AIM2, CASR, CHGA, FBN2, FCRL3, FOXN1, GATA3, GFAP, NKX3-1, NLRP7, NOX1, NR5A1, OLIG2, POU5F1, SOX10, TP63, TSHR, VTN
```


### Chunk 7
- source: PanglaoDB
- type: cell_type_marker
- title: PanglaoDB markers for Enterocytes
- genes: APOC3, CCL25, CDX1, CDX2, MUC13, SLC28A1, SOX10

#### text

```
PanglaoDB cell_type_marker PanglaoDB markers for Enterocytes 候选基因交集：APOC3, CCL25, CDX1, CDX2, MUC13, SLC28A1, SOX10
```


### Chunk 8
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Developmental Biology
- genes: CDX2, COL2A1, COL4A5, COL5A1, COL5A2, COL6A3, COL6A6, COL9A1, COL9A2, DPYSL5, EMX2, GATA3, KRT6A, KRT6C, KRT81, MLANA, NR5A1, PAX3, PDX1, POU5F1, SOX10, SOX17, TRPM1, TYR, VTN

#### text

```
Reactome pathway_gene_set Reactome pathway Developmental Biology 候选基因交集：CDX2, COL2A1, COL4A5, COL5A1, COL5A2, COL6A3, COL6A6, COL9A1, COL9A2, DPYSL5, EMX2, GATA3, KRT6A, KRT6C, KRT
```


### Chunk 9
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Signal Transduction
- genes: CASR, CCL25, COL2A1, COL4A5, COL5A1, COL5A2, COL6A3, COL6A6, COL9A1, COL9A2, ESR1, FLT3, GAS1, GATA3, GFAP, KLK2, KLK3, MUC13, NOX1, SOX17, TSHR

#### text

```
Reactome pathway_gene_set Reactome pathway Signal Transduction 候选基因交集：CASR, CCL25, COL2A1, COL4A5, COL5A1, COL5A2, COL6A3, COL6A6, COL9A1, COL9A2, ESR1, FLT3, GAS1, GATA3, GFAP, KL
```


### Chunk 10
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Disease
- genes: COL4A5, COL4A6, COL5A1, COL5A2, CYP11A1, CYP17A1, ESR1, FLT3, GBP6, MUC13, MUC17, NOX1, SFTPA1, SFTPB, SLC3A1, SLC4A1, UPK1A, VTN

#### text

```
Reactome pathway_gene_set Reactome pathway Disease 候选基因交集：COL4A5, COL4A6, COL5A1, COL5A2, CYP11A1, CYP17A1, ESR1, FLT3, GBP6, MUC13, MUC17, NOX1, SFTPA1, SFTPB, SLC3A1, SLC4A1, UPK
```


### Chunk 11
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Immune System
- genes: AIM2, CFHR2, CHGA, COL2A1, CPB2, CRP, FLT3, GATA3, GBP6, MPO, MUC13, MUC17, SFTPA1, TRIM31, VTN

#### text

```
Reactome pathway_gene_set Reactome pathway Immune System 候选基因交集：AIM2, CFHR2, CHGA, COL2A1, CPB2, CRP, FLT3, GATA3, GBP6, MPO, MUC13, MUC17, SFTPA1, TRIM31, VTN
```


### Chunk 12
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Transport of small molecules
- genes: APOC3, CLCNKA, CLCNKB, SLC17A1, SLC22A2, SLC26A7, SLC28A1, SLC3A1, SLC4A1, TRPM1

#### text

```
Reactome pathway_gene_set Reactome pathway Transport of small molecules 候选基因交集：APOC3, CLCNKA, CLCNKB, SLC17A1, SLC22A2, SLC26A7, SLC28A1, SLC3A1, SLC4A1, TRPM1
```


### Chunk 13
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Innate Immune System
- genes: AIM2, CFHR2, CHGA, CPB2, CRP, MPO, MUC13, MUC17, SFTPA1, VTN

#### text

```
Reactome pathway_gene_set Reactome pathway Innate Immune System 候选基因交集：AIM2, CFHR2, CHGA, CPB2, CRP, MPO, MUC13, MUC17, SFTPA1, VTN
```


### Chunk 14
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator AR
- genes: KLK2, KLK3, NKX2-1, NOX1, POU5F1, SFTPB, TG, TPO

#### text

```
RegNetwork regulator_targets RegNetwork regulator AR 候选基因交集：KLK2, KLK3, NKX2-1, NOX1, POU5F1, SFTPB, TG, TPO
```


### Chunk 15
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator RARA
- genes: ESR1, NKX2-1, POU5F1, SFTPB, TG, TPO

#### text

```
RegNetwork regulator_targets RegNetwork regulator RARA 候选基因交集：ESR1, NKX2-1, POU5F1, SFTPB, TG, TPO
```


### Chunk 16
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator SP3
- genes: COL2A1, CYP11A1, CYP17A1, ESR1, KLK3, POU5F1

#### text

```
RegNetwork regulator_targets RegNetwork regulator SP3 候选基因交集：COL2A1, CYP11A1, CYP17A1, ESR1, KLK3, POU5F1
```


## LLM Selected Chunks

### LLM Chunk 1
- source: ChEA
- type: tf_target_set
- title: ChEA term SUZ12 20075857 ChIP-Seq MESCs Mouse
- genes: CASR, CDX1, CDX2, CHGA, CHRNA3, COL2A1, COL5A1, COL7A1, COL9A2, DPYSL5, EMILIN3, EMX2, FAM163A, FBN2, FLT3, GAS1, GATA3, GFAP, KLHL14, LMX1B, NKX2-1, NKX3-1, NR5A1, OLIG2, PAX1, PAX3, PDX1, PVALB, RFX4, SOX10, SOX17, SYNPO2, TBX18, TCERG1L, TSHR, VTN

#### text

```
ChEA tf_target_set ChEA term SUZ12 20075857 ChIP-Seq MESCs Mouse 候选基因交集：CASR, CDX1, CDX2, CHGA, CHRNA3, COL2A1, COL5A1, COL7A1, COL9A2, DPYSL5, EMILIN3, EMX2, FAM163A, FBN2, FLT3, 
```


### LLM Chunk 2
- source: ChEA
- type: tf_target_set
- title: ChEA term EGR1 20690147 ChIP-Seq ERYTHROLEUKEMIA Human
- genes: APOC3, CHGA, CLCNKB, COL5A1, COL7A1, COL9A1, DPYSL5, ELF5, EMILIN3, EMX2, ESR1, FOXN1, GFAP, GPA33, KLHL14, KLK4, L1TD1, LMOD1, LMX1B, MPO, MUC17, NAPSA, NKX3-1, NR5A1, OLIG2, RFX4, SBSN, SLC28A1, SLC4A1, TCERG1L, TYR, ZCCHC12

#### text

```
ChEA tf_target_set ChEA term EGR1 20690147 ChIP-Seq ERYTHROLEUKEMIA Human 候选基因交集：APOC3, CHGA, CLCNKB, COL5A1, COL7A1, COL9A1, DPYSL5, ELF5, EMILIN3, EMX2, ESR1, FOXN1, GFAP, GPA33,
```


### LLM Chunk 3
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_POSITIVE_REGULATION_OF_RNA_METABOLIC_PROCESS
- genes: CDX1, CDX2, ELF5, ESR1, FOXN1, GATA3, LIN28B, LMX1B, NFE2, NKX2-1, NKX3-1, NR5A1, OLIG2, PAX3, PDX1, POU5F1, RFX4, SOX10, SOX17, TBX18, TP63, TRIM31, VGLL1

#### text

```
MSigDB gene_set MSigDB gene set GOBP_POSITIVE_REGULATION_OF_RNA_METABOLIC_PROCESS 候选基因交集：CDX1, CDX2, ELF5, ESR1, FOXN1, GATA3, LIN28B, LMX1B, NFE2, NKX2-1, NKX3-1, NR5A1, OLIG2, PA
```


### LLM Chunk 4
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_BIOLOGICAL_PROCESS_INVOLVED_IN_INTERSPECIES_INTERACTION_BETWEEN_ORGANISMS
- genes: ADH7, AIM2, CASR, CCL25, CFHR2, CHGA, CRP, ESR1, FCRL3, GATA3, GBP6, GZMK, KLK3, KRT6A, LGALS4, MPO, NLRP7, PLA2G2F, SERPINB4, TRIM31

#### text

```
MSigDB gene_set MSigDB gene set GOBP_BIOLOGICAL_PROCESS_INVOLVED_IN_INTERSPECIES_INTERACTION_BETWEEN_ORGANISMS 候选基因交集：ADH7, AIM2, CASR, CCL25, CFHR2, CHGA, CRP, ESR1, FCRL3, GATA3,
```


### LLM Chunk 5
- source: PanglaoDB
- type: cell_type_marker
- title: PanglaoDB markers for Enterocytes
- genes: APOC3, CCL25, CDX1, CDX2, MUC13, SLC28A1, SOX10

#### text

```
PanglaoDB cell_type_marker PanglaoDB markers for Enterocytes 候选基因交集：APOC3, CCL25, CDX1, CDX2, MUC13, SLC28A1, SOX10
```


### LLM Chunk 6
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Developmental Biology
- genes: CDX2, COL2A1, COL4A5, COL5A1, COL5A2, COL6A3, COL6A6, COL9A1, COL9A2, DPYSL5, EMX2, GATA3, KRT6A, KRT6C, KRT81, MLANA, NR5A1, PAX3, PDX1, POU5F1, SOX10, SOX17, TRPM1, TYR, VTN

#### text

```
Reactome pathway_gene_set Reactome pathway Developmental Biology 候选基因交集：CDX2, COL2A1, COL4A5, COL5A1, COL5A2, COL6A3, COL6A6, COL9A1, COL9A2, DPYSL5, EMX2, GATA3, KRT6A, KRT6C, KRT
```


### LLM Chunk 7
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Signal Transduction
- genes: CASR, CCL25, COL2A1, COL4A5, COL5A1, COL5A2, COL6A3, COL6A6, COL9A1, COL9A2, ESR1, FLT3, GAS1, GATA3, GFAP, KLK2, KLK3, MUC13, NOX1, SOX17, TSHR

#### text

```
Reactome pathway_gene_set Reactome pathway Signal Transduction 候选基因交集：CASR, CCL25, COL2A1, COL4A5, COL5A1, COL5A2, COL6A3, COL6A6, COL9A1, COL9A2, ESR1, FLT3, GAS1, GATA3, GFAP, KL
```


### LLM Chunk 8
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Disease
- genes: COL4A5, COL4A6, COL5A1, COL5A2, CYP11A1, CYP17A1, ESR1, FLT3, GBP6, MUC13, MUC17, NOX1, SFTPA1, SFTPB, SLC3A1, SLC4A1, UPK1A, VTN

#### text

```
Reactome pathway_gene_set Reactome pathway Disease 候选基因交集：COL4A5, COL4A6, COL5A1, COL5A2, CYP11A1, CYP17A1, ESR1, FLT3, GBP6, MUC13, MUC17, NOX1, SFTPA1, SFTPB, SLC3A1, SLC4A1, UPK
```


### LLM Chunk 9
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator AR
- genes: KLK2, KLK3, NKX2-1, NOX1, POU5F1, SFTPB, TG, TPO

#### text

```
RegNetwork regulator_targets RegNetwork regulator AR 候选基因交集：KLK2, KLK3, NKX2-1, NOX1, POU5F1, SFTPB, TG, TPO
```


### LLM Chunk 10
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator RARA
- genes: ESR1, NKX2-1, POU5F1, SFTPB, TG, TPO

#### text

```
RegNetwork regulator_targets RegNetwork regulator RARA 候选基因交集：ESR1, NKX2-1, POU5F1, SFTPB, TG, TPO
```


## Qwen Prompt

```
You are a biomedical reasoning model for DEEPSEARCH-based clustering prior generation.

Goal:
Use multi-source evidence (local biological DB chunks + online PubMed/STRING evidence)
to propose structured priors that can improve cluster separability for the current dataset.

IMPORTANT:
- Think about regulators, pathways, network neighbors, subtype separation, heterogeneity.
- Prefer genes supported by multiple evidence sources.
- Use ONLY genes from CANDIDATE_GENES unless a gene is strongly supported and appears in EVIDENCE_GENES.

Return EXACTLY one JSON object, no markdown, no explanation.

Schema:
{
  "global_gene_weights": [{"gene": "TP53", "weight": 1.2, "reason": "multi-source evidence"}],
  "suppress_genes": ["RPL27"],
  "modules": [{"name": "module_1", "genes": ["TP53","GATA3","ESR1"], "weight": 1.1, "reason": "same regulatory/pathway axis"}],
  "prototypes": [  {
    "name": "prototype_1",
    "genes_up": ["CANDIDATE_GENE_A", "CANDIDATE_GENE_B"],
    "genes_down": ["CANDIDATE_GENE_C"]
  }
],
  "key_gene_sets": ["EMT_like_program"],
  "key_regulators": ["GATA3","ESR1"],
  "notes": ["brief notes"]
}

Rules:
- global_gene_weights MUST contain exactly 12 genes.
- Every gene appearing anywhere in JSON MUST be selected from CANDIDATE_GENES.
- This applies to global_gene_weights, modules.genes, prototypes.genes_up, prototypes.genes_down, key_regulators, and suppress_genes.
- Do NOT output textbook genes if they are not in CANDIDATE_GENES.
- If a useful marker is absent from CANDIDATE_GENES, omit it.
- Do not output genes outside CANDIDATE_GENES.
- Each reason must be <= 12 words.
- modules must contain at most 2 modules.
- prototypes must contain at most 1 prototype.
- suppress_genes should be [] unless clear technical artifact.
- Return complete JSON. Do not stop before closing all brackets.
- Emphasize genes/modules that are useful for clustering/subtype separation, not merely abundant genes.
- prototypes format:
  {"name":"prototype_1","genes_up":["CANDIDATE_GENE_A","CANDIDATE_GENE_B"],"genes_down":["CANDIDATE_GENE_C"]}
- CRITICAL: The goal is label-discriminative clustering, not generic biological annotation.
- Use current dataset evidence first: cluster_marker_genes, top_var_genes, top_presence_genes, and CANDIDATE_GENES.
- External biological knowledge should refine dataset-supported genes, not replace them.
- Prefer genes/modules/prototypes that are both biologically meaningful and supported by current dataset statistics.
- Do NOT suppress high-variance genes unless they are clear technical artifacts.
- suppress_genes should usually be empty.
- For cancer or bulk RNA datasets, avoid priors dominated by immune/stromal/microenvironment signals unless they are necessary for class separation.
- For single-cell datasets such as PBMC, lung, liver, pancreas, and melanoma, cell-type marker programs are allowed if they correspond to real cell-type separation.
- prototypes should represent discriminative axes in the current dataset, not fixed BRCA textbook subtypes.
- Do NOT output template-like priors copied from the schema examples.
- Avoid generating priors dominated by immune/stromal composition.
- Current dataset evidence has absolute priority.
- External biomarkers not appearing in candidate genes should have low confidence.
- Never replace dataset-supported genes using textbook subtype markers.
- DO NOT use high-variance genes unless they are supported by:
    regulator evidence
    pathway evidence
    STRING evidence
    literature evidence
- High variance alone is insufficient.
- Prefer genes supported by biologically distinct evidence sources.
- Repeated evidence from the same semantic category or same gene family does NOT count as strong support.
- Avoid priors dominated by one biological theme; select genes from diverse discriminative axes.
- CLUSTER_MARKER_BLOCKS show markers grouped by unsupervised clusters.
- Select genes from multiple cluster blocks when evidence supports them.
- Do NOT select all genes from only the first or strongest lineage block.
- A gene is stronger if it is both cluster-specific and supported by external evidence.
- For cancer datasets:
    prioritize subtype discriminative genes
- Ignore housekeeping genes.
- Ignore generic stromal markers.
- Ignore generic immune abundance markers.
- Distinguish:
    subtype marker
    microenvironment marker
    bulk composition marker
- subtype markers are preferred
- global_gene_weights MUST be a list of objects. It MUST NOT be a list of strings.
- Correct global_gene_weights format:
  {"gene": "ESR1", "weight": 1.20, "reason": "supported by subtype evidence and network evidence"}
- Incorrect global_gene_weights format:
  "ESR1"
- Incorrect global_gene_weights format:
  ["ESR1", "GATA3"]
- Each global_gene_weights item MUST contain exactly gene, weight, and reason.
- The weight field MUST be numeric.
- Do not include a gene if you cannot assign a numeric weight and a reason.
- CANDIDATE_GENE_A/B/C are placeholders in the schema only.
- In the actual output, replace them with real genes from CANDIDATE_GENES.
- Do not copy placeholder names.
- Every gene appearing anywhere in JSON must come from CANDIDATE_GENES.
- If no valid down-regulated candidate gene exists, use "genes_down": [].

Dataset summary:
- disease_context=pan-cancer tumor heterogeneity immune stromal proliferation metabolic lineage programs
- n_samples=8314
- n_genes=19264
- cluster_count=32
- candidate_gene_count=128
- high variance genes=['COL4A5', 'COL4A6', 'COL5A1', 'COL5A2', 'TCERG1L', 'COL6A3', 'COL6A6', 'COL7A1', 'COL8A1', 'COL9A1', 'COL9A2', 'COL9A3', 'COLEC11', 'COLEC12', 'PCSK6', 'KANK4', 'TCEAL2', 'COMP', 'TC2N', 'JSRP1']

CLUSTER_MARKER_BLOCKS:
- cluster_module_0 | size=332: ['CDX1', 'NOX1', 'GPA33', 'CDX2']
- cluster_module_1 | size=220: ['VGLL1', 'KRT81', 'C5ORF46', 'ELF5']
- cluster_module_2 | size=505: ['RFX4', 'CACNG7', 'OLIG2', 'GFAP']
- cluster_module_3 | size=316: ['CFHR2', 'SERPINC1', 'APOC3', 'ITIH1']
- cluster_module_4 | size=94: ['AIM2', 'PLA2G2D', 'FCRL3', 'GZMK']
- cluster_module_5 | size=403: ['KLK9', 'SBSN', 'KRT6C', 'HEPHL1']
- cluster_module_6 | size=436: ['SOX17', 'SCGB2A1', 'KLHL14', 'EMX2']
- cluster_module_7 | size=164: ['CHGA', 'CHRNA3', 'TH', 'SYT4']
- cluster_module_8 | size=248: ['SLC17A1', 'ACSM2A', 'SLC3A1', 'GLYAT']
- cluster_module_9 | size=363: ['TG', 'TSHR', 'ZCCHC12', 'NKX2-1']
- cluster_module_10 | size=484: ['KLK3', 'KLK2', 'NKX3-1', 'KLK4']
- cluster_module_11 | size=441: ['NAPSA', 'SFTPB', 'SFTPA1', 'SFTA2']
- cluster_module_12 | size=257: ['UPK2', 'PLA2G2F', 'UPK1A', 'VGLL1']
- cluster_module_13 | size=361: ['SERPINB13', 'SERPINB4', 'KRT6A', 'GPR87']
- cluster_module_14 | size=163: ['MPO', 'NFE2', 'FLT3', 'SLC4A1']
- cluster_module_15 | size=75: ['TMEM213', 'CLCNKB', 'PVALB', 'CLCNKA']
- cluster_module_16 | size=137: ['COL2A1', 'EMILIN3', 'FBN2', 'DPYSL5']
- cluster_module_17 | size=90: ['MLANA', 'TRPM1', 'TYR', 'PAX3']
- cluster_module_18 | size=224: ['EPS8L3', 'MUC17', 'LGALS4', 'PDX1']
- cluster_module_19 | size=72: ['CRP', 'GC', 'VTN', 'CPB2']
- cluster_module_20 | size=477: ['GBP6', 'ADH7', 'TP63', 'SERPINB13']
- cluster_module_21 | size=270: ['GFPT2', 'GAS1', 'TBX18', 'COL5A1']
- cluster_module_22 | size=106: ['L1TD1', 'POU5F1', 'NLRP7', 'LIN28B']
- cluster_module_23 | size=609: ['LMX1B', 'GATA3', 'ANKRD30A', 'ESR1']
- cluster_module_24 | size=110: ['PAX1', 'CCL25', 'FAM163A', 'FOXN1']
- cluster_module_25 | size=312: ['PAX3', 'TYR', 'SOX10', 'MLANA']
- cluster_module_26 | size=292: ['EPS8L3', 'MUC13', 'PDX1', 'TRIM31']
- cluster_module_27 | size=75: ['NR5A1', 'STAR', 'CYP11A1', 'CYP17A1']
- cluster_module_28 | size=169: ['CHST4', 'CASR', 'TFF2', 'TM4SF4']
- cluster_module_29 | size=300: ['SLC28A1', 'SLC22A2', 'SLC3A1', 'ENPEP']
- cluster_module_30 | size=130: ['TPO', 'TG', 'TSHR', 'SLC26A7']
- cluster_module_31 | size=79: ['JPH2', 'LMOD1', 'SYNPO2', 'HSPB7']

CANDIDATE_GENES:
['CDX1', 'NOX1', 'GPA33', 'CDX2', 'VGLL1', 'KRT81', 'C5ORF46', 'ELF5', 'RFX4', 'CACNG7', 'OLIG2', 'GFAP', 'CFHR2', 'SERPINC1', 'APOC3', 'ITIH1', 'AIM2', 'PLA2G2D', 'FCRL3', 'GZMK', 'KLK9', 'SBSN', 'KRT6C', 'HEPHL1', 'SOX17', 'SCGB2A1', 'KLHL14', 'EMX2', 'CHGA', 'CHRNA3', 'TH', 'SYT4', 'SLC17A1', 'ACSM2A', 'SLC3A1', 'GLYAT', 'TG', 'TSHR', 'ZCCHC12', 'NKX2-1', 'KLK3', 'KLK2', 'NKX3-1', 'KLK4', 'NAPSA', 'SFTPB', 'SFTPA1', 'SFTA2', 'UPK2', 'PLA2G2F', 'UPK1A', 'SERPINB13', 'SERPINB4', 'KRT6A', 'GPR87', 'MPO', 'NFE2', 'FLT3', 'SLC4A1', 'TMEM213', 'CLCNKB', 'PVALB', 'CLCNKA', 'COL2A1', 'EMILIN3', 'FBN2', 'DPYSL5', 'MLANA', 'TRPM1', 'TYR', 'PAX3', 'EPS8L3', 'MUC17', 'LGALS4', 'PDX1', 'CRP', 'GC', 'VTN', 'CPB2', 'GBP6', 'ADH7', 'TP63', 'GFPT2', 'GAS1', 'TBX18', 'COL5A1', 'L1TD1', 'POU5F1', 'NLRP7', 'LIN28B', 'LMX1B', 'GATA3', 'ANKRD30A', 'ESR1', 'PAX1', 'CCL25', 'FAM163A', 'FOXN1', 'SOX10', 'MUC13', 'TRIM31', 'NR5A1', 'STAR', 'CYP11A1', 'CYP17A1', 'CHST4', 'CASR', 'TFF2', 'TM4SF4', 'SLC28A1', 'SLC22A2', 'ENPEP', 'TPO', 'SLC26A7', 'JPH2', 'LMOD1', 'SYNPO2', 'HSPB7', 'COL4A5', 'COL4A6', 'COL5A2', 'TCERG1L', 'COL6A3', 'COL6A6', 'COL7A1', 'COL8A1', 'COL9A1', 'COL9A2']

[EVIDENCE 1] source=ChEA type=tf_target_set title=ChEA term SUZ12 20075857 ChIP-Seq MESCs Mouse
GENES=['CASR', 'CDX1', 'CDX2', 'CHGA', 'CHRNA3', 'COL2A1', 'COL5A1', 'COL7A1', 'COL9A2', 'DPYSL5', 'EMILIN3', 'EMX2']
ChEA tf_target_set ChEA term SUZ12 20075857 ChIP-Seq MESCs Mouse 候选基因交集：CASR, CDX1, CDX2, CHGA, CHRNA3, COL2A1, COL5A1, COL7A1, COL9A2, DPYSL5, EMILIN3, EMX2, FAM163A, FBN2, FLT3, 

[EVIDENCE 2] source=ChEA type=tf_target_set title=ChEA term EGR1 20690147 ChIP-Seq ERYTHROLEUKEMIA Human
GENES=['APOC3', 'CHGA', 'CLCNKB', 'COL5A1', 'COL7A1', 'COL9A1', 'DPYSL5', 'ELF5', 'EMILIN3', 'EMX2', 'ESR1', 'FOXN1']
ChEA tf_target_set ChEA term EGR1 20690147 ChIP-Seq ERYTHROLEUKEMIA Human 候选基因交集：APOC3, CHGA, CLCNKB, COL5A1, COL7A1, COL9A1, DPYSL5, ELF5, EMILIN3, EMX2, ESR1, FOXN1, GFAP, GPA33,

[EVIDENCE 3] source=MSigDB type=gene_set title=MSigDB gene set GOBP_POSITIVE_REGULATION_OF_RNA_METABOLIC_PROCESS
GENES=['CDX1', 'CDX2', 'ELF5', 'ESR1', 'FOXN1', 'GATA3', 'LIN28B', 'LMX1B', 'NFE2', 'NKX2-1', 'NKX3-1', 'NR5A1']
MSigDB gene_set MSigDB gene set GOBP_POSITIVE_REGULATION_OF_RNA_METABOLIC_PROCESS 候选基因交集：CDX1, CDX2, ELF5, ESR1, FOXN1, GATA3, LIN28B, LMX1B, NFE2, NKX2-1, NKX3-1, NR5A1, OLIG2, PA

[EVIDENCE 4] source=MSigDB type=gene_set title=MSigDB gene set GOBP_BIOLOGICAL_PROCESS_INVOLVED_IN_INTERSPECIES_INTERACTION_BETWEEN_ORGANISMS
GENES=['ADH7', 'AIM2', 'CASR', 'CCL25', 'CFHR2', 'CHGA', 'CRP', 'ESR1', 'FCRL3', 'GATA3', 'GBP6', 'GZMK']
MSigDB gene_set MSigDB gene set GOBP_BIOLOGICAL_PROCESS_INVOLVED_IN_INTERSPECIES_INTERACTION_BETWEEN_ORGANISMS 候选基因交集：ADH7, AIM2, CASR, CCL25, CFHR2, CHGA, CRP, ESR1, FCRL3, GATA3,

[EVIDENCE 5] source=PanglaoDB type=cell_type_marker title=PanglaoDB markers for Enterocytes
GENES=['APOC3', 'CCL25', 'CDX1', 'CDX2', 'MUC13', 'SLC28A1', 'SOX10']
PanglaoDB cell_type_marker PanglaoDB markers for Enterocytes 候选基因交集：APOC3, CCL25, CDX1, CDX2, MUC13, SLC28A1, SOX10

[EVIDENCE 6] source=Reactome type=pathway_gene_set title=Reactome pathway Developmental Biology
GENES=['CDX2', 'COL2A1', 'COL4A5', 'COL5A1', 'COL5A2', 'COL6A3', 'COL6A6', 'COL9A1', 'COL9A2', 'DPYSL5', 'EMX2', 'GATA3']
Reactome pathway_gene_set Reactome pathway Developmental Biology 候选基因交集：CDX2, COL2A1, COL4A5, COL5A1, COL5A2, COL6A3, COL6A6, COL9A1, COL9A2, DPYSL5, EMX2, GATA3, KRT6A, KRT6C, KRT

[EVIDENCE 7] source=Reactome type=pathway_gene_set title=Reactome pathway Signal Transduction
GENES=['CASR', 'CCL25', 'COL2A1', 'COL4A5', 'COL5A1', 'COL5A2', 'COL6A3', 'COL6A6', 'COL9A1', 'COL9A2', 'ESR1', 'FLT3']
Reactome pathway_gene_set Reactome pathway Signal Transduction 候选基因交集：CASR, CCL25, COL2A1, COL4A5, COL5A1, COL5A2, COL6A3, COL6A6, COL9A1, COL9A2, ESR1, FLT3, GAS1, GATA3, GFAP, KL

[EVIDENCE 8] source=Reactome type=pathway_gene_set title=Reactome pathway Disease
GENES=['COL4A5', 'COL4A6', 'COL5A1', 'COL5A2', 'CYP11A1', 'CYP17A1', 'ESR1', 'FLT3', 'GBP6', 'MUC13', 'MUC17', 'NOX1']
Reactome pathway_gene_set Reactome pathway Disease 候选基因交集：COL4A5, COL4A6, COL5A1, COL5A2, CYP11A1, CYP17A1, ESR1, FLT3, GBP6, MUC13, MUC17, NOX1, SFTPA1, SFTPB, SLC3A1, SLC4A1, UPK

[EVIDENCE 9] source=RegNetwork type=regulator_targets title=RegNetwork regulator AR
GENES=['KLK2', 'KLK3', 'NKX2-1', 'NOX1', 'POU5F1', 'SFTPB', 'TG', 'TPO']
RegNetwork regulator_targets RegNetwork regulator AR 候选基因交集：KLK2, KLK3, NKX2-1, NOX1, POU5F1, SFTPB, TG, TPO

[EVIDENCE 10] source=RegNetwork type=regulator_targets title=RegNetwork regulator RARA
GENES=['ESR1', 'NKX2-1', 'POU5F1', 'SFTPB', 'TG', 'TPO']
RegNetwork regulator_targets RegNetwork regulator RARA 候选基因交集：ESR1, NKX2-1, POU5F1, SFTPB, TG, TPO

Return ONLY JSON. No markdown. No extra text.
```


## Qwen Raw Response

```
{
  "global_gene_weights": [
    {"gene": "ESR1", "weight": 1.3, "reason": "Strong regulator in breast/ovarian clusters with multi-source support."},
    {"gene": "GATA3", "weight": 1.25, "reason": "Key breast lineage marker supported by MSigDB and Reactome."},
    {"gene": "CDX1", "weight": 1.2, "reason": "Intestinal lineage marker supported by ChEA and PanglaoDB."},
    {"gene": "CDX2", "weight": 1.2, "reason": "Intestinal lineage marker supported by ChEA and Reactome."},
    {"gene": "SOX10", "weight": 1.15, "reason": "Melanocytic lineage marker supported by cluster module 25."},
    {"gene": "LMX1B", "weight": 1.15, "reason": "Melanocytic lineage marker supported by cluster module 23."},
    {"gene": "PAX3", "weight": 1.15, "reason": "Melanocytic lineage marker supported by cluster modules 17 and 25."},
    {"gene": "COL5A1", "weight": 1.1, "reason": "High variance collagen gene supported by Reactome and ChEA."},
    {"gene": "KLK3", "weight": 1.1, "reason": "Prostate specific marker supported by cluster module 10."},
    {"gene": "SFTPB", "weight": 1.1, "reason": "Lung specific marker supported by RegNetwork and cluster 11."},
    {"gene": "MPO", "weight": 1.05, "reason": "Myeloid marker supported by cluster module 14."},
    {"gene": "GZMK", "weight": 1.05, "reason": "Cytotoxic marker supported by cluster module 4."}
  ],
  "suppress_genes": [],
  "modules": [
    {"name": "module_1", "genes": ["ESR1", "GATA3", "LMX1B", "SOX10", "PAX3"], "weight": 1.2, "reason": "Core epithelial and melanocytic lineage regulators."},
    {"name": "module_2", "genes": ["CDX1", "CDX2", "SFTPB", "KLK3", "MPO"], "weight": 1.15, "reason": "Intestinal, lung, prostate, and myeloid lineage markers."}
  ],
  "prototypes": [
    {
      "name": "prototype_1",
      "genes_up": ["ESR1", "GATA3", "SOX10", "CDX1", "SFTPB"],
      "genes_down": ["MPO", "KLK3"]
    }
  ],
  "key_gene_sets": ["Melanocytic_program", "Intestinal_program", "Lung_program", "Breast_program"],
  "key_regulators": ["ESR1", "GATA3", "SOX10", "CDX1", "CDX2"],
  "notes": ["Prioritize lineage-specific markers over housekeeping genes.", "Use multi-source evidence to validate high-variance genes like COL5A1."]
}
```


## Parsed Prior JSON

```json
{
  "global_gene_weights": [
    {
      "gene": "ESR1",
      "weight": 1.3,
      "reason": "Strong regulator in breast/ovarian clusters with multi-source support."
    },
    {
      "gene": "GATA3",
      "weight": 1.25,
      "reason": "Key breast lineage marker supported by MSigDB and Reactome."
    },
    {
      "gene": "CDX1",
      "weight": 1.2,
      "reason": "Intestinal lineage marker supported by ChEA and PanglaoDB."
    },
    {
      "gene": "CDX2",
      "weight": 1.2,
      "reason": "Intestinal lineage marker supported by ChEA and Reactome."
    },
    {
      "gene": "SOX10",
      "weight": 1.15,
      "reason": "Melanocytic lineage marker supported by cluster module 25."
    },
    {
      "gene": "LMX1B",
      "weight": 1.15,
      "reason": "Melanocytic lineage marker supported by cluster module 23."
    },
    {
      "gene": "PAX3",
      "weight": 1.15,
      "reason": "Melanocytic lineage marker supported by cluster modules 17 and 25."
    },
    {
      "gene": "COL5A1",
      "weight": 1.1,
      "reason": "High variance collagen gene supported by Reactome and ChEA."
    },
    {
      "gene": "KLK3",
      "weight": 1.1,
      "reason": "Prostate specific marker supported by cluster module 10."
    },
    {
      "gene": "SFTPB",
      "weight": 1.1,
      "reason": "Lung specific marker supported by RegNetwork and cluster 11."
    },
    {
      "gene": "MPO",
      "weight": 1.05,
      "reason": "Myeloid marker supported by cluster module 14."
    },
    {
      "gene": "GZMK",
      "weight": 1.05,
      "reason": "Cytotoxic marker supported by cluster module 4."
    }
  ],
  "suppress_genes": [],
  "modules": [
    {
      "name": "module_1",
      "genes": [
        "ESR1",
        "GATA3",
        "LMX1B",
        "SOX10",
        "PAX3"
      ],
      "weight": 1.2,
      "reason": "Core epithelial and melanocytic lineage regulators."
    },
    {
      "name": "module_2",
      "genes": [
        "CDX1",
        "CDX2",
        "SFTPB",
        "KLK3",
        "MPO"
      ],
      "weight": 1.15,
      "reason": "Intestinal, lung, prostate, and myeloid lineage markers."
    }
  ],
  "prototypes": [
    {
      "name": "prototype_1",
      "genes_up": [
        "ESR1",
        "GATA3",
        "SOX10",
        "CDX1",
        "SFTPB"
      ],
      "genes_down": [
        "MPO",
        "KLK3"
      ]
    }
  ],
  "key_gene_sets": [
    "Melanocytic_program",
    "Intestinal_program",
    "Lung_program",
    "Breast_program"
  ],
  "key_regulators": [
    "ESR1",
    "GATA3",
    "SOX10",
    "CDX1",
    "CDX2"
  ],
  "notes": [
    "Prioritize lineage-specific markers over housekeeping genes.",
    "Use multi-source evidence to validate high-variance genes like COL5A1."
  ]
}
```

