# Qwen Full Report

## 0. Dataset / Run Summary

- dataset_name: `BRCA mRNA top`
- raw_shape: `(671, 5000)`
- selected_sources: `{'ChEA': 2, 'MSigDB': 4, 'PanglaoDB': 1, 'Reactome': 6, 'RegNetwork': 8, 'STRING': 3}`
- llm_selected_sources: `{'ChEA': 2, 'MSigDB': 2, 'PanglaoDB': 1, 'Reactome': 3, 'RegNetwork': 3, 'STRING': 3}`
- qwen_model_name: `qwen3.5:9b`

## Cluster-wise Candidate Marker Genes

### cluster_module_0 | size=186
- ESR1
- GATA3
- NECAB3
- PARD6B
- MOAP1
- ABCA3
- LCMT2
- CPLX1
- TSPAN13
- COG7
- HEXIM2
- PLA2G12A
- AFF3
- COQ7
- GATAD1
- RAD17
- GAMT
- EXD2
- CCND1
- CACNA2D2
- PPIP5K1
- PEX12
- PNPLA4
- ZNF24
- LAMTOR3
- ACBD4
- OCIAD1
- AP1AR
- ZNF552
- MLPH
- CNNM3
- FKBP4

### cluster_module_1 | size=140
- ARSB
- GPNMB
- SULF1
- THY1
- CTHRC1
- MMP1
- COL11A1
- PLXNC1
- GPC6
- TGFBR1
- SERPINF1
- G6PD
- ACTR3
- FBN1
- CHRNA1
- CAP1
- LHFPL2
- DACT1
- CEMIP
- FCGR3A
- ABCA12
- HAVCR2
- RARRES2
- PRRX1
- MARCKS
- VAMP5
- LYZ
- MSC
- COL6A3
- MAFB
- PCDH7
- POSTN

### cluster_module_2 | size=72
- BLOC1S1
- EDF1
- ELOB
- GADD45GIP1
- ZNF593
- PET100
- COX4I1
- FAU
- RNF181
- SERF2
- MRPL55
- NAA10
- UBL5
- MRPL52
- DRAP1
- CNPY2
- PFDN5
- MSRB2
- TXNDC17
- SNRPF
- CHCHD10
- LSM7
- UXT
- HAUS7
- UQCC2
- SNRPD2
- SURF2
- ZNF787
- TMSB10
- RFXANK
- NDUFA12
- ARL2

### cluster_module_3 | size=177
- ABCA9
- PLSCR4
- ABCA8
- AASS
- STARD9
- ADAM33
- TGFBR2
- SH3D19
- TTC28
- ABCA10
- RUNX1T1
- DIXDC1
- SHE
- FREM1
- UTRN
- PCSK5
- TNXB
- ADGRA2
- C7
- PRDM2
- SNRK
- ZNF423
- RECK
- GLI2
- TEK
- GEM
- LRRC70
- CCDC80
- CD302
- AHNAK
- SEMA5A
- DDR2

### cluster_module_4 | size=96
- PSAT1
- FAM171A1
- CDC20
- TTK
- PPP1R14C
- CDCA8
- AURKB
- PIMREG
- ORC1
- SRPK1
- EN1
- NDC80
- AMD1
- MICALL1
- DEPDC1
- RRP1B
- E2F3
- LDHB
- MELK
- LBR
- HJURP
- CLCN4
- XPO5
- FOXM1
- ARL9
- STK38
- TICRR
- ANLN
- SERBP1
- TPX2
- COMMD2
- KCNQ4

## Candidate Genes

- ESR1
- GATA3
- NECAB3
- PARD6B
- MOAP1
- ABCA3
- LCMT2
- CPLX1
- TSPAN13
- COG7
- HEXIM2
- PLA2G12A
- AFF3
- COQ7
- GATAD1
- RAD17
- GAMT
- EXD2
- CCND1
- CACNA2D2
- PPIP5K1
- PEX12
- PNPLA4
- ZNF24
- LAMTOR3
- ACBD4
- OCIAD1
- AP1AR
- ZNF552
- MLPH
- CNNM3
- FKBP4
- ARSB
- GPNMB
- SULF1
- THY1
- CTHRC1
- MMP1
- COL11A1
- PLXNC1
- GPC6
- TGFBR1
- SERPINF1
- G6PD
- ACTR3
- FBN1
- CHRNA1
- CAP1
- LHFPL2
- DACT1
- CEMIP
- FCGR3A
- ABCA12
- HAVCR2
- RARRES2
- PRRX1
- MARCKS
- VAMP5
- LYZ
- MSC
- COL6A3
- MAFB
- PCDH7
- POSTN
- BLOC1S1
- EDF1
- ELOB
- GADD45GIP1
- ZNF593
- PET100
- COX4I1
- FAU
- RNF181
- SERF2
- MRPL55
- NAA10
- UBL5
- MRPL52
- DRAP1
- CNPY2
- PFDN5
- MSRB2
- TXNDC17
- SNRPF
- CHCHD10
- LSM7
- UXT
- HAUS7
- UQCC2
- SNRPD2
- SURF2
- ZNF787
- TMSB10
- RFXANK
- NDUFA12
- ARL2
- ABCA9
- PLSCR4
- ABCA8
- AASS
- STARD9
- ADAM33
- TGFBR2
- SH3D19
- TTC28
- ABCA10
- RUNX1T1
- DIXDC1
- SHE
- FREM1
- UTRN
- PCSK5
- TNXB
- ADGRA2
- C7
- PRDM2
- SNRK
- ZNF423
- RECK
- GLI2
- TEK
- GEM
- LRRC70
- CCDC80
- CD302
- AHNAK
- SEMA5A
- DDR2
- PSAT1
- FAM171A1
- CDC20
- TTK
- PPP1R14C
- CDCA8
- AURKB
- PIMREG
- ORC1
- SRPK1
- EN1
- NDC80
- AMD1
- MICALL1
- DEPDC1
- RRP1B
- E2F3
- LDHB
- MELK
- LBR
- HJURP
- CLCN4
- XPO5
- FOXM1
- ARL9
- STK38
- TICRR
- ANLN
- SERBP1
- TPX2
- COMMD2
- KCNQ4
- TMEM154
- SLC22A14
- CIB1
- FBXL8
- LRRC8E
- TMEM165
- IFFO2
- TSPAN2
- TMEM168
- LRRD1
- TMEM17
- TMEM170A
- PITPNC1
- SLC20A2
- RARB
- CHST6
- TMEM167B
- LRRC58
- FBXL18
- PKD1L1
- LRRC63
- CIR1
- IFI44
- TMEM144
- FBXL4
- FBXL2
- LRRC7
- PJA2
- CIDEC
- FBXL20
- FBXL3
- TMEM150C
- CINP
- CHRNA3
- FBXO31
- PIP4K2C
- CHRM5
- CHRM4
- CHRM3
- RARG
- CHRM1
- CHRFAM7A
- IDS
- CHRDL1
- FBXO34
- CHRAC1
- LSG1
- LSM14A
- FBXO32
- CHST4
- CHST3
- CHST2
- CHST15
- LRRIQ4
- TMEM176B
- TMEM178A
- FBXO30
- LRRN2
- PIPOX
- FBXO28
- CHRNB2
- TMEM184A
- LRRTM2
- TMEM184C
- CHRNA5
- PIR
- PLA2G2D
- PLA2G2C
- FAXC
- RANGAP1
- LRRC27
- RANGRF
- LRRC29
- CISD3
- TMED9
- TMEM100
- TMEM101
- TMEM102
- CLDN18
- TMEM104
- LRRC31
- TMED8
- CLEC4A
- SLC25A15
- RANBP10
- PLA2R1
- SLC25A12
- CLEC1A
- SLC24A4
- FAT3
- CLEC16A
- PLA2G3
- FATE1
- CLEC12A
- LRRC19
- LRRC2
- CLDND2
- CLDND1
- CLEC18A
- SLC22A4
- TMEM126B
- SLC22A31
- CKS1B
- CKMT2
- CKMT1B
- CKMT1A
- FBL
- LRRC46
- FBRSL1
- PKIA
- FBXL13
- CKAP2
- RAPGEF1
- PKDCC
- PKD2
- RAP2B
- FBLIM1
- CLDN12
- RAP1GAP
- TMEM109
- TMEM11
- PKP2
- LRRC37A3
- CLCN6
- LRRC41
- PKP1
- CLCF1
- CLCC1
- IFITM1
- CLCA2
- IFIT5
- TMEM116
- CFAP77
- TMEM37
- LYL1
- TMEM38B
- LYN
- LYPD1
- CFAP58
- RASA4
- CFAP54
- PIGB
- CFAP52
- LYPD3
- CFAP46
- SLC15A4
- PIFO
- LYPD6
- CFAP57
- SLC16A14
- PIGO
- RASGRP1
- TMEM266
- SLC44A4
- SCNN1A
- SLC7A8
- ALKBH3
- C9ORF152
- SMIM14
- PLEKHA6
- RB1
- VAV3
- DSP
- SEC24C
- CSTF2T
- TEAD2
- MGST1
- BOK
- MYOF
- TSPAN15
- DAZAP2
- TOX4
- CDH1
- PHF2
- SEZ6L2
- NPDC1
- STAT6
- NEO1
- FAM174B
- REEP6
- TES
- ZFYVE9
- SH3BP4
- KRT19
- GPD1L
- ERBIN
- SIDT1
- MAGEH1
- GLT8D1
- PDCD6IP
- SPG11
- SNAP23
- ZNF175
- SMIM22
- DHCR24
- HSPG2
- USP4
- FUBP3
- RECQL
- IGF1R
- GABARAPL1
- APPL1
- EFS
- BCOR
- SEMA3C
- RIPK1
- ZNF467
- SP1
- GTF2F1
- ERCC5
- ISG20
- DAB2
- SULT1A3
- PANO1
- ZNF513
- RASAL2
- SORL1
- FAM209B
- KIF20B
- AGO1
- MAX
- HMG20A
- GZMM
- CDK10
- METTL17
- BTBD8
- NFKB2
- BNC2
- TRAM2
- MXD3
- PSMB6
- GGA1
- PPP1R7
- SSBP1
- ACER2
- NT5C
- TMTC3
- PCNX1
- KDELR1
- MDH1


## Retrieved Knowledge Chunks

### Chunk 1
- source: ChEA
- type: tf_target_set
- title: ChEA term HNF4A 19822575 ChIP-Seq HepG2 Human
- genes: AASS, ABCA8, ABCA9, ACTR3, AFF3, AHNAK, ARSB, AURKB, BCOR, BNC2, BOK, CAP1, CCND1, CD302, CDH1, CDK10, CHRAC1, CHST3, CLCN6, CLDN12, CLEC16A, CNNM3, COG7, COMMD2, COQ7, CPLX1, DAB2, DDR2, DHCR24, DIXDC1, DSP, E2F3, ERCC5, ESR1, FAM171A1, FAM174B, FAT3, FBLIM1, FBXL13, FBXL4

#### text

```
ChEA tf_target_set ChEA term HNF4A 19822575 ChIP-Seq HepG2 Human 候选基因交集：AASS, ABCA8, ABCA9, ACTR3, AFF3, AHNAK, ARSB, AURKB, BCOR, BNC2, BOK, CAP1, CCND1, CD302, CDH1, CDK10, CHRAC
```


### Chunk 2
- source: ChEA
- type: tf_target_set
- title: ChEA term FLI1 21571218 ChIP-Seq MEGAKARYOCYTES Human
- genes: ABCA3, ACTR3, AHNAK, AMD1, AURKB, BCOR, BLOC1S1, CAP1, CHRAC1, CHRM3, CHST15, CHST6, CINP, CIR1, CLCN6, CLDND2, CLEC1A, COG7, COL6A3, COMMD2, COX4I1, CSTF2T, DAZAP2, E2F3, EN1, ERCC5, EXD2, FAU, FBL, FBRSL1, FBXO28, FBXO31, FBXO32, FKBP4, FUBP3, G6PD, GATAD1, GGA1, GLT8D1, GTF2F1

#### text

```
ChEA tf_target_set ChEA term FLI1 21571218 ChIP-Seq MEGAKARYOCYTES Human 候选基因交集：ABCA3, ACTR3, AHNAK, AMD1, AURKB, BCOR, BLOC1S1, CAP1, CHRAC1, CHRM3, CHST15, CHST6, CINP, CIR1, CLC
```


### Chunk 3
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_CELL_CYCLE
- genes: ACTR3, ANLN, APPL1, ARL2, AURKB, CCND1, CDC20, CDCA8, CDK10, CIB1, CKAP2, CKS1B, DACT1, DDR2, E2F3, FBXL13, FBXO30, FBXO31, FOXM1, GATA3, GEM, GPNMB, HAUS7, HEXIM2, HJURP, KIF20B, LSM14A, LYN, MELK, NAA10, NDC80, ORC1, PARD6B, PDCD6IP, PKD2, PKIA, PLA2R1, PPP1R7, PSMB6, RAD17

#### text

```
MSigDB gene_set MSigDB gene set GOBP_CELL_CYCLE 候选基因交集：ACTR3, ANLN, APPL1, ARL2, AURKB, CCND1, CDC20, CDCA8, CDK10, CIB1, CKAP2, CKS1B, DACT1, DDR2, E2F3, FBXL13, FBXO30, FBXO31, F
```


### Chunk 4
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_CELL_CYCLE_PROCESS
- genes: ACTR3, ANLN, APPL1, ARL2, AURKB, CCND1, CDC20, CDCA8, CDK10, CKAP2, DACT1, DDR2, E2F3, FBXL13, FBXO30, FBXO31, FOXM1, GEM, GPNMB, HAUS7, HEXIM2, HJURP, KIF20B, LSM14A, LYN, MELK, NAA10, NDC80, ORC1, PARD6B, PDCD6IP, PKD2, PKIA, PLA2R1, PPP1R7, PSMB6, RAD17, RANGRF, RB1, SRPK1

#### text

```
MSigDB gene_set MSigDB gene set GOBP_CELL_CYCLE_PROCESS 候选基因交集：ACTR3, ANLN, APPL1, ARL2, AURKB, CCND1, CDC20, CDCA8, CDK10, CKAP2, DACT1, DDR2, E2F3, FBXL13, FBXO30, FBXO31, FOXM1,
```


### Chunk 5
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_CYTOSKELETON_ORGANIZATION
- genes: ACTR3, ANLN, AP1AR, ARL2, AURKB, CAP1, CDC20, CDCA8, CDK10, CFAP46, CFAP57, CFAP58, CIB1, CKAP2, DIXDC1, DSP, ERBIN, FAM171A1, FBXL13, FKBP4, HAUS7, KRT19, LRRC46, LSM14A, MARCKS, MICALL1, MSRB2, NDC80, PARD6B, PDCD6IP, PKD2, PKP1, PKP2, PLA2G3, RANBP10, RANGRF, SEMA5A, SH3BP4, SH3D19, SMIM22

#### text

```
MSigDB gene_set MSigDB gene set GOBP_CYTOSKELETON_ORGANIZATION 候选基因交集：ACTR3, ANLN, AP1AR, ARL2, AURKB, CAP1, CDC20, CDCA8, CDK10, CFAP46, CFAP57, CFAP58, CIB1, CKAP2, DIXDC1, DSP, ERBIN, FAM171A1, FBXL13, FKBP4, HAUS7, KRT19, LRRC46, LSM14A, MARCKS, MICALL1, MSRB2, NDC80, PARD6B, PDCD6IP, PKD2, PKP1, PKP2, PLA2G3, RANBP10, RANGRF, SEMA5A, SH3BP4, SH3D19, SMIM22
```


### Chunk 6
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_PROTEIN_CONTAINING_COMPLEX_ORGANIZATION
- genes: ABCA3, AGO1, ANLN, ARL2, AURKB, BOK, CFAP57, CHRAC1, CIB1, CKAP2, CLEC16A, DAB2, DACT1, DRAP1, ELOB, ESR1, FAU, FBLIM1, FBXL2, FKBP4, GABARAPL1, HAUS7, HJURP, IGF1R, LSM7, METTL17, MMP1, MSRB2, PARD6B, PCSK5, PDCD6IP, PET100, PEX12, PFDN5, PKD2, PLA2G3, RIPK1, SEMA5A, SNAP23, SNRPD2

#### text

```
MSigDB gene_set MSigDB gene set GOBP_PROTEIN_CONTAINING_COMPLEX_ORGANIZATION 候选基因交集：ABCA3, AGO1, ANLN, ARL2, AURKB, BOK, CFAP57, CHRAC1, CIB1, CKAP2, CLEC16A, DAB2, DACT1, DRAP1, ELOB, ESR1, FAU, FBLIM1, FBXL2, FKBP4, GABARAPL1, HAUS7, HJURP, IGF1R, LSM7, METTL17, MMP1, MSRB2, PARD6B, PCSK5, PDCD6IP, PET100, PEX12, PFDN5, PKD2, PLA2G3, RIPK1, SEMA5A, SNAP23, SNRPD2
```


### Chunk 7
- source: PanglaoDB
- type: cell_type_marker
- title: PanglaoDB markers for Fibroblasts
- genes: ADAM33, COL6A3, CTHRC1, FBN1, PKD2, POSTN, PRRX1, RARRES2, TNXB

#### text

```
PanglaoDB cell_type_marker PanglaoDB markers for Fibroblasts 候选基因交集：ADAM33, COL6A3, CTHRC1, FBN1, PKD2, POSTN, PRRX1, RARRES2, TNXB
```


### Chunk 8
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Signal Transduction
- genes: ACTR3, AGO1, ANLN, ARL2, AURKB, CCND1, CDC20, CDCA8, CDH1, CHRDL1, CHRM1, CHRM3, CHRM4, CHRM5, COL11A1, COL6A3, DACT1, DRAP1, DSP, E2F3, ERBIN, ESR1, FBN1, FKBP4, GATA3, GLI2, GPNMB, GTF2F1, IGF1R, LAMTOR3, LBR, LRRC41, LRRC7, LYL1, LYN, NDC80, PARD6B, PCDH7, PCSK5, PIP4K2C

#### text

```
Reactome pathway_gene_set Reactome pathway Signal Transduction 候选基因交集：ACTR3, AGO1, ANLN, ARL2, AURKB, CCND1, CDC20, CDCA8, CDH1, CHRDL1, CHRM1, CHRM3, CHRM4, CHRM5, COL11A1, COL6A3
```


### Chunk 9
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Disease
- genes: ABCA12, ABCA3, ACTR3, AGO1, ARSB, CCND1, CDH1, CHST3, CHST6, CLCN6, CSTF2T, E2F3, ELOB, ERBIN, ESR1, FAU, FCGR3A, FKBP4, FOXM1, GPC6, GTF2F1, HSPG2, IDS, IGF1R, KDELR1, LYN, NFKB2, PDCD6IP, PSMB6, RAD17, RANGAP1, RB1, RIPK1, SEC24C, SEMA5A, SLC20A2, SLC24A4, SLC25A15, SNRPD2, SNRPF

#### text

```
Reactome pathway_gene_set Reactome pathway Disease 候选基因交集：ABCA12, ABCA3, ACTR3, AGO1, ARSB, CCND1, CDH1, CHST3, CHST6, CLCN6, CSTF2T, E2F3, ELOB, ERBIN, ESR1, FAU, FCGR3A, FKBP4, F
```


### Chunk 10
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Gene expression (Transcription)
- genes: AGO1, AURKB, CCND1, CIDEC, COX4I1, CSTF2T, ELOB, ESR1, FBXO32, G6PD, GAMT, GATA3, GEM, GLI2, GTF2F1, LAMTOR3, LBR, MAX, PIP4K2C, PSMB6, RAD17, RARB, RARG, RB1, SNRPF, SP1, TEAD2, TPX2, UXT, XPO5, ZNF175, ZNF552

#### text

```
Reactome pathway_gene_set Reactome pathway Gene expression (Transcription) 候选基因交集：AGO1, AURKB, CCND1, CIDEC, COX4I1, CSTF2T, ELOB, ESR1, FBXO32, G6PD, GAMT, GATA3, GEM, GLI2, GTF2F
```


### Chunk 11
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway RNA Polymerase II Transcription
- genes: AGO1, AURKB, CCND1, COX4I1, CSTF2T, ELOB, ESR1, FBXO32, G6PD, GAMT, GATA3, GEM, GLI2, GTF2F1, LAMTOR3, LBR, MAX, PIP4K2C, PSMB6, RAD17, RARB, RARG, RB1, SNRPF, SP1, TEAD2, TPX2, UXT, ZNF175, ZNF552

#### text

```
Reactome pathway_gene_set Reactome pathway RNA Polymerase II Transcription 候选基因交集：AGO1, AURKB, CCND1, COX4I1, CSTF2T, ELOB, ESR1, FBXO32, G6PD, GAMT, GATA3, GEM, GLI2, GTF2F1, LAMTOR3, LBR, MAX, PIP4K2C, PSMB6, RAD17, RARB, RARG, RB1, SNRPF, SP1, TEAD2, TPX2, UXT, ZNF175, ZNF552
```


### Chunk 12
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Post-translational protein modification
- genes: ARSB, AURKB, CDC20, CDCA8, CHRDL1, CHST4, COG7, COMMD2, ELOB, ESR1, FBN1, FBXL13, FBXL18, FBXL20, FBXL3, FBXL4, FBXL8, FBXO30, FBXO31, FBXO32, GATA3, KDELR1, LRRC41, LYPD1, LYPD3, NFKB2, PEX12, PIGB, PIGO, PSMB6, RANGAP1, RECK, RIPK1, RNF181, SEC24C, SEMA5A, TGFBR1, TGFBR2, THY1, TMED9

#### text

```
Reactome pathway_gene_set Reactome pathway Post-translational protein modification 候选基因交集：ARSB, AURKB, CDC20, CDCA8, CHRDL1, CHST4, COG7, COMMD2, ELOB, ESR1, FBN1, FBXL13, FBXL18, FBXL20, FBXL3, FBXL4, FBXL8, FBXO30, FBXO31, FBXO32, GATA3, KDELR1, LRRC41, LYPD1, LYPD3, NFKB2, PEX12, PIGB, PIGO, PSMB6, RANGAP1, RECK, RIPK1, RNF181, SEC24C, SEMA5A, TGFBR1, TGFBR2, THY1, TMED9
```


### Chunk 13
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Immune System
- genes: ACTR3, AGO1, ARSB, C7, CAP1, CCND1, CDC20, CDH1, CLCF1, CLEC12A, CLEC4A, DSP, ELOB, FBXL13, FBXL18, FBXL20, FBXL3, FBXL4, FBXL8, FBXO30, FBXO31, FBXO32, FCGR3A, GATA3, GZMM, HAVCR2, IFI44, IFIT5, IFITM1, ISG20, LAMTOR3, LRRC41, LRRC7, LYN, LYZ, MGST1, MMP1, NFKB2, NPDC1, PJA2

#### text

```
Reactome pathway_gene_set Reactome pathway Immune System 候选基因交集：ACTR3, AGO1, ARSB, C7, CAP1, CCND1, CDC20, CDH1, CLCF1, CLEC12A, CLEC4A, DSP, ELOB, FBXL13, FBXL18, FBXL20, FBXL3, FBXL4, FBXL8, FBXO30, FBXO31, FBXO32, FCGR3A, GATA3, GZMM, HAVCR2, IFI44, IFIT5, IFITM1, ISG20, LAMTOR3, LRRC41, LRRC7, LYN, LYZ, MGST1, MMP1, NFKB2, NPDC1, PJA2
```


### Chunk 14
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator HSA-MIR-503
- genes: ANLN, ARL2, BNC2, CCND1, DIXDC1, E2F3

#### text

```
RegNetwork regulator_targets RegNetwork regulator HSA-MIR-503 候选基因交集：ANLN, ARL2, BNC2, CCND1, DIXDC1, E2F3
```


### Chunk 15
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator ALX1
- genes: PCDH7, PCSK5, RUNX1T1, SH3D19, TEK

#### text

```
RegNetwork regulator_targets RegNetwork regulator ALX1 候选基因交集：PCDH7, PCSK5, RUNX1T1, SH3D19, TEK
```


### Chunk 16
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator HSA-MIR-429
- genes: AFF3, AHNAK, ANLN, AP1AR, APPL1, BNC2

#### text

```
RegNetwork regulator_targets RegNetwork regulator HSA-MIR-429 候选基因交集：AFF3, AHNAK, ANLN, AP1AR, APPL1, BNC2
```


### Chunk 17
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator ETS2
- genes: CCND1, CDK10, GATA3, SURF2, TGFBR2, ZFYVE9

#### text

```
RegNetwork regulator_targets RegNetwork regulator ETS2 候选基因交集：CCND1, CDK10, GATA3, SURF2, TGFBR2, ZFYVE9
```


### Chunk 18
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator HSA-MIR-448
- genes: ANLN, BCOR, BNC2, CAP1, CLCN4, DACT1

#### text

```
RegNetwork regulator_targets RegNetwork regulator HSA-MIR-448 候选基因交集：ANLN, BCOR, BNC2, CAP1, CLCN4, DACT1
```


### Chunk 19
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator HSA-MIR-518D-5P
- genes: ACTR3, CAP1, COL6A3, DIXDC1, FBXO32, IDS

#### text

```
RegNetwork regulator_targets RegNetwork regulator HSA-MIR-518D-5P 候选基因交集：ACTR3, CAP1, COL6A3, DIXDC1, FBXO32, IDS
```


### Chunk 20
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator RB1
- genes: BNC2, CCND1, E2F3, NDC80, PRDM2, RB1

#### text

```
RegNetwork regulator_targets RegNetwork regulator RB1 候选基因交集：BNC2, CCND1, E2F3, NDC80, PRDM2, RB1
```


### Chunk 21
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator SP3
- genes: CCND1, ESR1, RB1, SP1, TGFBR2, UTRN

#### text

```
RegNetwork regulator_targets RegNetwork regulator SP3 候选基因交集：CCND1, ESR1, RB1, SP1, TGFBR2, UTRN
```


### Chunk 22
- source: STRING
- type: ppi_neighbors
- title: STRING neighbors of HAVCR2
- genes: HAVCR2

#### text

```
STRING ppi_neighbors STRING neighbors of HAVCR2 候选基因交集：HAVCR2
```


### Chunk 23
- source: STRING
- type: ppi_neighbors
- title: STRING neighbors of FCGR3A
- genes: FCGR3A

#### text

```
STRING ppi_neighbors STRING neighbors of FCGR3A 候选基因交集：FCGR3A
```


### Chunk 24
- source: STRING
- type: ppi_neighbors
- title: STRING neighbors of FBN1
- genes: FBN1

#### text

```
STRING ppi_neighbors STRING neighbors of FBN1 候选基因交集：FBN1
```


## LLM Selected Chunks

### LLM Chunk 1
- source: ChEA
- type: tf_target_set
- title: ChEA term HNF4A 19822575 ChIP-Seq HepG2 Human
- genes: AASS, ABCA8, ABCA9, ACTR3, AFF3, AHNAK, ARSB, AURKB, BCOR, BNC2, BOK, CAP1, CCND1, CD302, CDH1, CDK10, CHRAC1, CHST3, CLCN6, CLDN12, CLEC16A, CNNM3, COG7, COMMD2, COQ7, CPLX1, DAB2, DDR2, DHCR24, DIXDC1, DSP, E2F3, ERCC5, ESR1, FAM171A1, FAM174B, FAT3, FBLIM1, FBXL13, FBXL4

#### text

```
ChEA tf_target_set ChEA term HNF4A 19822575 ChIP-Seq HepG2 Human 候选基因交集：AASS, ABCA8, ABCA9, ACTR3, AFF3, AHNAK, ARSB, AURKB, BCOR, BNC2, BOK, CAP1, CCND1, CD302, CDH1, CDK10, CHRAC
```


### LLM Chunk 2
- source: ChEA
- type: tf_target_set
- title: ChEA term FLI1 21571218 ChIP-Seq MEGAKARYOCYTES Human
- genes: ABCA3, ACTR3, AHNAK, AMD1, AURKB, BCOR, BLOC1S1, CAP1, CHRAC1, CHRM3, CHST15, CHST6, CINP, CIR1, CLCN6, CLDND2, CLEC1A, COG7, COL6A3, COMMD2, COX4I1, CSTF2T, DAZAP2, E2F3, EN1, ERCC5, EXD2, FAU, FBL, FBRSL1, FBXO28, FBXO31, FBXO32, FKBP4, FUBP3, G6PD, GATAD1, GGA1, GLT8D1, GTF2F1

#### text

```
ChEA tf_target_set ChEA term FLI1 21571218 ChIP-Seq MEGAKARYOCYTES Human 候选基因交集：ABCA3, ACTR3, AHNAK, AMD1, AURKB, BCOR, BLOC1S1, CAP1, CHRAC1, CHRM3, CHST15, CHST6, CINP, CIR1, CLC
```


### LLM Chunk 3
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_CELL_CYCLE
- genes: ACTR3, ANLN, APPL1, ARL2, AURKB, CCND1, CDC20, CDCA8, CDK10, CIB1, CKAP2, CKS1B, DACT1, DDR2, E2F3, FBXL13, FBXO30, FBXO31, FOXM1, GATA3, GEM, GPNMB, HAUS7, HEXIM2, HJURP, KIF20B, LSM14A, LYN, MELK, NAA10, NDC80, ORC1, PARD6B, PDCD6IP, PKD2, PKIA, PLA2R1, PPP1R7, PSMB6, RAD17

#### text

```
MSigDB gene_set MSigDB gene set GOBP_CELL_CYCLE 候选基因交集：ACTR3, ANLN, APPL1, ARL2, AURKB, CCND1, CDC20, CDCA8, CDK10, CIB1, CKAP2, CKS1B, DACT1, DDR2, E2F3, FBXL13, FBXO30, FBXO31, F
```


### LLM Chunk 4
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_CELL_CYCLE_PROCESS
- genes: ACTR3, ANLN, APPL1, ARL2, AURKB, CCND1, CDC20, CDCA8, CDK10, CKAP2, DACT1, DDR2, E2F3, FBXL13, FBXO30, FBXO31, FOXM1, GEM, GPNMB, HAUS7, HEXIM2, HJURP, KIF20B, LSM14A, LYN, MELK, NAA10, NDC80, ORC1, PARD6B, PDCD6IP, PKD2, PKIA, PLA2R1, PPP1R7, PSMB6, RAD17, RANGRF, RB1, SRPK1

#### text

```
MSigDB gene_set MSigDB gene set GOBP_CELL_CYCLE_PROCESS 候选基因交集：ACTR3, ANLN, APPL1, ARL2, AURKB, CCND1, CDC20, CDCA8, CDK10, CKAP2, DACT1, DDR2, E2F3, FBXL13, FBXO30, FBXO31, FOXM1,
```


### LLM Chunk 5
- source: PanglaoDB
- type: cell_type_marker
- title: PanglaoDB markers for Fibroblasts
- genes: ADAM33, COL6A3, CTHRC1, FBN1, PKD2, POSTN, PRRX1, RARRES2, TNXB

#### text

```
PanglaoDB cell_type_marker PanglaoDB markers for Fibroblasts 候选基因交集：ADAM33, COL6A3, CTHRC1, FBN1, PKD2, POSTN, PRRX1, RARRES2, TNXB
```


### LLM Chunk 6
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Signal Transduction
- genes: ACTR3, AGO1, ANLN, ARL2, AURKB, CCND1, CDC20, CDCA8, CDH1, CHRDL1, CHRM1, CHRM3, CHRM4, CHRM5, COL11A1, COL6A3, DACT1, DRAP1, DSP, E2F3, ERBIN, ESR1, FBN1, FKBP4, GATA3, GLI2, GPNMB, GTF2F1, IGF1R, LAMTOR3, LBR, LRRC41, LRRC7, LYL1, LYN, NDC80, PARD6B, PCDH7, PCSK5, PIP4K2C

#### text

```
Reactome pathway_gene_set Reactome pathway Signal Transduction 候选基因交集：ACTR3, AGO1, ANLN, ARL2, AURKB, CCND1, CDC20, CDCA8, CDH1, CHRDL1, CHRM1, CHRM3, CHRM4, CHRM5, COL11A1, COL6A3
```


### LLM Chunk 7
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Disease
- genes: ABCA12, ABCA3, ACTR3, AGO1, ARSB, CCND1, CDH1, CHST3, CHST6, CLCN6, CSTF2T, E2F3, ELOB, ERBIN, ESR1, FAU, FCGR3A, FKBP4, FOXM1, GPC6, GTF2F1, HSPG2, IDS, IGF1R, KDELR1, LYN, NFKB2, PDCD6IP, PSMB6, RAD17, RANGAP1, RB1, RIPK1, SEC24C, SEMA5A, SLC20A2, SLC24A4, SLC25A15, SNRPD2, SNRPF

#### text

```
Reactome pathway_gene_set Reactome pathway Disease 候选基因交集：ABCA12, ABCA3, ACTR3, AGO1, ARSB, CCND1, CDH1, CHST3, CHST6, CLCN6, CSTF2T, E2F3, ELOB, ERBIN, ESR1, FAU, FCGR3A, FKBP4, F
```


### LLM Chunk 8
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Gene expression (Transcription)
- genes: AGO1, AURKB, CCND1, CIDEC, COX4I1, CSTF2T, ELOB, ESR1, FBXO32, G6PD, GAMT, GATA3, GEM, GLI2, GTF2F1, LAMTOR3, LBR, MAX, PIP4K2C, PSMB6, RAD17, RARB, RARG, RB1, SNRPF, SP1, TEAD2, TPX2, UXT, XPO5, ZNF175, ZNF552

#### text

```
Reactome pathway_gene_set Reactome pathway Gene expression (Transcription) 候选基因交集：AGO1, AURKB, CCND1, CIDEC, COX4I1, CSTF2T, ELOB, ESR1, FBXO32, G6PD, GAMT, GATA3, GEM, GLI2, GTF2F
```


### LLM Chunk 9
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator HSA-MIR-503
- genes: ANLN, ARL2, BNC2, CCND1, DIXDC1, E2F3

#### text

```
RegNetwork regulator_targets RegNetwork regulator HSA-MIR-503 候选基因交集：ANLN, ARL2, BNC2, CCND1, DIXDC1, E2F3
```


### LLM Chunk 10
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator ALX1
- genes: PCDH7, PCSK5, RUNX1T1, SH3D19, TEK

#### text

```
RegNetwork regulator_targets RegNetwork regulator ALX1 候选基因交集：PCDH7, PCSK5, RUNX1T1, SH3D19, TEK
```


### LLM Chunk 11
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator HSA-MIR-429
- genes: AFF3, AHNAK, ANLN, AP1AR, APPL1, BNC2

#### text

```
RegNetwork regulator_targets RegNetwork regulator HSA-MIR-429 候选基因交集：AFF3, AHNAK, ANLN, AP1AR, APPL1, BNC2
```


### LLM Chunk 12
- source: STRING
- type: ppi_neighbors
- title: STRING neighbors of HAVCR2
- genes: HAVCR2

#### text

```
STRING ppi_neighbors STRING neighbors of HAVCR2 候选基因交集：HAVCR2
```


### LLM Chunk 13
- source: STRING
- type: ppi_neighbors
- title: STRING neighbors of FCGR3A
- genes: FCGR3A

#### text

```
STRING ppi_neighbors STRING neighbors of FCGR3A 候选基因交集：FCGR3A
```


### LLM Chunk 14
- source: STRING
- type: ppi_neighbors
- title: STRING neighbors of FBN1
- genes: FBN1

#### text

```
STRING ppi_neighbors STRING neighbors of FBN1 候选基因交集：FBN1
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
- Prioritize genes that are BOTH in cluster_marker_genes and top_var_genes when possible.
- Penalize genes that are only generic cancer/stromal/immune markers without strong current-dataset discriminative evidence.
- Prioritize genes with high GENE_DISCRIMINATIVE_STATS score.
- A gene with weak current-dataset discriminative score should not be selected only because it is a famous marker.
- For any dataset, generic composition markers are allowed only if their GENE_DISCRIMINATIVE_STATS score is high.
- Prefer genes that distinguish current unsupervised cluster blocks.
- Do not create a module only because it is biologically recognizable.
- Do not select a module only because it is biologically recognizable; it must help separate current unsupervised clusters.
- Prefer genes that explain differences between current cluster blocks, not genes that are uniformly high or broadly cancer-associated.
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
- disease_context=breast cancer molecular subtype ER PR HER2 luminal basal proliferation cell cycle EMT immune microenvironment heterogeneity cluster separability
- n_samples=671
- n_genes=19264
- cluster_count=5
- candidate_gene_count=400
- high variance genes=['TMEM154', 'SLC22A14', 'CIB1', 'FBXL8', 'LRRC8E', 'TMEM165', 'IFFO2', 'TSPAN2', 'TMEM168', 'LRRD1', 'TMEM17', 'TMEM170A', 'PITPNC1', 'SLC20A2', 'RARB', 'CHST6', 'TMEM167B', 'LRRC58', 'FBXL18', 'PKD1L1']

CLUSTER_MARKER_BLOCKS:
- cluster_module_0 | size=186: ['ESR1', 'GATA3', 'NECAB3', 'PARD6B', 'MOAP1', 'ABCA3', 'LCMT2', 'CPLX1', 'TSPAN13', 'COG7', 'HEXIM2', 'PLA2G12A', 'AFF3', 'COQ7', 'GATAD1', 'RAD17', 'GAMT', 'EXD2', 'CCND1', 'CACNA2D2', 'PPIP5K1', 'PEX12', 'PNPLA4', 'ZNF24', 'LAMTOR3', 'ACBD4', 'OCIAD1', 'AP1AR', 'ZNF552', 'MLPH', 'CNNM3', 'FKBP4']
- cluster_module_1 | size=140: ['ARSB', 'GPNMB', 'SULF1', 'THY1', 'CTHRC1', 'MMP1', 'COL11A1', 'PLXNC1', 'GPC6', 'TGFBR1', 'SERPINF1', 'G6PD', 'ACTR3', 'FBN1', 'CHRNA1', 'CAP1', 'LHFPL2', 'DACT1', 'CEMIP', 'FCGR3A', 'ABCA12', 'HAVCR2', 'RARRES2', 'PRRX1', 'MARCKS', 'VAMP5', 'LYZ', 'MSC', 'COL6A3', 'MAFB', 'PCDH7', 'POSTN']
- cluster_module_2 | size=72: ['BLOC1S1', 'EDF1', 'ELOB', 'GADD45GIP1', 'ZNF593', 'PET100', 'COX4I1', 'FAU', 'RNF181', 'SERF2', 'MRPL55', 'NAA10', 'UBL5', 'MRPL52', 'DRAP1', 'CNPY2', 'PFDN5', 'MSRB2', 'TXNDC17', 'SNRPF', 'CHCHD10', 'LSM7', 'UXT', 'HAUS7', 'UQCC2', 'SNRPD2', 'SURF2', 'ZNF787', 'TMSB10', 'RFXANK', 'NDUFA12', 'ARL2']
- cluster_module_3 | size=177: ['ABCA9', 'PLSCR4', 'ABCA8', 'AASS', 'STARD9', 'ADAM33', 'TGFBR2', 'SH3D19', 'TTC28', 'ABCA10', 'RUNX1T1', 'DIXDC1', 'SHE', 'FREM1', 'UTRN', 'PCSK5', 'TNXB', 'ADGRA2', 'C7', 'PRDM2', 'SNRK', 'ZNF423', 'RECK', 'GLI2', 'TEK', 'GEM', 'LRRC70', 'CCDC80', 'CD302', 'AHNAK', 'SEMA5A', 'DDR2']
- cluster_module_4 | size=96: ['PSAT1', 'FAM171A1', 'CDC20', 'TTK', 'PPP1R14C', 'CDCA8', 'AURKB', 'PIMREG', 'ORC1', 'SRPK1', 'EN1', 'NDC80', 'AMD1', 'MICALL1', 'DEPDC1', 'RRP1B', 'E2F3', 'LDHB', 'MELK', 'LBR', 'HJURP', 'CLCN4', 'XPO5', 'FOXM1', 'ARL9', 'STK38', 'TICRR', 'ANLN', 'SERBP1', 'TPX2', 'COMMD2', 'KCNQ4']

GENE_DISCRIMINATIVE_STATS:
- ESR1: score=1.5502, cluster=0, cluster_size=186, z_effect=1.5502, presence_gain=0.0000
- GATA3: score=1.3529, cluster=0, cluster_size=186, z_effect=1.3529, presence_gain=0.0000
- NECAB3: score=1.3142, cluster=0, cluster_size=186, z_effect=1.3142, presence_gain=0.0000
- PARD6B: score=1.2486, cluster=0, cluster_size=186, z_effect=1.2486, presence_gain=0.0000
- MOAP1: score=1.2447, cluster=0, cluster_size=186, z_effect=1.2447, presence_gain=0.0000
- ABCA3: score=1.2442, cluster=0, cluster_size=186, z_effect=1.2442, presence_gain=0.0000
- LCMT2: score=1.2385, cluster=0, cluster_size=186, z_effect=1.2385, presence_gain=0.0000
- CPLX1: score=1.2078, cluster=0, cluster_size=186, z_effect=1.2078, presence_gain=0.0000
- TSPAN13: score=1.2024, cluster=0, cluster_size=186, z_effect=1.2024, presence_gain=0.0000
- COG7: score=1.1979, cluster=0, cluster_size=186, z_effect=1.1979, presence_gain=0.0000
- HEXIM2: score=1.1966, cluster=0, cluster_size=186, z_effect=1.1966, presence_gain=0.0000
- PLA2G12A: score=1.1807, cluster=0, cluster_size=186, z_effect=1.1807, presence_gain=0.0000
- AFF3: score=1.1793, cluster=0, cluster_size=186, z_effect=1.1793, presence_gain=0.0000
- COQ7: score=1.1730, cluster=0, cluster_size=186, z_effect=1.1730, presence_gain=0.0000
- GATAD1: score=1.1694, cluster=0, cluster_size=186, z_effect=1.1694, presence_gain=0.0000
- RAD17: score=1.1676, cluster=0, cluster_size=186, z_effect=1.1676, presence_gain=0.0000
- GAMT: score=1.1580, cluster=0, cluster_size=186, z_effect=1.1580, presence_gain=0.0000
- EXD2: score=1.1556, cluster=0, cluster_size=186, z_effect=1.1556, presence_gain=0.0000
- CCND1: score=1.1496, cluster=0, cluster_size=186, z_effect=1.1496, presence_gain=0.0000
- CACNA2D2: score=1.1312, cluster=0, cluster_size=186, z_effect=1.1312, presence_gain=0.0000
- PPIP5K1: score=1.1208, cluster=0, cluster_size=186, z_effect=1.1208, presence_gain=0.0000
- PEX12: score=1.1132, cluster=0, cluster_size=186, z_effect=1.1132, presence_gain=0.0000
- PNPLA4: score=1.1127, cluster=0, cluster_size=186, z_effect=1.1127, presence_gain=0.0000
- ZNF24: score=1.1023, cluster=0, cluster_size=186, z_effect=1.1023, presence_gain=0.0000
- LAMTOR3: score=1.1008, cluster=0, cluster_size=186, z_effect=1.1008, presence_gain=0.0000
- ACBD4: score=1.0997, cluster=0, cluster_size=186, z_effect=1.0997, presence_gain=0.0000
- OCIAD1: score=1.0975, cluster=0, cluster_size=186, z_effect=1.0975, presence_gain=0.0000
- AP1AR: score=1.0818, cluster=0, cluster_size=186, z_effect=1.0818, presence_gain=0.0000
- ZNF552: score=1.0798, cluster=0, cluster_size=186, z_effect=1.0798, presence_gain=0.0000
- MLPH: score=1.0767, cluster=0, cluster_size=186, z_effect=1.0767, presence_gain=0.0000
- CNNM3: score=1.0759, cluster=0, cluster_size=186, z_effect=1.0759, presence_gain=0.0000
- FKBP4: score=1.0731, cluster=0, cluster_size=186, z_effect=1.0731, presence_gain=0.0000
- ARSB: score=1.0506, cluster=1, cluster_size=140, z_effect=1.0506, presence_gain=0.0000
- GPNMB: score=0.9454, cluster=1, cluster_size=140, z_effect=0.9454, presence_gain=0.0000
- SULF1: score=0.9364, cluster=1, cluster_size=140, z_effect=0.9364, presence_gain=0.0000
- THY1: score=0.8844, cluster=1, cluster_size=140, z_effect=0.8844, presence_gain=0.0000
- CTHRC1: score=0.8772, cluster=1, cluster_size=140, z_effect=0.8772, presence_gain=0.0000
- MMP1: score=0.8751, cluster=1, cluster_size=140, z_effect=0.8751, presence_gain=0.0000
- COL11A1: score=0.8731, cluster=1, cluster_size=140, z_effect=0.8731, presence_gain=0.0000
- PLXNC1: score=0.8713, cluster=1, cluster_size=140, z_effect=0.8713, presence_gain=0.0000
- GPC6: score=0.8635, cluster=1, cluster_size=140, z_effect=0.8635, presence_gain=0.0000
- TGFBR1: score=0.8621, cluster=1, cluster_size=140, z_effect=0.8621, presence_gain=0.0000
- SERPINF1: score=0.8386, cluster=1, cluster_size=140, z_effect=0.8386, presence_gain=0.0000
- G6PD: score=0.8250, cluster=1, cluster_size=140, z_effect=0.8250, presence_gain=0.0000
- ACTR3: score=0.8212, cluster=1, cluster_size=140, z_effect=0.8212, presence_gain=0.0000
- FBN1: score=0.8172, cluster=1, cluster_size=140, z_effect=0.8172, presence_gain=0.0000
- CHRNA1: score=0.7987, cluster=1, cluster_size=140, z_effect=0.7987, presence_gain=0.0000
- CAP1: score=0.7986, cluster=1, cluster_size=140, z_effect=0.7986, presence_gain=0.0000
- LHFPL2: score=0.7940, cluster=1, cluster_size=140, z_effect=0.7940, presence_gain=0.0000
- DACT1: score=0.7922, cluster=1, cluster_size=140, z_effect=0.7922, presence_gain=0.0000
- CEMIP: score=0.7908, cluster=1, cluster_size=140, z_effect=0.7908, presence_gain=0.0000
- FCGR3A: score=0.7869, cluster=1, cluster_size=140, z_effect=0.7869, presence_gain=0.0000
- ABCA12: score=0.7829, cluster=1, cluster_size=140, z_effect=0.7829, presence_gain=0.0000
- HAVCR2: score=0.7724, cluster=1, cluster_size=140, z_effect=0.7724, presence_gain=0.0000
- RARRES2: score=0.7696, cluster=1, cluster_size=140, z_effect=0.7696, presence_gain=0.0000
- PRRX1: score=0.7637, cluster=1, cluster_size=140, z_effect=0.7637, presence_gain=0.0000
- MARCKS: score=0.7499, cluster=1, cluster_size=140, z_effect=0.7499, presence_gain=0.0000
- VAMP5: score=0.7397, cluster=1, cluster_size=140, z_effect=0.7397, presence_gain=0.0000
- LYZ: score=0.7383, cluster=1, cluster_size=140, z_effect=0.7383, presence_gain=0.0000
- MSC: score=0.7357, cluster=1, cluster_size=140, z_effect=0.7357, presence_gain=0.0000
- COL6A3: score=0.7286, cluster=1, cluster_size=140, z_effect=0.7286, presence_gain=0.0000
- MAFB: score=0.7275, cluster=1, cluster_size=140, z_effect=0.7275, presence_gain=0.0000
- PCDH7: score=0.7173, cluster=1, cluster_size=140, z_effect=0.7173, presence_gain=0.0000
- POSTN: score=0.7150, cluster=1, cluster_size=140, z_effect=0.7150, presence_gain=0.0000
- BLOC1S1: score=1.9423, cluster=2, cluster_size=72, z_effect=1.9423, presence_gain=0.0000
- EDF1: score=1.8549, cluster=2, cluster_size=72, z_effect=1.8549, presence_gain=0.0000
- ELOB: score=1.8519, cluster=2, cluster_size=72, z_effect=1.8519, presence_gain=0.0000
- GADD45GIP1: score=1.8419, cluster=2, cluster_size=72, z_effect=1.8419, presence_gain=0.0000
- ZNF593: score=1.8252, cluster=2, cluster_size=72, z_effect=1.8252, presence_gain=0.0000
- PET100: score=1.8241, cluster=2, cluster_size=72, z_effect=1.8241, presence_gain=0.0000
- COX4I1: score=1.7750, cluster=2, cluster_size=72, z_effect=1.7750, presence_gain=0.0000
- FAU: score=1.7624, cluster=2, cluster_size=72, z_effect=1.7624, presence_gain=0.0000
- RNF181: score=1.7575, cluster=2, cluster_size=72, z_effect=1.7575, presence_gain=0.0000
- SERF2: score=1.6900, cluster=2, cluster_size=72, z_effect=1.6900, presence_gain=0.0000
- MRPL55: score=1.6899, cluster=2, cluster_size=72, z_effect=1.6899, presence_gain=0.0000
- NAA10: score=1.6791, cluster=2, cluster_size=72, z_effect=1.6791, presence_gain=0.0000
- UBL5: score=1.6694, cluster=2, cluster_size=72, z_effect=1.6694, presence_gain=0.0000
- MRPL52: score=1.6210, cluster=2, cluster_size=72, z_effect=1.6210, presence_gain=0.0000
- DRAP1: score=1.6039, cluster=2, cluster_size=72, z_effect=1.6039, presence_gain=0.0000
- CNPY2: score=1.5730, cluster=2, cluster_size=72, z_effect=1.5730, presence_gain=0.0000
- PFDN5: score=1.5678, cluster=2, cluster_size=72, z_effect=1.5678, presence_gain=0.0000
- MSRB2: score=1.5523, cluster=2, cluster_size=72, z_effect=1.5523, presence_gain=0.0000
- TXNDC17: score=1.5516, cluster=2, cluster_size=72, z_effect=1.5516, presence_gain=0.0000
- SNRPF: score=1.5491, cluster=2, cluster_size=72, z_effect=1.5491, presence_gain=0.0000
- CHCHD10: score=1.5349, cluster=2, cluster_size=72, z_effect=1.5349, presence_gain=0.0000
- LSM7: score=1.5347, cluster=2, cluster_size=72, z_effect=1.5347, presence_gain=0.0000
- UXT: score=1.5027, cluster=2, cluster_size=72, z_effect=1.5027, presence_gain=0.0000
- HAUS7: score=1.5017, cluster=2, cluster_size=72, z_effect=1.5017, presence_gain=0.0000
- UQCC2: score=1.4870, cluster=2, cluster_size=72, z_effect=1.4870, presence_gain=0.0000
- SNRPD2: score=1.4838, cluster=2, cluster_size=72, z_effect=1.4838, presence_gain=0.0000
- SURF2: score=1.4681, cluster=2, cluster_size=72, z_effect=1.4681, presence_gain=0.0000
- ZNF787: score=1.4656, cluster=2, cluster_size=72, z_effect=1.4656, presence_gain=0.0000
- TMSB10: score=1.4646, cluster=2, cluster_size=72, z_effect=1.4646, presence_gain=0.0000
- RFXANK: score=1.4564, cluster=2, cluster_size=72, z_effect=1.4564, presence_gain=0.0000
- NDUFA12: score=1.4534, cluster=2, cluster_size=72, z_effect=1.4534, presence_gain=0.0000
- ARL2: score=1.4496, cluster=2, cluster_size=72, z_effect=1.4496, presence_gain=0.0000
- ABCA9: score=1.8169, cluster=3, cluster_size=177, z_effect=1.8169, presence_gain=0.0000
- PLSCR4: score=1.8030, cluster=3, cluster_size=177, z_effect=1.8030, presence_gain=0.0000
- ABCA8: score=1.7806, cluster=3, cluster_size=177, z_effect=1.7806, presence_gain=0.0000
- AASS: score=1.7424, cluster=3, cluster_size=177, z_effect=1.7424, presence_gain=0.0000
- STARD9: score=1.7391, cluster=3, cluster_size=177, z_effect=1.7391, presence_gain=0.0000
- ADAM33: score=1.6903, cluster=3, cluster_size=177, z_effect=1.6903, presence_gain=0.0000
- TGFBR2: score=1.6879, cluster=3, cluster_size=177, z_effect=1.6879, presence_gain=0.0000
- SH3D19: score=1.6795, cluster=3, cluster_size=177, z_effect=1.6795, presence_gain=0.0000
- TTC28: score=1.6719, cluster=3, cluster_size=177, z_effect=1.6719, presence_gain=0.0000
- ABCA10: score=1.6657, cluster=3, cluster_size=177, z_effect=1.6657, presence_gain=0.0000
- RUNX1T1: score=1.6409, cluster=3, cluster_size=177, z_effect=1.6409, presence_gain=0.0000
- DIXDC1: score=1.6391, cluster=3, cluster_size=177, z_effect=1.6391, presence_gain=0.0000
- SHE: score=1.6277, cluster=3, cluster_size=177, z_effect=1.6277, presence_gain=0.0000
- FREM1: score=1.6277, cluster=3, cluster_size=177, z_effect=1.6277, presence_gain=0.0000
- UTRN: score=1.6256, cluster=3, cluster_size=177, z_effect=1.6256, presence_gain=0.0000
- PCSK5: score=1.5984, cluster=3, cluster_size=177, z_effect=1.5984, presence_gain=0.0000
- TNXB: score=1.5794, cluster=3, cluster_size=177, z_effect=1.5794, presence_gain=0.0000
- ADGRA2: score=1.5787, cluster=3, cluster_size=177, z_effect=1.5787, presence_gain=0.0000
- C7: score=1.5494, cluster=3, cluster_size=177, z_effect=1.5494, presence_gain=0.0000
- PRDM2: score=1.5448, cluster=3, cluster_size=177, z_effect=1.5448, presence_gain=0.0000
- SNRK: score=1.5230, cluster=3, cluster_size=177, z_effect=1.5230, presence_gain=0.0000
- ZNF423: score=1.5193, cluster=3, cluster_size=177, z_effect=1.5193, presence_gain=0.0000
- RECK: score=1.5148, cluster=3, cluster_size=177, z_effect=1.5148, presence_gain=0.0000
- GLI2: score=1.5136, cluster=3, cluster_size=177, z_effect=1.5136, presence_gain=0.0000
- TEK: score=1.5076, cluster=3, cluster_size=177, z_effect=1.5076, presence_gain=0.0000
- GEM: score=1.4907, cluster=3, cluster_size=177, z_effect=1.4907, presence_gain=0.0000
- LRRC70: score=1.4819, cluster=3, cluster_size=177, z_effect=1.4819, presence_gain=0.0000
- CCDC80: score=1.4815, cluster=3, cluster_size=177, z_effect=1.4815, presence_gain=0.0000
- CD302: score=1.4667, cluster=3, cluster_size=177, z_effect=1.4667, presence_gain=0.0000
- AHNAK: score=1.4634, cluster=3, cluster_size=177, z_effect=1.4634, presence_gain=0.0000
- SEMA5A: score=1.4531, cluster=3, cluster_size=177, z_effect=1.4531, presence_gain=0.0000
- DDR2: score=1.4506, cluster=3, cluster_size=177, z_effect=1.4506, presence_gain=0.0000
- PSAT1: score=2.6236, cluster=4, cluster_size=96, z_effect=2.6236, presence_gain=0.0000
- FAM171A1: score=2.4856, cluster=4, cluster_size=96, z_effect=2.4856, presence_gain=0.0000
- CDC20: score=2.4116, cluster=4, cluster_size=96, z_effect=2.4116, presence_gain=0.0000
- TTK: score=2.3738, cluster=4, cluster_size=96, z_effect=2.3738, presence_gain=0.0000
- PPP1R14C: score=2.3629, cluster=4, cluster_size=96, z_effect=2.3629, presence_gain=0.0000
- CDCA8: score=2.3409, cluster=4, cluster_size=96, z_effect=2.3409, presence_gain=0.0000
- AURKB: score=2.3032, cluster=4, cluster_size=96, z_effect=2.3032, presence_gain=0.0000
- PIMREG: score=2.2752, cluster=4, cluster_size=96, z_effect=2.2752, presence_gain=0.0000
- ORC1: score=2.2575, cluster=4, cluster_size=96, z_effect=2.2575, presence_gain=0.0000
- SRPK1: score=2.2466, cluster=4, cluster_size=96, z_effect=2.2466, presence_gain=0.0000
- EN1: score=2.2132, cluster=4, cluster_size=96, z_effect=2.2132, presence_gain=0.0000
- NDC80: score=2.1581, cluster=4, cluster_size=96, z_effect=2.1581, presence_gain=0.0000
- AMD1: score=2.1396, cluster=4, cluster_size=96, z_effect=2.1396, presence_gain=0.0000
- MICALL1: score=2.1161, cluster=4, cluster_size=96, z_effect=2.1161, presence_gain=0.0000
- DEPDC1: score=2.1150, cluster=4, cluster_size=96, z_effect=2.1150, presence_gain=0.0000
- RRP1B: score=2.1083, cluster=4, cluster_size=96, z_effect=2.1083, presence_gain=0.0000
- E2F3: score=2.0906, cluster=4, cluster_size=96, z_effect=2.0906, presence_gain=0.0000
- LDHB: score=2.0795, cluster=4, cluster_size=96, z_effect=2.0795, presence_gain=0.0000
- MELK: score=2.0688, cluster=4, cluster_size=96, z_effect=2.0688, presence_gain=0.0000
- LBR: score=2.0339, cluster=4, cluster_size=96, z_effect=2.0339, presence_gain=0.0000
- HJURP: score=2.0132, cluster=4, cluster_size=96, z_effect=2.0132, presence_gain=0.0000
- CLCN4: score=2.0127, cluster=4, cluster_size=96, z_effect=2.0127, presence_gain=0.0000
- XPO5: score=2.0095, cluster=4, cluster_size=96, z_effect=2.0095, presence_gain=0.0000
- FOXM1: score=2.0041, cluster=4, cluster_size=96, z_effect=2.0041, presence_gain=0.0000
- ARL9: score=1.9886, cluster=4, cluster_size=96, z_effect=1.9886, presence_gain=0.0000
- STK38: score=1.9835, cluster=4, cluster_size=96, z_effect=1.9835, presence_gain=0.0000
- TICRR: score=1.9773, cluster=4, cluster_size=96, z_effect=1.9773, presence_gain=0.0000
- ANLN: score=1.9749, cluster=4, cluster_size=96, z_effect=1.9749, presence_gain=0.0000
- SERBP1: score=1.9582, cluster=4, cluster_size=96, z_effect=1.9582, presence_gain=0.0000
- TPX2: score=1.9425, cluster=4, cluster_size=96, z_effect=1.9425, presence_gain=0.0000
- COMMD2: score=1.9406, cluster=4, cluster_size=96, z_effect=1.9406, presence_gain=0.0000
- KCNQ4: score=1.9365, cluster=4, cluster_size=96, z_effect=1.9365, presence_gain=0.0000

CANDIDATE_GENES:
['ESR1', 'GATA3', 'NECAB3', 'PARD6B', 'MOAP1', 'ABCA3', 'LCMT2', 'CPLX1', 'TSPAN13', 'COG7', 'HEXIM2', 'PLA2G12A', 'AFF3', 'COQ7', 'GATAD1', 'RAD17', 'GAMT', 'EXD2', 'CCND1', 'CACNA2D2', 'PPIP5K1', 'PEX12', 'PNPLA4', 'ZNF24', 'LAMTOR3', 'ACBD4', 'OCIAD1', 'AP1AR', 'ZNF552', 'MLPH', 'CNNM3', 'FKBP4', 'ARSB', 'GPNMB', 'SULF1', 'THY1', 'CTHRC1', 'MMP1', 'COL11A1', 'PLXNC1', 'GPC6', 'TGFBR1', 'SERPINF1', 'G6PD', 'ACTR3', 'FBN1', 'CHRNA1', 'CAP1', 'LHFPL2', 'DACT1', 'CEMIP', 'FCGR3A', 'ABCA12', 'HAVCR2', 'RARRES2', 'PRRX1', 'MARCKS', 'VAMP5', 'LYZ', 'MSC', 'COL6A3', 'MAFB', 'PCDH7', 'POSTN', 'BLOC1S1', 'EDF1', 'ELOB', 'GADD45GIP1', 'ZNF593', 'PET100', 'COX4I1', 'FAU', 'RNF181', 'SERF2', 'MRPL55', 'NAA10', 'UBL5', 'MRPL52', 'DRAP1', 'CNPY2', 'PFDN5', 'MSRB2', 'TXNDC17', 'SNRPF', 'CHCHD10', 'LSM7', 'UXT', 'HAUS7', 'UQCC2', 'SNRPD2', 'SURF2', 'ZNF787', 'TMSB10', 'RFXANK', 'NDUFA12', 'ARL2', 'ABCA9', 'PLSCR4', 'ABCA8', 'AASS', 'STARD9', 'ADAM33', 'TGFBR2', 'SH3D19', 'TTC28', 'ABCA10', 'RUNX1T1', 'DIXDC1', 'SHE', 'FREM1', 'UTRN', 'PCSK5', 'TNXB', 'ADGRA2', 'C7', 'PRDM2', 'SNRK', 'ZNF423', 'RECK', 'GLI2', 'TEK', 'GEM', 'LRRC70', 'CCDC80', 'CD302', 'AHNAK', 'SEMA5A', 'DDR2', 'PSAT1', 'FAM171A1', 'CDC20', 'TTK', 'PPP1R14C', 'CDCA8', 'AURKB', 'PIMREG', 'ORC1', 'SRPK1', 'EN1', 'NDC80', 'AMD1', 'MICALL1', 'DEPDC1', 'RRP1B', 'E2F3', 'LDHB', 'MELK', 'LBR', 'HJURP', 'CLCN4', 'XPO5', 'FOXM1', 'ARL9', 'STK38', 'TICRR', 'ANLN', 'SERBP1', 'TPX2', 'COMMD2', 'KCNQ4', 'TMEM154', 'SLC22A14', 'CIB1', 'FBXL8', 'LRRC8E', 'TMEM165', 'IFFO2', 'TSPAN2', 'TMEM168', 'LRRD1', 'TMEM17', 'TMEM170A', 'PITPNC1', 'SLC20A2', 'RARB', 'CHST6', 'TMEM167B', 'LRRC58', 'FBXL18', 'PKD1L1', 'LRRC63', 'CIR1', 'IFI44', 'TMEM144', 'FBXL4', 'FBXL2', 'LRRC7', 'PJA2', 'CIDEC', 'FBXL20', 'FBXL3', 'TMEM150C', 'CINP', 'CHRNA3', 'FBXO31', 'PIP4K2C', 'CHRM5', 'CHRM4', 'CHRM3', 'RARG', 'CHRM1', 'CHRFAM7A', 'IDS', 'CHRDL1', 'FBXO34', 'CHRAC1', 'LSG1', 'LSM14A', 'FBXO32', 'CHST4', 'CHST3', 'CHST2', 'CHST15', 'LRRIQ4', 'TMEM176B', 'TMEM178A', 'FBXO30', 'LRRN2', 'PIPOX', 'FBXO28', 'CHRNB2', 'TMEM184A', 'LRRTM2', 'TMEM184C', 'CHRNA5', 'PIR', 'PLA2G2D', 'PLA2G2C', 'FAXC', 'RANGAP1', 'LRRC27', 'RANGRF', 'LRRC29', 'CISD3', 'TMED9', 'TMEM100', 'TMEM101', 'TMEM102', 'CLDN18', 'TMEM104', 'LRRC31', 'TMED8', 'CLEC4A', 'SLC25A15', 'RANBP10', 'PLA2R1', 'SLC25A12', 'CLEC1A', 'SLC24A4', 'FAT3', 'CLEC16A', 'PLA2G3', 'FATE1', 'CLEC12A', 'LRRC19', 'LRRC2', 'CLDND2', 'CLDND1', 'CLEC18A', 'SLC22A4', 'TMEM126B', 'SLC22A31', 'CKS1B', 'CKMT2', 'CKMT1B', 'CKMT1A', 'FBL', 'LRRC46', 'FBRSL1', 'PKIA', 'FBXL13', 'CKAP2', 'RAPGEF1', 'PKDCC', 'PKD2', 'RAP2B', 'FBLIM1', 'CLDN12', 'RAP1GAP', 'TMEM109', 'TMEM11', 'PKP2', 'LRRC37A3', 'CLCN6', 'LRRC41', 'PKP1', 'CLCF1', 'CLCC1', 'IFITM1', 'CLCA2', 'IFIT5', 'TMEM116', 'CFAP77', 'TMEM37', 'LYL1', 'TMEM38B', 'LYN', 'LYPD1', 'CFAP58', 'RASA4', 'CFAP54', 'PIGB', 'CFAP52', 'LYPD3', 'CFAP46', 'SLC15A4', 'PIFO', 'LYPD6', 'CFAP57', 'SLC16A14', 'PIGO', 'RASGRP1', 'TMEM266', 'SLC44A4', 'SCNN1A', 'SLC7A8', 'ALKBH3', 'C9ORF152', 'SMIM14', 'PLEKHA6', 'RB1', 'VAV3', 'DSP', 'SEC24C', 'CSTF2T', 'TEAD2', 'MGST1', 'BOK', 'MYOF', 'TSPAN15', 'DAZAP2', 'TOX4', 'CDH1', 'PHF2', 'SEZ6L2', 'NPDC1', 'STAT6', 'NEO1', 'FAM174B', 'REEP6', 'TES', 'ZFYVE9', 'SH3BP4', 'KRT19', 'GPD1L', 'ERBIN', 'SIDT1', 'MAGEH1', 'GLT8D1', 'PDCD6IP', 'SPG11', 'SNAP23', 'ZNF175', 'SMIM22', 'DHCR24', 'HSPG2', 'USP4', 'FUBP3', 'RECQL', 'IGF1R', 'GABARAPL1', 'APPL1', 'EFS', 'BCOR', 'SEMA3C', 'RIPK1', 'ZNF467', 'SP1', 'GTF2F1', 'ERCC5', 'ISG20', 'DAB2', 'SULT1A3', 'PANO1', 'ZNF513', 'RASAL2', 'SORL1', 'FAM209B', 'KIF20B', 'AGO1', 'MAX', 'HMG20A', 'GZMM', 'CDK10', 'METTL17', 'BTBD8', 'NFKB2', 'BNC2', 'TRAM2', 'MXD3', 'PSMB6', 'GGA1', 'PPP1R7', 'SSBP1', 'ACER2', 'NT5C', 'TMTC3', 'PCNX1', 'KDELR1', 'MDH1']

[EVIDENCE 1] source=ChEA type=tf_target_set title=ChEA term HNF4A 19822575 ChIP-Seq HepG2 Human
GENES=['AASS', 'ABCA8', 'ABCA9', 'ACTR3', 'AFF3', 'AHNAK', 'ARSB', 'AURKB', 'BCOR', 'BNC2', 'BOK', 'CAP1']
ChEA tf_target_set ChEA term HNF4A 19822575 ChIP-Seq HepG2 Human 候选基因交集：AASS, ABCA8, ABCA9, ACTR3, AFF3, AHNAK, ARSB, AURKB, BCOR, BNC2, BOK, CAP1, CCND1, CD302, CDH1, CDK10, CHRAC

[EVIDENCE 2] source=ChEA type=tf_target_set title=ChEA term FLI1 21571218 ChIP-Seq MEGAKARYOCYTES Human
GENES=['ABCA3', 'ACTR3', 'AHNAK', 'AMD1', 'AURKB', 'BCOR', 'BLOC1S1', 'CAP1', 'CHRAC1', 'CHRM3', 'CHST15', 'CHST6']
ChEA tf_target_set ChEA term FLI1 21571218 ChIP-Seq MEGAKARYOCYTES Human 候选基因交集：ABCA3, ACTR3, AHNAK, AMD1, AURKB, BCOR, BLOC1S1, CAP1, CHRAC1, CHRM3, CHST15, CHST6, CINP, CIR1, CLC

[EVIDENCE 3] source=MSigDB type=gene_set title=MSigDB gene set GOBP_CELL_CYCLE
GENES=['ACTR3', 'ANLN', 'APPL1', 'ARL2', 'AURKB', 'CCND1', 'CDC20', 'CDCA8', 'CDK10', 'CIB1', 'CKAP2', 'CKS1B']
MSigDB gene_set MSigDB gene set GOBP_CELL_CYCLE 候选基因交集：ACTR3, ANLN, APPL1, ARL2, AURKB, CCND1, CDC20, CDCA8, CDK10, CIB1, CKAP2, CKS1B, DACT1, DDR2, E2F3, FBXL13, FBXO30, FBXO31, F

[EVIDENCE 4] source=MSigDB type=gene_set title=MSigDB gene set GOBP_CELL_CYCLE_PROCESS
GENES=['ACTR3', 'ANLN', 'APPL1', 'ARL2', 'AURKB', 'CCND1', 'CDC20', 'CDCA8', 'CDK10', 'CKAP2', 'DACT1', 'DDR2']
MSigDB gene_set MSigDB gene set GOBP_CELL_CYCLE_PROCESS 候选基因交集：ACTR3, ANLN, APPL1, ARL2, AURKB, CCND1, CDC20, CDCA8, CDK10, CKAP2, DACT1, DDR2, E2F3, FBXL13, FBXO30, FBXO31, FOXM1,

[EVIDENCE 5] source=PanglaoDB type=cell_type_marker title=PanglaoDB markers for Fibroblasts
GENES=['ADAM33', 'COL6A3', 'CTHRC1', 'FBN1', 'PKD2', 'POSTN', 'PRRX1', 'RARRES2', 'TNXB']
PanglaoDB cell_type_marker PanglaoDB markers for Fibroblasts 候选基因交集：ADAM33, COL6A3, CTHRC1, FBN1, PKD2, POSTN, PRRX1, RARRES2, TNXB

[EVIDENCE 6] source=Reactome type=pathway_gene_set title=Reactome pathway Signal Transduction
GENES=['ACTR3', 'AGO1', 'ANLN', 'ARL2', 'AURKB', 'CCND1', 'CDC20', 'CDCA8', 'CDH1', 'CHRDL1', 'CHRM1', 'CHRM3']
Reactome pathway_gene_set Reactome pathway Signal Transduction 候选基因交集：ACTR3, AGO1, ANLN, ARL2, AURKB, CCND1, CDC20, CDCA8, CDH1, CHRDL1, CHRM1, CHRM3, CHRM4, CHRM5, COL11A1, COL6A3

[EVIDENCE 7] source=Reactome type=pathway_gene_set title=Reactome pathway Disease
GENES=['ABCA12', 'ABCA3', 'ACTR3', 'AGO1', 'ARSB', 'CCND1', 'CDH1', 'CHST3', 'CHST6', 'CLCN6', 'CSTF2T', 'E2F3']
Reactome pathway_gene_set Reactome pathway Disease 候选基因交集：ABCA12, ABCA3, ACTR3, AGO1, ARSB, CCND1, CDH1, CHST3, CHST6, CLCN6, CSTF2T, E2F3, ELOB, ERBIN, ESR1, FAU, FCGR3A, FKBP4, F

[EVIDENCE 8] source=Reactome type=pathway_gene_set title=Reactome pathway Gene expression (Transcription)
GENES=['AGO1', 'AURKB', 'CCND1', 'CIDEC', 'COX4I1', 'CSTF2T', 'ELOB', 'ESR1', 'FBXO32', 'G6PD', 'GAMT', 'GATA3']
Reactome pathway_gene_set Reactome pathway Gene expression (Transcription) 候选基因交集：AGO1, AURKB, CCND1, CIDEC, COX4I1, CSTF2T, ELOB, ESR1, FBXO32, G6PD, GAMT, GATA3, GEM, GLI2, GTF2F

[EVIDENCE 9] source=RegNetwork type=regulator_targets title=RegNetwork regulator HSA-MIR-503
GENES=['ANLN', 'ARL2', 'BNC2', 'CCND1', 'DIXDC1', 'E2F3']
RegNetwork regulator_targets RegNetwork regulator HSA-MIR-503 候选基因交集：ANLN, ARL2, BNC2, CCND1, DIXDC1, E2F3

[EVIDENCE 10] source=RegNetwork type=regulator_targets title=RegNetwork regulator ALX1
GENES=['PCDH7', 'PCSK5', 'RUNX1T1', 'SH3D19', 'TEK']
RegNetwork regulator_targets RegNetwork regulator ALX1 候选基因交集：PCDH7, PCSK5, RUNX1T1, SH3D19, TEK

[EVIDENCE 11] source=RegNetwork type=regulator_targets title=RegNetwork regulator HSA-MIR-429
GENES=['AFF3', 'AHNAK', 'ANLN', 'AP1AR', 'APPL1', 'BNC2']
RegNetwork regulator_targets RegNetwork regulator HSA-MIR-429 候选基因交集：AFF3, AHNAK, ANLN, AP1AR, APPL1, BNC2

[EVIDENCE 12] source=STRING type=ppi_neighbors title=STRING neighbors of HAVCR2
GENES=['HAVCR2']
STRING ppi_neighbors STRING neighbors of HAVCR2 候选基因交集：HAVCR2

[EVIDENCE 13] source=STRING type=ppi_neighbors title=STRING neighbors of FCGR3A
GENES=['FCGR3A']
STRING ppi_neighbors STRING neighbors of FCGR3A 候选基因交集：FCGR3A

[EVIDENCE 14] source=STRING type=ppi_neighbors title=STRING neighbors of FBN1
GENES=['FBN1']
STRING ppi_neighbors STRING neighbors of FBN1 候选基因交集：FBN1

Return ONLY JSON. No markdown. No extra text.
```


## Qwen Raw Response

```
{
  "global_gene_weights": [
    {"gene": "ESR1", "weight": 1.55, "reason": "Top discriminative marker for luminal cluster with high z-effect."},
    {"gene": "GATA3", "weight": 1.35, "reason": "Strong luminal marker supporting cluster 0 separation."},
    {"gene": "PSAT1", "weight": 2.62, "reason": "Highest variance gene defining cluster 4 proliferation axis."},
    {"gene": "BLOC1S1", "weight": 1.94, "reason": "Top discriminative marker for cluster 2 mitochondrial program."},
    {"gene": "ABCA9", "weight": 1.82, "reason": "High variance marker defining cluster 3 distinct identity."},
    {"gene": "ARSB", "weight": 1.05, "reason": "Key marker for cluster 1 mesenchymal/stromal separation."},
    {"gene": "CCND1", "weight": 1.15, "reason": "Cell cycle regulator supporting cluster 4 proliferation."},
    {"gene": "AURKB", "weight": 2.30, "reason": "Mitotic marker highly specific to cluster 4."},
    {"gene": "GPNMB", "weight": 0.95, "reason": "Mesenchymal marker aiding cluster 1 separation."},
    {"gene": "COX4I1", "weight": 1.78, "reason": "Mitochondrial marker defining cluster 2 metabolic state."},
    {"gene": "ACTR3", "weight": 0.82, "reason": "Cell cycle gene supported by multiple pathway databases."},
    {"gene": "AHNAK", "weight": 1.46, "reason": "Cluster 3 marker supported by multiple regulatory networks."}
  ],
  "suppress_genes": [],
  "modules": [
    {
      "name": "module_1",
      "genes": ["ESR1", "GATA3", "CCND1", "CDCA8", "AURKB", "ANLN"],
      "weight": 1.2,
      "reason": "Luminal and proliferation axis separating cluster 0 from cluster 4."
    },
    {
      "name": "module_2",
      "genes": ["BLOC1S1", "COX4I1", "EDF1", "GADD45GIP1", "ABCA9", "PLSCR4"],
      "weight": 1.1,
      "reason": "Metabolic and mitochondrial axis separating cluster 2 from others."
    }
  ],
  "prototypes": [
    {
      "name": "prototype_1",
      "genes_up": ["ESR1", "GATA3", "CCND1", "AURKB", "PSAT1"],
      "genes_down": ["BLOC1S1", "COX4I1", "ARSB", "GPNMB"]
    }
  ],
  "key_gene_sets": ["Luminal_Program", "Proliferation_Program", "Mitochondrial_Program", "Mesenchymal_Program"],
  "key_regulators": ["ESR1", "GATA3", "CCND1", "AURKB"],
  "notes": ["Prioritized genes with high GENE_DISCRIMINATIVE_STATS scores.", "Avoided generic immune/stromal markers unless cluster-specific.", "Selected genes from diverse cluster blocks to ensure separation."]
}
```


## Parsed Prior JSON

```json
{
  "global_gene_weights": [
    {
      "gene": "ESR1",
      "weight": 1.55,
      "reason": "Top discriminative marker for luminal cluster with high z-effect."
    },
    {
      "gene": "GATA3",
      "weight": 1.35,
      "reason": "Strong luminal marker supporting cluster 0 separation."
    },
    {
      "gene": "PSAT1",
      "weight": 2.62,
      "reason": "Highest variance gene defining cluster 4 proliferation axis."
    },
    {
      "gene": "BLOC1S1",
      "weight": 1.94,
      "reason": "Top discriminative marker for cluster 2 mitochondrial program."
    },
    {
      "gene": "ABCA9",
      "weight": 1.82,
      "reason": "High variance marker defining cluster 3 distinct identity."
    },
    {
      "gene": "ARSB",
      "weight": 1.05,
      "reason": "Key marker for cluster 1 mesenchymal/stromal separation."
    },
    {
      "gene": "CCND1",
      "weight": 1.15,
      "reason": "Cell cycle regulator supporting cluster 4 proliferation."
    },
    {
      "gene": "AURKB",
      "weight": 2.3,
      "reason": "Mitotic marker highly specific to cluster 4."
    },
    {
      "gene": "GPNMB",
      "weight": 0.95,
      "reason": "Mesenchymal marker aiding cluster 1 separation."
    },
    {
      "gene": "COX4I1",
      "weight": 1.78,
      "reason": "Mitochondrial marker defining cluster 2 metabolic state."
    },
    {
      "gene": "ACTR3",
      "weight": 0.82,
      "reason": "Cell cycle gene supported by multiple pathway databases."
    },
    {
      "gene": "AHNAK",
      "weight": 1.46,
      "reason": "Cluster 3 marker supported by multiple regulatory networks."
    }
  ],
  "suppress_genes": [],
  "modules": [
    {
      "name": "module_1",
      "genes": [
        "ESR1",
        "GATA3",
        "CCND1",
        "CDCA8",
        "AURKB",
        "ANLN"
      ],
      "weight": 1.2,
      "reason": "Luminal and proliferation axis separating cluster 0 from cluster 4."
    },
    {
      "name": "module_2",
      "genes": [
        "BLOC1S1",
        "COX4I1",
        "EDF1",
        "GADD45GIP1",
        "ABCA9",
        "PLSCR4"
      ],
      "weight": 1.1,
      "reason": "Metabolic and mitochondrial axis separating cluster 2 from others."
    }
  ],
  "prototypes": [
    {
      "name": "prototype_1",
      "genes_up": [
        "ESR1",
        "GATA3",
        "CCND1",
        "AURKB",
        "PSAT1"
      ],
      "genes_down": [
        "BLOC1S1",
        "COX4I1",
        "ARSB",
        "GPNMB"
      ]
    }
  ],
  "key_gene_sets": [
    "Luminal_Program",
    "Proliferation_Program",
    "Mitochondrial_Program",
    "Mesenchymal_Program"
  ],
  "key_regulators": [
    "ESR1",
    "GATA3",
    "CCND1",
    "AURKB"
  ],
  "notes": [
    "Prioritized genes with high GENE_DISCRIMINATIVE_STATS scores.",
    "Avoided generic immune/stromal markers unless cluster-specific.",
    "Selected genes from diverse cluster blocks to ensure separation."
  ]
}
```



# Qwen Prior Application To Expression Matrix

## 1. Application Pipeline

The final Qwen prior is projected back to the aligned expression matrix in this order:

```text
aligned_expression_before_qwen
  -> _apply_global_gene_weights
  -> _apply_module_priors        [only when apply_mode in {full, deep_full}]
  -> _apply_prototype_priors     [only when apply_mode in {full, deep_full}]
  -> _apply_sample_specific_priors [only when apply_mode == deep_full]
  -> clean_numeric_df
  -> qwen_guided_expression.csv
```

## 2. Effective Application Config

- apply_mode: `deep_full`
- weight_strength: `0.16`
- effective_weight_min: `0.86`
- effective_weight_max: `1.2`
- network_diffusion_steps: `1`
- network_diffusion_alpha: `0.08`
- module_strength: `0.12`
- prototype_strength: `0.0`
- sample_gate_strength: `0.0`

## 3. Mathematical Meaning Of Each Stage

### 3.1 Global gene weights

For each Qwen-selected gene, the LLM weight is converted into a bounded effective weight:
```text
effective_weight = clip(1 + weight_strength * (qwen_weight - 1),
                        effective_weight_min, effective_weight_max)
```
Then the expression column is modified in a sample-aware way:
```text
z_gene = (x_gene - mean(x_gene)) / (std(x_gene) + 1e-6)
x_gene_new = x_gene * (1 + (effective_weight - 1) * z_gene)
```
This means samples with higher expression of that gene receive stronger modulation.

### 3.2 Module priors

For each Qwen module:
```text
module_signal = mean(expression of genes in this module, per sample)
x_module_genes_new = x_module_genes + module_strength * module_weight * module_signal
```
This reinforces a co-expression program proposed by Qwen.

### 3.3 Prototype priors

For each prototype:
```text
prototype_score = mean(genes_up) - mean(genes_down)
prototype_score = zscore(prototype_score)
genes_up   *= 1 + prototype_strength * prototype_score
genes_down *= 1 - prototype_strength * prototype_score
```
If prototype_strength is 0, this stage records prototype features but does not change expression.

### 3.4 Sample-specific gate

For deep_full mode, module/prototype scores can further modulate genes per sample:
```text
gate = 1 + sample_gate_strength * z(module_or_prototype_score)
x_selected_genes_new = x_selected_genes * gate
```
If sample_gate_strength is 0, this stage does not change expression.

## 4. Final Prior Size After Filtering

- global_gene_weights: `43`
- modules: `4`
- prototypes: `1`
- non-default genes in final weight_map: `500`

## 5. Global Gene Weight Map Used For Matrix Projection

| gene | effective_weight |
|---|---:|
| AURKB | 1.184273 |
| COX4I1 | 1.147494 |
| ESR1 | 1.122454 |
| GATA3 | 1.088606 |
| AHNAK | 1.088602 |
| CCND1 | 1.063583 |
| E2F3 | 1.041503 |
| ARSB | 1.040043 |
| NDC80 | 1.037134 |
| FAU | 1.037112 |
| ABCA3 | 1.037109 |
| ARL2 | 1.037101 |
| PCSK5 | 1.037100 |
| FKBP4 | 1.037098 |
| ANLN | 1.037095 |
| COG7 | 1.032696 |
| COMMD2 | 1.032684 |
| CLCN6 | 1.032684 |
| CHST3 | 1.032679 |
| SP1 | 1.032677 |
| TGFBR2 | 1.032677 |
| DIXDC1 | 1.025320 |
| ELOB | 1.022400 |
| FOXM1 | 1.020939 |
| AP1AR | 1.020932 |
| RAD17 | 1.020928 |
| SNRPD2 | 1.020928 |
| DRAP1 | 1.020927 |
| PSMB6 | 1.020927 |
| CDCA8 | 1.020923 |
| PEX12 | 1.020923 |
| CDC20 | 1.020920 |
| SH3D19 | 1.020918 |
| GEM | 1.020913 |
| DDR2 | 1.020911 |
| FAM171A1 | 1.020911 |
| SEMA5A | 1.020910 |
| LYN | 1.020908 |
| DAB2 | 1.020907 |
| AFF3 | 1.020905 |
| PARD6B | 1.020905 |
| BNC2 | 1.020902 |
| CLCN4 | 1.016490 |
| ADGRB1 | 1.003584 |
| AAR2 | 1.001576 |
| ABHD16A | 1.000709 |
| ACTRT3 | 1.000662 |
| AKAP17A | 1.000523 |
| AKIP1 | 1.000431 |
| ACTR3C | 1.000420 |
| ACTRT1 | 1.000392 |
| AGAP6 | 1.000385 |
| AGAP5 | 1.000384 |
| AARD | 1.000382 |
| ADH1C | 1.000377 |
| AK4 | 1.000370 |
| AIMP1 | 1.000365 |
| A4GNT | 1.000365 |
| AIMP2 | 1.000364 |
| ACTL8 | 1.000356 |
| AADACL3 | 1.000355 |
| AGER | 1.000355 |
| AKR1C1 | 1.000353 |
| ABCF3 | 1.000352 |
| ADM2 | 1.000352 |
| ADAM18 | 1.000350 |
| ABO | 1.000349 |
| ACOT13 | 1.000348 |
| ACD | 1.000348 |
| ADGRE5 | 1.000347 |
| AHNAK2 | 1.000345 |
| ACTL7A | 1.000343 |
| ACSM2A | 1.000341 |
| ACAD8 | 1.000341 |
| ABCA2 | 1.000340 |
| ACSM2B | 1.000339 |
| ADAT3 | 1.000339 |
| ACR | 1.000338 |
| AGTR2 | 1.000338 |
| ACAP1 | 1.000338 |
| AFM | 1.000337 |
| ACP1 | 1.000337 |
| ADAMDEC1 | 1.000336 |
| ADH1B | 1.000336 |
| ACY1 | 1.000335 |
| AEN | 1.000335 |
| ACTR5 | 1.000334 |
| AADACL4 | 1.000334 |
| A2ML1 | 1.000333 |
| ACTL6B | 1.000333 |
| ADNP2 | 1.000333 |
| ABCG5 | 1.000331 |
| ACER1 | 1.000331 |
| ADH1A | 1.000331 |
| ACSM4 | 1.000331 |
| ACOT4 | 1.000331 |
| AARSD1 | 1.000330 |
| ABCE1 | 1.000329 |
| ADAL | 1.000329 |
| ABCG8 | 1.000329 |
| ABI3 | 1.000329 |
| AADAC | 1.000329 |
| ACTL7B | 1.000329 |
| ADPRH | 1.000329 |
| ACTN3 | 1.000329 |
| AGBL1 | 1.000328 |
| AKR1B10 | 1.000328 |
| AIDA | 1.000328 |
| AGAP2 | 1.000327 |
| ABCF1 | 1.000327 |
| ACAD9 | 1.000327 |
| ADAD1 | 1.000327 |
| A3GALT2 | 1.000327 |
| ABCB5 | 1.000327 |
| AHSA1 | 1.000326 |
| ADAMTS13 | 1.000326 |
| AIRE | 1.000326 |
| ABHD8 | 1.000325 |
| AIF1L | 1.000325 |
| ACSM3 | 1.000325 |
| ACSM5 | 1.000325 |
| AIM2 | 1.000325 |
| AKAP3 | 1.000325 |
| AK8 | 1.000324 |
| AASS | 1.000324 |
| AGA | 1.000324 |
| AGBL3 | 1.000323 |
| ADCY4 | 1.000323 |
| AKR1B1 | 1.000323 |
| A2M | 1.000322 |
| AAGAB | 1.000322 |
| ABCC8 | 1.000322 |
| ABHD1 | 1.000322 |
| ABHD14A | 1.000322 |
| ADIG | 1.000321 |
| AFP | 1.000321 |
| AATK | 1.000321 |
| ABHD10 | 1.000321 |
| ACP5 | 1.000321 |
| ACCS | 1.000321 |
| AIFM1 | 1.000321 |
| ACAT2 | 1.000321 |
| ADAMTSL2 | 1.000321 |
| AGK | 1.000321 |
| ACTR10 | 1.000320 |
| ACOT6 | 1.000320 |
| ADCYAP1 | 1.000320 |
| ABCC11 | 1.000320 |
| AASDH | 1.000320 |
| AKAP8 | 1.000320 |
| ACTR8 | 1.000320 |
| AANAT | 1.000320 |
| ACBD4 | 1.000319 |
| AFMID | 1.000319 |
| ABCB7 | 1.000319 |
| ACSBG1 | 1.000319 |
| ADCYAP1R1 | 1.000319 |
| AARS2 | 1.000318 |
| ACYP1 | 1.000318 |
| ADAM29 | 1.000318 |
| AGRP | 1.000318 |
| ACO2 | 1.000318 |
| ABHD15 | 1.000318 |
| ABHD12B | 1.000317 |
| ABCG4 | 1.000317 |
| ADHFE1 | 1.000317 |
| AK7 | 1.000317 |
| ACOT1 | 1.000317 |
| ABCB11 | 1.000317 |
| ADCY10 | 1.000317 |
| ACTN2 | 1.000316 |
| ADAT1 | 1.000316 |
| AGR3 | 1.000316 |
| ACOT8 | 1.000316 |
| ACTA1 | 1.000316 |
| ADAM11 | 1.000316 |
| ABCA9 | 1.000316 |
| ACTC1 | 1.000316 |
| AADAT | 1.000316 |
| ACADVL | 1.000316 |
| ADSL | 1.000316 |
| AK1 | 1.000316 |
| ACRV1 | 1.000315 |
| ACAP3 | 1.000315 |
| AGXT | 1.000315 |
| ACOT9 | 1.000315 |
| AKAP5 | 1.000315 |
| ACADL | 1.000315 |
| ACADSB | 1.000314 |
| ADAM15 | 1.000314 |
| ADH5 | 1.000314 |
| ACBD7 | 1.000314 |
| AHSG | 1.000314 |
| ADAMTSL5 | 1.000314 |
| A4GALT | 1.000314 |
| ABCB8 | 1.000314 |
| ABHD11 | 1.000314 |
| ABI2 | 1.000314 |
| ACTR1B | 1.000314 |
| ADAM9 | 1.000314 |
| ABI3BP | 1.000313 |
| ACE | 1.000313 |
| AGMO | 1.000313 |
| ABHD12 | 1.000313 |
| ADAMTS10 | 1.000313 |
| AGR2 | 1.000313 |
| AASDHPPT | 1.000313 |
| ACTG2 | 1.000313 |
| AGMAT | 1.000313 |
| ABHD13 | 1.000312 |
| ACER3 | 1.000312 |
| ACHE | 1.000312 |
| ACOX1 | 1.000312 |
| ACVRL1 | 1.000312 |
| ADAT2 | 1.000312 |
| ADCY3 | 1.000312 |
| ACTL9 | 1.000312 |
| ABCA6 | 1.000312 |
| ACTRT2 | 1.000312 |
| ADH4 | 1.000312 |
| AAMP | 1.000312 |
| ABCA7 | 1.000312 |
| ABCC12 | 1.000312 |
| ACSF3 | 1.000312 |
| ADCK5 | 1.000312 |
| AFAP1L1 | 1.000312 |
| AHRR | 1.000312 |
| ABCC6 | 1.000312 |
| ABCA12 | 1.000311 |
| ADAM28 | 1.000311 |
| ABCA13 | 1.000311 |
| ABCC10 | 1.000311 |
| ABHD3 | 1.000311 |
| ABT1 | 1.000311 |
| ACTR3B | 1.000311 |
| ADCK2 | 1.000311 |
| ADRB3 | 1.000311 |
| AFAP1L2 | 1.000311 |
| AGPAT1 | 1.000311 |
| ADAMTS7 | 1.000311 |
| ACAA2 | 1.000311 |
| ADORA2A | 1.000310 |
| ADAM32 | 1.000310 |
| ADA | 1.000310 |
| ADRA2C | 1.000310 |
| ADRM1 | 1.000310 |
| AGT | 1.000310 |
| AIF1 | 1.000310 |
| ADAMTS5 | 1.000310 |
| ADAP2 | 1.000310 |
| ACOX2 | 1.000310 |
| ADAMTS9 | 1.000310 |
| ABCC2 | 1.000310 |
| ABHD4 | 1.000310 |
| ACSBG2 | 1.000310 |
| ADIPOR1 | 1.000310 |
| AIP | 1.000310 |
| AGAP3 | 1.000309 |
| ADH7 | 1.000309 |
| ADRA1B | 1.000309 |
| ABCB6 | 1.000309 |
| ACTA2 | 1.000309 |
| AFG3L2 | 1.000309 |
| AGFG1 | 1.000309 |
| AGPAT2 | 1.000309 |
| ADAM7 | 1.000309 |
| ABTB1 | 1.000309 |
| ACLY | 1.000309 |
| ACSM1 | 1.000308 |
| AACS | 1.000308 |
| ACIN1 | 1.000308 |
| ACSS2 | 1.000308 |
| ADCY6 | 1.000308 |
| ADIPOQ | 1.000308 |
| ABRA | 1.000308 |
| ADAMTS15 | 1.000308 |
| ABCD1 | 1.000308 |
| ACOT2 | 1.000308 |
| AIPL1 | 1.000308 |
| ADRA2B | 1.000308 |
| ADAP1 | 1.000308 |
| ABAT | 1.000308 |
| ABCF2 | 1.000308 |
| ACADM | 1.000308 |
| ADRA1A | 1.000308 |
| ADRA1D | 1.000308 |
| AFF4 | 1.000308 |
| AKAP8L | 1.000308 |
| ADD2 | 1.000307 |
| ABHD5 | 1.000307 |
| ACP2 | 1.000307 |
| ADAMTS6 | 1.000307 |
| ADAMTSL4 | 1.000307 |
| AKAP10 | 1.000307 |
| ACSL4 | 1.000307 |
| ACAT1 | 1.000307 |
| AKR1A1 | 1.000307 |
| ACE2 | 1.000307 |
| ACAD10 | 1.000306 |
| ACY3 | 1.000306 |
| ACTL6A | 1.000306 |
| ACTR6 | 1.000306 |
| ADAMTSL1 | 1.000306 |
| ADPRHL1 | 1.000306 |
| AGL | 1.000306 |
| ABCB10 | 1.000306 |
| ABLIM2 | 1.000306 |
| ACOX3 | 1.000306 |
| ACVR2B | 1.000306 |
| ADAMTS8 | 1.000306 |
| ADRA2A | 1.000306 |
| AGTR1 | 1.000306 |
| AEBP1 | 1.000305 |
| ABHD14B | 1.000305 |
| ACRBP | 1.000305 |
| ABCG2 | 1.000305 |
| AKR1C3 | 1.000305 |
| ADAMTS18 | 1.000305 |
| ACER2 | 1.000305 |
| ADAM19 | 1.000305 |
| ADAMTS17 | 1.000305 |
| ADI1 | 1.000305 |
| AGAP1 | 1.000305 |
| AKIRIN2 | 1.000305 |
| ABCB4 | 1.000305 |
| ADAM8 | 1.000305 |
| ADCY8 | 1.000305 |
| ACOT11 | 1.000304 |
| ACYP2 | 1.000304 |
| ADAR | 1.000304 |
| ADCK1 | 1.000304 |
| ADORA2B | 1.000304 |
| AKAP14 | 1.000304 |
| ADAMTS20 | 1.000304 |
| AGGF1 | 1.000304 |
| AKNAD1 | 1.000304 |
| ADCY1 | 1.000304 |
| ADCY7 | 1.000304 |
| ABCB1 | 1.000304 |
| AAAS | 1.000304 |
| ACACB | 1.000304 |
| ACBD3 | 1.000304 |
| ACSL3 | 1.000304 |
| ACSS1 | 1.000304 |
| ADAM17 | 1.000304 |
| ADAM22 | 1.000304 |
| AGFG2 | 1.000304 |
| AGPAT5 | 1.000304 |
| AHCYL2 | 1.000304 |
| AK5 | 1.000304 |
| AKAP11 | 1.000304 |
| ADAM21 | 1.000304 |
| ACTBL2 | 1.000303 |
| ADAMTS19 | 1.000303 |
| ACVR1C | 1.000303 |
| ABCA5 | 1.000303 |
| ACADS | 1.000303 |
| ADAMTS2 | 1.000303 |
| ADAMTS3 | 1.000303 |
| ACACA | 1.000303 |
| ACAD11 | 1.000303 |
| ADIPOR2 | 1.000303 |
| AGPAT4 | 1.000303 |
| AHCTF1 | 1.000303 |
| AHCY | 1.000303 |
| AHR | 1.000303 |
| ACAN | 1.000303 |
| AGBL2 | 1.000303 |
| AFF2 | 1.000303 |
| ADAMTS12 | 1.000303 |
| ABCC4 | 1.000302 |
| ABHD6 | 1.000302 |
| ACOXL | 1.000302 |
| ACSF2 | 1.000302 |
| ACSL5 | 1.000302 |
| ACSL6 | 1.000302 |
| ACVR1 | 1.000302 |
| ADARB2 | 1.000302 |
| ADPGK | 1.000302 |
| AGPS | 1.000302 |
| AIFM2 | 1.000302 |
| AJAP1 | 1.000302 |
| AK3 | 1.000302 |
| AKAP1 | 1.000302 |
| AGXT2 | 1.000302 |
| ADAM2 | 1.000302 |
| ADAMTS4 | 1.000302 |
| AATF | 1.000302 |
| ABCB9 | 1.000302 |
| ABCD4 | 1.000302 |
| ACAP2 | 1.000302 |
| ACSL1 | 1.000302 |
| ACVR1B | 1.000302 |
| ADCY2 | 1.000302 |
| ADO | 1.000302 |
| AGBL5 | 1.000302 |
| AKAP7 | 1.000302 |
| ADAMTSL3 | 1.000301 |
| AGRN | 1.000301 |
| ABCC5 | 1.000301 |
| ACVR2A | 1.000301 |
| ADAM23 | 1.000301 |
| ADARB1 | 1.000301 |
| ADCY5 | 1.000301 |
| AGTPBP1 | 1.000301 |
| AGTRAP | 1.000301 |
| AKAP12 | 1.000301 |
| AKAP9 | 1.000301 |
| ADAD2 | 1.000301 |
| ABLIM3 | 1.000301 |
| ACBD6 | 1.000301 |
| ACP6 | 1.000301 |
| ACTN4 | 1.000301 |
| ACTR1A | 1.000301 |
| ACTR2 | 1.000301 |
| ADAM10 | 1.000301 |
| ADCY9 | 1.000301 |
| ADD1 | 1.000301 |
| AHI1 | 1.000301 |
| AKAP6 | 1.000301 |
| ABCA8 | 1.000300 |
| ABCC3 | 1.000300 |
| AKNA | 1.000300 |
| ABCA4 | 1.000300 |
| ACTB | 1.000300 |
| ACTG1 | 1.000300 |
| ADM | 1.000300 |
| ADORA3 | 1.000300 |
| AGPAT3 | 1.000300 |
| AIG1 | 1.000300 |
| AKIRIN1 | 1.000300 |
| ADORA1 | 1.000299 |
| ABCC1 | 1.000299 |
| ABCD3 | 1.000299 |
| ABL1 | 1.000299 |
| ABL2 | 1.000299 |
| ACTN1 | 1.000299 |
| ADRB1 | 1.000299 |
| AADACL2 | 1.000299 |
| AKR1C2 | 1.000299 |
| AAK1 | 1.000299 |
| ADAMTS1 | 1.000299 |
| ACBD5 | 1.000299 |
| ADAM12 | 1.000299 |
| ADAMTS14 | 1.000299 |
| ADNP | 1.000299 |
| AKAP13 | 1.000299 |
| ADH6 | 1.000298 |
| ABCG1 | 1.000298 |
| ABHD2 | 1.000298 |
| ABI1 | 1.000298 |
| ABR | 1.000298 |
| ACO1 | 1.000298 |
| AEBP2 | 1.000298 |
| AFAP1 | 1.000298 |
| AK2 | 1.000298 |
| ACKR3 | 1.000298 |
| ACKR4 | 1.000298 |
| ABCD2 | 1.000298 |
| ADAMTS16 | 1.000298 |
| ACOT7 | 1.000297 |
| AHCYL1 | 1.000297 |
| AHDC1 | 1.000297 |
| ADAM30 | 1.000297 |
| ACTR3 | 1.000297 |
| ADK | 1.000297 |
| AFF1 | 1.000297 |
| AFTPH | 1.000297 |
| ABTB2 | 1.000296 |
| ADD3 | 1.000296 |
| ABCA1 | 1.000296 |
| ABHD16B | 1.000296 |
| ADPRM | 1.000296 |
| AIFM3 | 1.000295 |
| ABLIM1 | 1.000295 |
| A1BG | 1.000295 |
| ACCSL | 1.000295 |
| AHSP | 1.000294 |
| ACAA1 | 1.000289 |
| ADGB | 1.000289 |
| ABCC9 | 1.000288 |
| AICDA | 1.000286 |
| AKR1C4 | 1.000286 |
| ADAM33 | 1.000284 |
| ADTRP | 1.000284 |
| ACOT12 | 1.000282 |
| ACMSD | 1.000280 |
| AGAP4 | 1.000279 |
| AGBL4 | 1.000277 |
| AKR1B15 | 1.000277 |
| ABCA10 | 1.000277 |
| ABRACL | 1.000274 |
| ADRB2 | 1.000273 |
| ACSS3 | 1.000272 |
| A1CF | 1.000271 |
| ACTL10 | 1.000261 |
| AJUBA | 1.000237 |
| AKAP4 | 1.000220 |
| AGAP9 | 1.000218 |
| ADAM20 | 1.000199 |

## 6. Modules Used For Matrix Projection

### Module 1: module_1
- weight: `1.2`
- genes: `ESR1, GATA3, CCND1, CDCA8, AURKB, ANLN`
- reason: Luminal and proliferation axis separating cluster 0 from cluster 4. | module_discriminative_filtered genes=6 cutoff=1.0272

### Module 2: module_2
- weight: `1.1`
- genes: `BLOC1S1, COX4I1, EDF1, GADD45GIP1, ABCA9, PLSCR4`
- reason: Metabolic and mitochondrial axis separating cluster 2 from others. | module_discriminative_filtered genes=6 cutoff=1.0272

### Module 3: reg_module_HSA-MIR-503
- weight: `1.1`
- genes: `ANLN, ARL2, CCND1, DIXDC1, E2F3`
- reason: targets of regulator HSA-MIR-503 supported by retrieved evidence | module_discriminative_filtered genes=5 cutoff=1.0272

### Module 4: reg_module_HSA-MIR-429
- weight: `1.1`
- genes: `AFF3, AHNAK, ANLN, AP1AR`
- reason: targets of regulator HSA-MIR-429 supported by retrieved evidence | module_discriminative_filtered genes=4 cutoff=1.0272

## 7. Prototypes Used For Matrix Projection

### Prototype 1: prototype_1
- genes_up: `ESR1, GATA3, CCND1, AURKB, PSAT1`
- genes_down: `BLOC1S1, COX4I1, ARSB`

### Prototype score statistics
| prototype | mean | std | min | max |
|---|---:|---:|---:|---:|
| prototype_1 | 0.000180 | 0.999449 | -3.000000 | 2.725492 |

## 8. Stage-by-stage Matrix Change Summary

| stage | changed_fraction | mean_abs_diff | max_abs_diff |
|---|---:|---:|---:|
| global_gene_weights | 0.00742279 | 0.00008966 | 2.06296945 |
| module_priors | 0.00093439 | 0.00005349 | 0.49265146 |
| prototype_priors | 0.00000000 | 0.00000000 | 0.00000000 |
| sample_specific_priors | 0.00000000 | 0.00000000 | 0.00000000 |
| clean_numeric_df | 0.00000000 | 0.00000000 | 0.00000000 |

## 9. Top Changed Genes By Stage

### global_gene_weights
| gene | mean_abs_diff | max_abs_diff | changed_samples |
|---|---:|---:|---:|
| AURKB | 0.18413524 | 1.35893726 | 671 |
| COX4I1 | 0.14738399 | 2.06296945 | 671 |
| ESR1 | 0.12236243 | 0.62143517 | 671 |
| GATA3 | 0.08854018 | 1.05538511 | 671 |
| AHNAK | 0.08853605 | 1.13004065 | 671 |
| CCND1 | 0.06353581 | 0.67937827 | 671 |
| E2F3 | 0.04147152 | 0.54664636 | 671 |
| ARSB | 0.04001305 | 0.51676273 | 671 |
| NDC80 | 0.03710636 | 0.36555219 | 671 |
| FAU | 0.03708437 | 0.54249144 | 671 |
| ABCA3 | 0.03708095 | 0.36894011 | 671 |
| ARL2 | 0.03707371 | 0.58909535 | 671 |
| PCSK5 | 0.03707245 | 0.41392994 | 671 |
| FKBP4 | 0.03706989 | 0.34869337 | 671 |
| ANLN | 0.03706741 | 0.34019375 | 671 |
| COG7 | 0.03267131 | 0.25274944 | 671 |
| COMMD2 | 0.03265993 | 0.69242477 | 671 |
| CLCN6 | 0.03265926 | 0.34946609 | 671 |
| CHST3 | 0.03265427 | 0.41693473 | 671 |
| TGFBR2 | 0.03265245 | 0.47358942 | 671 |
| SP1 | 0.03265245 | 0.40092683 | 671 |
| DIXDC1 | 0.02530063 | 0.20568180 | 671 |
| ELOB | 0.02238328 | 0.29944539 | 671 |
| FOXM1 | 0.02092382 | 0.19178677 | 671 |
| AP1AR | 0.02091650 | 0.18293977 | 671 |
| RAD17 | 0.02091223 | 0.22973871 | 671 |
| SNRPD2 | 0.02091208 | 0.38148737 | 671 |
| DRAP1 | 0.02091164 | 0.20949912 | 671 |
| PSMB6 | 0.02091109 | 0.27370429 | 671 |
| CDCA8 | 0.02090757 | 0.19652915 | 671 |

### module_priors
| gene | mean_abs_diff | max_abs_diff | changed_samples |
|---|---:|---:|---:|
| ANLN | 0.12246674 | 0.49265146 | 671 |
| CCND1 | 0.08255135 | 0.35264111 | 671 |
| AFF3 | 0.06073315 | 0.21775496 | 671 |
| AP1AR | 0.06073314 | 0.21775508 | 671 |
| AHNAK | 0.06073314 | 0.21775496 | 671 |
| GATA3 | 0.05390909 | 0.27080631 | 671 |
| CDCA8 | 0.05390909 | 0.27080631 | 671 |
| ESR1 | 0.05390909 | 0.27080631 | 671 |
| AURKB | 0.05390909 | 0.27080619 | 671 |
| ABCA9 | 0.05191876 | 0.21197283 | 671 |
| BLOC1S1 | 0.05191876 | 0.21197295 | 671 |
| PLSCR4 | 0.05191875 | 0.21197283 | 671 |
| COX4I1 | 0.05191875 | 0.21197295 | 671 |
| GADD45GIP1 | 0.05191875 | 0.21197295 | 671 |
| EDF1 | 0.05191875 | 0.21197295 | 671 |
| E2F3 | 0.03869775 | 0.17832398 | 671 |
| ARL2 | 0.03869775 | 0.17832398 | 671 |
| DIXDC1 | 0.03869775 | 0.17832392 | 671 |

### prototype_priors
- No changed genes detected.

### sample_specific_priors
- No changed genes detected.

### clean_numeric_df
- No changed genes detected.

## 10. Final Guided Expression Check

- changed_fraction: `0.00763043`
- mean_abs_diff: `0.00012725`
- max_abs_diff: `1.87942338`
- output_nonzero_fraction: `0.21485673`
