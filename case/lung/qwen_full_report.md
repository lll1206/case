# Qwen Full Report

## 0. Dataset / Run Summary

- dataset_name: `Vieira Braga lung scRNA`
- raw_shape: `(10360, 16327)`
- selected_sources: `{'ChEA': 3, 'GTEx': 2, 'MSigDB': 5, 'PanglaoDB': 6}`
- llm_selected_sources: `{'ChEA': 3, 'GTEx': 1, 'MSigDB': 2, 'PanglaoDB': 3}`
- qwen_model_name: `qwen3.5:9b`

## Cluster-wise Candidate Marker Genes

### cluster_module_0 | size=205
- SCGB1A1
- SCGB3A1
- SCGB3A2
- WFDC2
- CP
- BPIFB1
- SLPI
- TMC5
- AGR2
- CXCL17

### cluster_module_2 | size=322
- FTL
- TMSB4X
- HLA-DRA
- TMSB10
- B2M
- HLA-DRB1
- IFI30
- CD74
- TYROBP
- MARCO

### cluster_module_3 | size=221
- SFTPB
- SFTPA2
- SFTPA1
- SFTPC
- NAPSA
- SFTPD
- MUC1
- CTSH
- SLPI
- SFTA2

### cluster_module_4 | size=559
- SFTPC
- SFTPA1
- SFTPA2
- SFTPB
- NAPSA
- SLC34A2
- SFTPD
- CTSH
- MUC1
- DHCR24

### cluster_module_5 | size=23
- RPLP1
- RPS6
- RPS14
- MT-RNR2
- RPL13
- MT-CO1
- RPS18
- RPL31
- RPL37A
- RPS8

### cluster_module_6 | size=1800
- SAMSN1
- SRGN
- MT-RNR2
- IFITM2
- SLC2A3
- RGS2
- MT-ND2
- S100A8
- CPA3
- CCL5

### cluster_module_7 | size=1041
- SFTPC
- SFTPA2
- SFTPB
- SFTPA1
- NAPSA
- SFTPD
- SLC34A2
- MUC1
- LAMP3
- CTSH

### cluster_module_8 | size=123
- TMSB4X
- FTL
- B2M
- HLA-DRA
- CD74
- TMSB10
- FTH1
- HLA-DRB1
- TYROBP
- IFI30

### cluster_module_9 | size=120
- MT-RNR2
- B2M
- TMSB4X
- CD74
- TMSB10
- FTH1
- RPS14
- MT-CO1
- ACTB
- RPS29

### cluster_module_10 | size=570
- FTL
- HLA-DRA
- MARCO
- C1QA
- IFI30
- APOC1
- TMSB10
- PSAP
- C1QB
- HLA-DRB1

### cluster_module_11 | size=598
- MT-RNR2
- RPL34
- RPS29
- RPS6
- RPS27A
- MT-CO1
- RPL26
- MT-ND4
- RPL32
- RPS14

### cluster_module_12 | size=98
- MT-RNR2
- MT-CO3
- MT-CO1
- RPL31
- RPL35A
- RPS7
- RPS8
- MT-CO2
- MT-ND4
- RPL10A

## Candidate Genes

- SCGB1A1
- SCGB3A1
- SCGB3A2
- WFDC2
- CP
- BPIFB1
- SLPI
- TMC5
- AGR2
- CXCL17
- FTL
- TMSB4X
- HLA-DRA
- TMSB10
- B2M
- HLA-DRB1
- IFI30
- CD74
- TYROBP
- MARCO
- SFTPB
- SFTPA2
- SFTPA1
- SFTPC
- NAPSA
- SFTPD
- MUC1
- CTSH
- SFTA2
- SLC34A2
- DHCR24
- RPLP1
- RPS6
- RPS14
- MT-RNR2
- RPL13
- MT-CO1
- RPS18
- RPL31
- RPL37A
- RPS8
- SAMSN1
- SRGN
- IFITM2
- SLC2A3
- RGS2
- MT-ND2
- S100A8
- CPA3
- CCL5
- LAMP3
- FTH1
- ACTB
- RPS29
- C1QA
- APOC1
- PSAP
- C1QB
- RPL34
- RPS27A
- RPL26
- MT-ND4
- RPL32
- MT-CO3
- RPL35A
- RPS7
- MT-CO2
- RPL10A


## Retrieved Knowledge Chunks

### Chunk 1
- source: ChEA
- type: tf_target_set
- title: ChEA term SPI1 23547873 ChIP-Seq NB4 Human
- genes: B2M, C1QA, C1QB, DHCR24, FTL, IFITM2, PSAP, RGS2, RPL13, RPL26, RPL37A, RPS18, RPS27A, RPS6, S100A8, SAMSN1, TMSB10, TYROBP

#### text

```
ChEA tf_target_set ChEA term SPI1 23547873 ChIP-Seq NB4 Human 候选基因交集：B2M, C1QA, C1QB, DHCR24, FTL, IFITM2, PSAP, RGS2, RPL13, RPL26, RPL37A, RPS18, RPS27A, RPS6, S100A8, SAMSN1, TM
```


### Chunk 2
- source: ChEA
- type: tf_target_set
- title: ChEA term GATA3 27048872 Chip-Seq THYMUS Human
- genes: B2M, CCL5, CTSH, CXCL17, DHCR24, FTH1, LAMP3, PSAP, RGS2, RPLP1, SAMSN1, SFTPA2, SRGN, TMSB4X

#### text

```
ChEA tf_target_set ChEA term GATA3 27048872 Chip-Seq THYMUS Human 候选基因交集：B2M, CCL5, CTSH, CXCL17, DHCR24, FTH1, LAMP3, PSAP, RGS2, RPLP1, SAMSN1, SFTPA2, SRGN, TMSB4X
```


### Chunk 3
- source: ChEA
- type: tf_target_set
- title: ChEA term OCT4 19829295 ChIP-Seq ESCs Human
- genes: APOC1, CD74, LAMP3, RPL37A, S100A8, SCGB1A1, SCGB3A1, SCGB3A2, SFTPB, SLC2A3, SLC34A2, SRGN

#### text

```
ChEA tf_target_set ChEA term OCT4 19829295 ChIP-Seq ESCs Human 候选基因交集：APOC1, CD74, LAMP3, RPL37A, S100A8, SCGB1A1, SCGB3A1, SCGB3A2, SFTPB, SLC2A3, SLC34A2, SRGN
```


### Chunk 4
- source: GTEx
- type: tissue_expression
- title: GTEx tissue Lung
- genes: ACTB, B2M, CD74, FTL, HLA-DRA, IFI30, MT-CO1, MT-CO2, MT-CO3, MT-ND2, MT-ND4, MT-RNR2, PSAP, RPL10A, RPLP1, RPS18, RPS27A, RPS6, RPS7, RPS8, S100A8, SCGB1A1, SFTPA1, SFTPA2, SFTPB, SFTPC, SLPI, TMSB10, TMSB4X

#### text

```
GTEx tissue_expression GTEx tissue Lung 候选基因交集：ACTB, B2M, CD74, FTL, HLA-DRA, IFI30, MT-CO1, MT-CO2, MT-CO3, MT-ND2, MT-ND4, MT-RNR2, PSAP, RPL10A, RPLP1, RPS18, RPS27A, RPS6, RPS7
```


### Chunk 5
- source: GTEx
- type: tissue_expression
- title: GTEx tissue Whole Blood
- genes: ACTB, B2M, CD74, FTL, HLA-DRA, IFI30, IFITM2, MT-CO1, MT-CO2, MT-CO3, MT-ND2, MT-ND4, MT-RNR2, PSAP, RPLP1, RPS18, S100A8, SLC2A3, SRGN, TMSB10, TMSB4X, TYROBP

#### text

```
GTEx tissue_expression GTEx tissue Whole Blood 候选基因交集：ACTB, B2M, CD74, FTL, HLA-DRA, IFI30, IFITM2, MT-CO1, MT-CO2, MT-CO3, MT-ND2, MT-ND4, MT-RNR2, PSAP, RPLP1, RPS18, S100A8, SLC2A3, SRGN, TMSB10, TMSB4X, TYROBP
```


### Chunk 6
- source: MSigDB
- type: gene_set
- title: MSigDB gene set MURARO_PANCREAS_DUCTAL_CELL
- genes: ACTB, AGR2, B2M, C1QA, C1QB, CD74, CPA3, CTSH, DHCR24, FTH1, HLA-DRA, HLA-DRB1, IFI30, IFITM2, MUC1, PSAP, SLC34A2, SLPI, SRGN, TMC5, TMSB10, TMSB4X, TYROBP, WFDC2

#### text

```
MSigDB gene_set MSigDB gene set MURARO_PANCREAS_DUCTAL_CELL 候选基因交集：ACTB, AGR2, B2M, C1QA, C1QB, CD74, CPA3, CTSH, DHCR24, FTH1, HLA-DRA, HLA-DRB1, IFI30, IFITM2, MUC1, PSAP, SLC34A
```


### Chunk 7
- source: MSigDB
- type: gene_set
- title: MSigDB gene set RUBENSTEIN_SKELETAL_MUSCLE_MYELOID_CELLS
- genes: ACTB, CD74, CTSH, FTH1, FTL, HLA-DRA, HLA-DRB1, IFI30, MT-CO1, PSAP, RGS2, RPL26, RPL32, RPL34, RPLP1, RPS14, RPS29, RPS7, S100A8, SRGN, TMSB10, TMSB4X, TYROBP

#### text

```
MSigDB gene_set MSigDB gene set RUBENSTEIN_SKELETAL_MUSCLE_MYELOID_CELLS 候选基因交集：ACTB, CD74, CTSH, FTH1, FTL, HLA-DRA, HLA-DRB1, IFI30, MT-CO1, PSAP, RGS2, RPL26, RPL32, RPL34, RPLP
```


### Chunk 8
- source: MSigDB
- type: gene_set
- title: MSigDB gene set FAN_OVARY_CL13_MONOCYTE_MACROPHAGE
- genes: ACTB, B2M, C1QA, CD74, CTSH, FTH1, FTL, HLA-DRA, HLA-DRB1, IFI30, MT-CO1, MT-CO2, PSAP, RGS2, SAMSN1, SRGN, TMSB4X, TYROBP

#### text

```
MSigDB gene_set MSigDB gene set FAN_OVARY_CL13_MONOCYTE_MACROPHAGE 候选基因交集：ACTB, B2M, C1QA, CD74, CTSH, FTH1, FTL, HLA-DRA, HLA-DRB1, IFI30, MT-CO1, MT-CO2, PSAP, RGS2, SAMSN1, SRGN, TMSB4X, TYROBP
```


### Chunk 9
- source: MSigDB
- type: gene_set
- title: MSigDB gene set REACTOME_INNATE_IMMUNE_SYSTEM
- genes: ACTB, B2M, BPIFB1, C1QA, C1QB, CTSH, FTH1, FTL, MUC1, PSAP, RPS27A, S100A8, SFTPA1, SFTPA2, SFTPD, SLC2A3, SLPI, TYROBP

#### text

```
MSigDB gene_set MSigDB gene set REACTOME_INNATE_IMMUNE_SYSTEM 候选基因交集：ACTB, B2M, BPIFB1, C1QA, C1QB, CTSH, FTH1, FTL, MUC1, PSAP, RPS27A, S100A8, SFTPA1, SFTPA2, SFTPD, SLC2A3, SLPI, TYROBP
```


### Chunk 10
- source: MSigDB
- type: gene_set
- title: MSigDB gene set TRAVAGLINI_LUNG_MESOTHELIAL_CELL
- genes: APOC1, B2M, C1QA, C1QB, CD74, DHCR24, HLA-DRA, HLA-DRB1, IFI30, MARCO, RPL10A, RPL13, RPL26, RPL31, RPL32, RPL34, RPL35A, RPL37A, RPLP1, RPS14, RPS18, RPS27A, RPS29, RPS6, RPS8, SLPI, TMSB10, TMSB4X, TYROBP, WFDC2

#### text

```
MSigDB gene_set MSigDB gene set TRAVAGLINI_LUNG_MESOTHELIAL_CELL 候选基因交集：APOC1, B2M, C1QA, C1QB, CD74, DHCR24, HLA-DRA, HLA-DRB1, IFI30, MARCO, RPL10A, RPL13, RPL26, RPL31, RPL32, RPL34, RPL35A, RPL37A, RPLP1, RPS14, RPS18, RPS27A, RPS29, RPS6, RPS8, SLPI, TMSB10, TMSB4X, TYROBP, WFDC2
```


### Chunk 11
- source: PanglaoDB
- type: cell_type_marker
- title: PanglaoDB markers for Pulmonary alveolar type II cells
- genes: LAMP3, MUC1, NAPSA, SFTA2, SFTPA1, SFTPB, SFTPC, SFTPD, SLC34A2

#### text

```
PanglaoDB cell_type_marker PanglaoDB markers for Pulmonary alveolar type II cells 候选基因交集：LAMP3, MUC1, NAPSA, SFTA2, SFTPA1, SFTPB, SFTPC, SFTPD, SLC34A2
```


### Chunk 12
- source: PanglaoDB
- type: cell_type_marker
- title: PanglaoDB markers for Clara cells
- genes: MUC1, SCGB1A1, SCGB3A1, SCGB3A2, SFTPA1, SFTPC, SFTPD

#### text

```
PanglaoDB cell_type_marker PanglaoDB markers for Clara cells 候选基因交集：MUC1, SCGB1A1, SCGB3A1, SCGB3A2, SFTPA1, SFTPC, SFTPD
```


### Chunk 13
- source: PanglaoDB
- type: cell_type_marker
- title: PanglaoDB markers for Dendritic cells
- genes: FTL, HLA-DRA, HLA-DRB1, LAMP3, NAPSA, S100A8

#### text

```
PanglaoDB cell_type_marker PanglaoDB markers for Dendritic cells 候选基因交集：FTL, HLA-DRA, HLA-DRB1, LAMP3, NAPSA, S100A8
```


### Chunk 14
- source: PanglaoDB
- type: cell_type_marker
- title: PanglaoDB markers for Monocytes
- genes: HLA-DRA, IFI30, PSAP, RGS2, S100A8

#### text

```
PanglaoDB cell_type_marker PanglaoDB markers for Monocytes 候选基因交集：HLA-DRA, IFI30, PSAP, RGS2, S100A8
```


### Chunk 15
- source: PanglaoDB
- type: cell_type_marker
- title: PanglaoDB markers for Luminal epithelial cells
- genes: AGR2, CD74, MUC1, SLPI, WFDC2

#### text

```
PanglaoDB cell_type_marker PanglaoDB markers for Luminal epithelial cells 候选基因交集：AGR2, CD74, MUC1, SLPI, WFDC2
```


### Chunk 16
- source: PanglaoDB
- type: cell_type_marker
- title: PanglaoDB markers for Macrophages
- genes: CCL5, CD74, S100A8, SAMSN1

#### text

```
PanglaoDB cell_type_marker PanglaoDB markers for Macrophages 候选基因交集：CCL5, CD74, S100A8, SAMSN1
```


## LLM Selected Chunks

### LLM Chunk 1
- source: ChEA
- type: tf_target_set
- title: ChEA term SPI1 23547873 ChIP-Seq NB4 Human
- genes: B2M, C1QA, C1QB, DHCR24, FTL, IFITM2, PSAP, RGS2, RPL13, RPL26, RPL37A, RPS18, RPS27A, RPS6, S100A8, SAMSN1, TMSB10, TYROBP

#### text

```
ChEA tf_target_set ChEA term SPI1 23547873 ChIP-Seq NB4 Human 候选基因交集：B2M, C1QA, C1QB, DHCR24, FTL, IFITM2, PSAP, RGS2, RPL13, RPL26, RPL37A, RPS18, RPS27A, RPS6, S100A8, SAMSN1, TM
```


### LLM Chunk 2
- source: ChEA
- type: tf_target_set
- title: ChEA term GATA3 27048872 Chip-Seq THYMUS Human
- genes: B2M, CCL5, CTSH, CXCL17, DHCR24, FTH1, LAMP3, PSAP, RGS2, RPLP1, SAMSN1, SFTPA2, SRGN, TMSB4X

#### text

```
ChEA tf_target_set ChEA term GATA3 27048872 Chip-Seq THYMUS Human 候选基因交集：B2M, CCL5, CTSH, CXCL17, DHCR24, FTH1, LAMP3, PSAP, RGS2, RPLP1, SAMSN1, SFTPA2, SRGN, TMSB4X
```


### LLM Chunk 3
- source: ChEA
- type: tf_target_set
- title: ChEA term OCT4 19829295 ChIP-Seq ESCs Human
- genes: APOC1, CD74, LAMP3, RPL37A, S100A8, SCGB1A1, SCGB3A1, SCGB3A2, SFTPB, SLC2A3, SLC34A2, SRGN

#### text

```
ChEA tf_target_set ChEA term OCT4 19829295 ChIP-Seq ESCs Human 候选基因交集：APOC1, CD74, LAMP3, RPL37A, S100A8, SCGB1A1, SCGB3A1, SCGB3A2, SFTPB, SLC2A3, SLC34A2, SRGN
```


### LLM Chunk 4
- source: GTEx
- type: tissue_expression
- title: GTEx tissue Lung
- genes: ACTB, B2M, CD74, FTL, HLA-DRA, IFI30, MT-CO1, MT-CO2, MT-CO3, MT-ND2, MT-ND4, MT-RNR2, PSAP, RPL10A, RPLP1, RPS18, RPS27A, RPS6, RPS7, RPS8, S100A8, SCGB1A1, SFTPA1, SFTPA2, SFTPB, SFTPC, SLPI, TMSB10, TMSB4X

#### text

```
GTEx tissue_expression GTEx tissue Lung 候选基因交集：ACTB, B2M, CD74, FTL, HLA-DRA, IFI30, MT-CO1, MT-CO2, MT-CO3, MT-ND2, MT-ND4, MT-RNR2, PSAP, RPL10A, RPLP1, RPS18, RPS27A, RPS6, RPS7
```


### LLM Chunk 5
- source: MSigDB
- type: gene_set
- title: MSigDB gene set MURARO_PANCREAS_DUCTAL_CELL
- genes: ACTB, AGR2, B2M, C1QA, C1QB, CD74, CPA3, CTSH, DHCR24, FTH1, HLA-DRA, HLA-DRB1, IFI30, IFITM2, MUC1, PSAP, SLC34A2, SLPI, SRGN, TMC5, TMSB10, TMSB4X, TYROBP, WFDC2

#### text

```
MSigDB gene_set MSigDB gene set MURARO_PANCREAS_DUCTAL_CELL 候选基因交集：ACTB, AGR2, B2M, C1QA, C1QB, CD74, CPA3, CTSH, DHCR24, FTH1, HLA-DRA, HLA-DRB1, IFI30, IFITM2, MUC1, PSAP, SLC34A
```


### LLM Chunk 6
- source: MSigDB
- type: gene_set
- title: MSigDB gene set RUBENSTEIN_SKELETAL_MUSCLE_MYELOID_CELLS
- genes: ACTB, CD74, CTSH, FTH1, FTL, HLA-DRA, HLA-DRB1, IFI30, MT-CO1, PSAP, RGS2, RPL26, RPL32, RPL34, RPLP1, RPS14, RPS29, RPS7, S100A8, SRGN, TMSB10, TMSB4X, TYROBP

#### text

```
MSigDB gene_set MSigDB gene set RUBENSTEIN_SKELETAL_MUSCLE_MYELOID_CELLS 候选基因交集：ACTB, CD74, CTSH, FTH1, FTL, HLA-DRA, HLA-DRB1, IFI30, MT-CO1, PSAP, RGS2, RPL26, RPL32, RPL34, RPLP
```


### LLM Chunk 7
- source: PanglaoDB
- type: cell_type_marker
- title: PanglaoDB markers for Pulmonary alveolar type II cells
- genes: LAMP3, MUC1, NAPSA, SFTA2, SFTPA1, SFTPB, SFTPC, SFTPD, SLC34A2

#### text

```
PanglaoDB cell_type_marker PanglaoDB markers for Pulmonary alveolar type II cells 候选基因交集：LAMP3, MUC1, NAPSA, SFTA2, SFTPA1, SFTPB, SFTPC, SFTPD, SLC34A2
```


### LLM Chunk 8
- source: PanglaoDB
- type: cell_type_marker
- title: PanglaoDB markers for Clara cells
- genes: MUC1, SCGB1A1, SCGB3A1, SCGB3A2, SFTPA1, SFTPC, SFTPD

#### text

```
PanglaoDB cell_type_marker PanglaoDB markers for Clara cells 候选基因交集：MUC1, SCGB1A1, SCGB3A1, SCGB3A2, SFTPA1, SFTPC, SFTPD
```


### LLM Chunk 9
- source: PanglaoDB
- type: cell_type_marker
- title: PanglaoDB markers for Dendritic cells
- genes: FTL, HLA-DRA, HLA-DRB1, LAMP3, NAPSA, S100A8

#### text

```
PanglaoDB cell_type_marker PanglaoDB markers for Dendritic cells 候选基因交集：FTL, HLA-DRA, HLA-DRB1, LAMP3, NAPSA, S100A8
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
- disease_context=human lung single-cell transcriptome airway alveolar epithelial endothelial immune fibroblast cell type programs
- n_samples=10360
- n_genes=19264
- cluster_count=12
- candidate_gene_count=68
- high variance genes=['SFTPC', 'FTL', 'SFTPA1', 'SFTPA2', 'TMSB4X', 'MT-RNR2', 'SFTPB', 'B2M', 'FTH1', 'SCGB1A1', 'CD74', 'MT-CO1', 'HLA-DRA', 'TMSB10', 'SCGB3A2', 'S100A6', 'MT-CO3', 'HLA-DRB1', 'RPLP1', 'SCGB3A1']

CLUSTER_MARKER_BLOCKS:
- cluster_module_0 | size=205: ['SCGB1A1', 'SCGB3A1', 'SCGB3A2', 'WFDC2', 'CP', 'BPIFB1', 'SLPI', 'TMC5', 'AGR2', 'CXCL17']
- cluster_module_2 | size=322: ['FTL', 'TMSB4X', 'HLA-DRA', 'TMSB10', 'B2M', 'HLA-DRB1', 'IFI30', 'CD74', 'TYROBP', 'MARCO']
- cluster_module_3 | size=221: ['SFTPB', 'SFTPA2', 'SFTPA1', 'SFTPC', 'NAPSA', 'SFTPD', 'MUC1', 'CTSH', 'SLPI', 'SFTA2']
- cluster_module_4 | size=559: ['SFTPC', 'SFTPA1', 'SFTPA2', 'SFTPB', 'NAPSA', 'SLC34A2', 'SFTPD', 'CTSH', 'MUC1', 'DHCR24']
- cluster_module_5 | size=23: ['RPLP1', 'RPS6', 'RPS14', 'MT-RNR2', 'RPL13', 'MT-CO1', 'RPS18', 'RPL31', 'RPL37A', 'RPS8']
- cluster_module_6 | size=1800: ['SAMSN1', 'SRGN', 'MT-RNR2', 'IFITM2', 'SLC2A3', 'RGS2', 'MT-ND2', 'S100A8', 'CPA3', 'CCL5']
- cluster_module_7 | size=1041: ['SFTPC', 'SFTPA2', 'SFTPB', 'SFTPA1', 'NAPSA', 'SFTPD', 'SLC34A2', 'MUC1', 'LAMP3', 'CTSH']
- cluster_module_8 | size=123: ['TMSB4X', 'FTL', 'B2M', 'HLA-DRA', 'CD74', 'TMSB10', 'FTH1', 'HLA-DRB1', 'TYROBP', 'IFI30']
- cluster_module_9 | size=120: ['MT-RNR2', 'B2M', 'TMSB4X', 'CD74', 'TMSB10', 'FTH1', 'RPS14', 'MT-CO1', 'ACTB', 'RPS29']
- cluster_module_10 | size=570: ['FTL', 'HLA-DRA', 'MARCO', 'C1QA', 'IFI30', 'APOC1', 'TMSB10', 'PSAP', 'C1QB', 'HLA-DRB1']
- cluster_module_11 | size=598: ['MT-RNR2', 'RPL34', 'RPS29', 'RPS6', 'RPS27A', 'MT-CO1', 'RPL26', 'MT-ND4', 'RPL32', 'RPS14']
- cluster_module_12 | size=98: ['MT-RNR2', 'MT-CO3', 'MT-CO1', 'RPL31', 'RPL35A', 'RPS7', 'RPS8', 'MT-CO2', 'MT-ND4', 'RPL10A']

CANDIDATE_GENES:
['SCGB1A1', 'SCGB3A1', 'SCGB3A2', 'WFDC2', 'CP', 'BPIFB1', 'SLPI', 'TMC5', 'AGR2', 'CXCL17', 'FTL', 'TMSB4X', 'HLA-DRA', 'TMSB10', 'B2M', 'HLA-DRB1', 'IFI30', 'CD74', 'TYROBP', 'MARCO', 'SFTPB', 'SFTPA2', 'SFTPA1', 'SFTPC', 'NAPSA', 'SFTPD', 'MUC1', 'CTSH', 'SFTA2', 'SLC34A2', 'DHCR24', 'RPLP1', 'RPS6', 'RPS14', 'MT-RNR2', 'RPL13', 'MT-CO1', 'RPS18', 'RPL31', 'RPL37A', 'RPS8', 'SAMSN1', 'SRGN', 'IFITM2', 'SLC2A3', 'RGS2', 'MT-ND2', 'S100A8', 'CPA3', 'CCL5', 'LAMP3', 'FTH1', 'ACTB', 'RPS29', 'C1QA', 'APOC1', 'PSAP', 'C1QB', 'RPL34', 'RPS27A', 'RPL26', 'MT-ND4', 'RPL32', 'MT-CO3', 'RPL35A', 'RPS7', 'MT-CO2', 'RPL10A']

[EVIDENCE 1] source=ChEA type=tf_target_set title=ChEA term SPI1 23547873 ChIP-Seq NB4 Human
GENES=['B2M', 'C1QA', 'C1QB', 'DHCR24', 'FTL', 'IFITM2', 'PSAP', 'RGS2', 'RPL13', 'RPL26', 'RPL37A', 'RPS18']
ChEA tf_target_set ChEA term SPI1 23547873 ChIP-Seq NB4 Human 候选基因交集：B2M, C1QA, C1QB, DHCR24, FTL, IFITM2, PSAP, RGS2, RPL13, RPL26, RPL37A, RPS18, RPS27A, RPS6, S100A8, SAMSN1, TM

[EVIDENCE 2] source=ChEA type=tf_target_set title=ChEA term GATA3 27048872 Chip-Seq THYMUS Human
GENES=['B2M', 'CCL5', 'CTSH', 'CXCL17', 'DHCR24', 'FTH1', 'LAMP3', 'PSAP', 'RGS2', 'RPLP1', 'SAMSN1', 'SFTPA2']
ChEA tf_target_set ChEA term GATA3 27048872 Chip-Seq THYMUS Human 候选基因交集：B2M, CCL5, CTSH, CXCL17, DHCR24, FTH1, LAMP3, PSAP, RGS2, RPLP1, SAMSN1, SFTPA2, SRGN, TMSB4X

[EVIDENCE 3] source=ChEA type=tf_target_set title=ChEA term OCT4 19829295 ChIP-Seq ESCs Human
GENES=['APOC1', 'CD74', 'LAMP3', 'RPL37A', 'S100A8', 'SCGB1A1', 'SCGB3A1', 'SCGB3A2', 'SFTPB', 'SLC2A3', 'SLC34A2', 'SRGN']
ChEA tf_target_set ChEA term OCT4 19829295 ChIP-Seq ESCs Human 候选基因交集：APOC1, CD74, LAMP3, RPL37A, S100A8, SCGB1A1, SCGB3A1, SCGB3A2, SFTPB, SLC2A3, SLC34A2, SRGN

[EVIDENCE 4] source=GTEx type=tissue_expression title=GTEx tissue Lung
GENES=['ACTB', 'B2M', 'CD74', 'FTL', 'HLA-DRA', 'IFI30', 'MT-CO1', 'MT-CO2', 'MT-CO3', 'MT-ND2', 'MT-ND4', 'MT-RNR2']
GTEx tissue_expression GTEx tissue Lung 候选基因交集：ACTB, B2M, CD74, FTL, HLA-DRA, IFI30, MT-CO1, MT-CO2, MT-CO3, MT-ND2, MT-ND4, MT-RNR2, PSAP, RPL10A, RPLP1, RPS18, RPS27A, RPS6, RPS7

[EVIDENCE 5] source=MSigDB type=gene_set title=MSigDB gene set MURARO_PANCREAS_DUCTAL_CELL
GENES=['ACTB', 'AGR2', 'B2M', 'C1QA', 'C1QB', 'CD74', 'CPA3', 'CTSH', 'DHCR24', 'FTH1', 'HLA-DRA', 'HLA-DRB1']
MSigDB gene_set MSigDB gene set MURARO_PANCREAS_DUCTAL_CELL 候选基因交集：ACTB, AGR2, B2M, C1QA, C1QB, CD74, CPA3, CTSH, DHCR24, FTH1, HLA-DRA, HLA-DRB1, IFI30, IFITM2, MUC1, PSAP, SLC34A

[EVIDENCE 6] source=MSigDB type=gene_set title=MSigDB gene set RUBENSTEIN_SKELETAL_MUSCLE_MYELOID_CELLS
GENES=['ACTB', 'CD74', 'CTSH', 'FTH1', 'FTL', 'HLA-DRA', 'HLA-DRB1', 'IFI30', 'MT-CO1', 'PSAP', 'RGS2', 'RPL26']
MSigDB gene_set MSigDB gene set RUBENSTEIN_SKELETAL_MUSCLE_MYELOID_CELLS 候选基因交集：ACTB, CD74, CTSH, FTH1, FTL, HLA-DRA, HLA-DRB1, IFI30, MT-CO1, PSAP, RGS2, RPL26, RPL32, RPL34, RPLP

[EVIDENCE 7] source=PanglaoDB type=cell_type_marker title=PanglaoDB markers for Pulmonary alveolar type II cells
GENES=['LAMP3', 'MUC1', 'NAPSA', 'SFTA2', 'SFTPA1', 'SFTPB', 'SFTPC', 'SFTPD', 'SLC34A2']
PanglaoDB cell_type_marker PanglaoDB markers for Pulmonary alveolar type II cells 候选基因交集：LAMP3, MUC1, NAPSA, SFTA2, SFTPA1, SFTPB, SFTPC, SFTPD, SLC34A2

[EVIDENCE 8] source=PanglaoDB type=cell_type_marker title=PanglaoDB markers for Clara cells
GENES=['MUC1', 'SCGB1A1', 'SCGB3A1', 'SCGB3A2', 'SFTPA1', 'SFTPC', 'SFTPD']
PanglaoDB cell_type_marker PanglaoDB markers for Clara cells 候选基因交集：MUC1, SCGB1A1, SCGB3A1, SCGB3A2, SFTPA1, SFTPC, SFTPD

[EVIDENCE 9] source=PanglaoDB type=cell_type_marker title=PanglaoDB markers for Dendritic cells
GENES=['FTL', 'HLA-DRA', 'HLA-DRB1', 'LAMP3', 'NAPSA', 'S100A8']
PanglaoDB cell_type_marker PanglaoDB markers for Dendritic cells 候选基因交集：FTL, HLA-DRA, HLA-DRB1, LAMP3, NAPSA, S100A8

Return ONLY JSON. No markdown. No extra text.
```


## Qwen Raw Response

```
{
  "global_gene_weights": [
    {"gene": "SFTPC", "weight": 1.3, "reason": "Strong alveolar type II marker with high variance and cluster specificity."},
    {"gene": "SFTPA1", "weight": 1.25, "reason": "Core alveolar type II marker supported by multiple cell type databases."},
    {"gene": "SFTPB", "weight": 1.25, "reason": "Core alveolar type II marker with strong dataset support."},
    {"gene": "SCGB1A1", "weight": 1.2, "reason": "Specific Clara cell marker supported by PanglaoDB and cluster data."},
    {"gene": "SCGB3A1", "weight": 1.2, "reason": "Specific Clara cell marker with high cluster module presence."},
    {"gene": "SCGB3A2", "weight": 1.2, "reason": "Specific Clara cell marker supported by external evidence."},
    {"gene": "MUC1", "weight": 1.15, "reason": "Clara cell and airway epithelial marker with broad support."},
    {"gene": "LAMP3", "weight": 1.15, "reason": "Dendritic cell marker providing immune lineage separation."},
    {"gene": "FTL", "weight": 1.1, "reason": "Dendritic cell marker supported by ChEA and PanglaoDB."},
    {"gene": "HLA-DRA", "weight": 1.1, "reason": "Immune activation marker for dendritic cell separation."},
    {"gene": "SLC34A2", "weight": 1.05, "reason": "Alveolar type II marker supported by PanglaoDB and GTEx."},
    {"gene": "NAPSA", "weight": 1.05, "reason": "Alveolar type II marker with strong cluster module correlation."}
  ],
  "suppress_genes": [],
  "modules": [
    {
      "name": "alveolar_type_ii_program",
      "genes": ["SFTPC", "SFTPA1", "SFTPB", "SFTPA2", "SFTPD", "SLC34A2", "NAPSA", "MUC1"],
      "weight": 1.2,
      "reason": "Defines alveolar type II cell identity and separates from other lung lineages."
    },
    {
      "name": "clara_cell_program",
      "genes": ["SCGB1A1", "SCGB3A1", "SCGB3A2", "MUC1", "SFTPA1", "SFTPC"],
      "weight": 1.15,
      "reason": "Defines Clara cell identity and separates from alveolar and immune cells."
    }
  ],
  "prototypes": [
    {
      "name": "prototype_1",
      "genes_up": ["SFTPC", "SFTPA1", "SCGB1A1", "LAMP3"],
      "genes_down": ["RPLP1", "MT-RNR2"]
    }
  ],
  "key_gene_sets": ["alveolar_type_ii_markers", "clara_cell_markers", "dendritic_cell_markers"],
  "key_regulators": ["GATA3", "SPI1"],
  "notes": ["Prioritize alveolar type II and Clara cell markers for epithelial separation.", "Use immune markers like LAMP3 and FTL for dendritic cell separation.", "Avoid housekeeping genes like RPLP1 and MT-RNR2 unless necessary for normalization."]
}
```


## Parsed Prior JSON

```json
{
  "global_gene_weights": [
    {
      "gene": "SFTPC",
      "weight": 1.3,
      "reason": "Strong alveolar type II marker with high variance and cluster specificity."
    },
    {
      "gene": "SFTPA1",
      "weight": 1.25,
      "reason": "Core alveolar type II marker supported by multiple cell type databases."
    },
    {
      "gene": "SFTPB",
      "weight": 1.25,
      "reason": "Core alveolar type II marker with strong dataset support."
    },
    {
      "gene": "SCGB1A1",
      "weight": 1.2,
      "reason": "Specific Clara cell marker supported by PanglaoDB and cluster data."
    },
    {
      "gene": "SCGB3A1",
      "weight": 1.2,
      "reason": "Specific Clara cell marker with high cluster module presence."
    },
    {
      "gene": "SCGB3A2",
      "weight": 1.2,
      "reason": "Specific Clara cell marker supported by external evidence."
    },
    {
      "gene": "MUC1",
      "weight": 1.15,
      "reason": "Clara cell and airway epithelial marker with broad support."
    },
    {
      "gene": "LAMP3",
      "weight": 1.15,
      "reason": "Dendritic cell marker providing immune lineage separation."
    },
    {
      "gene": "FTL",
      "weight": 1.1,
      "reason": "Dendritic cell marker supported by ChEA and PanglaoDB."
    },
    {
      "gene": "HLA-DRA",
      "weight": 1.1,
      "reason": "Immune activation marker for dendritic cell separation."
    },
    {
      "gene": "SLC34A2",
      "weight": 1.05,
      "reason": "Alveolar type II marker supported by PanglaoDB and GTEx."
    },
    {
      "gene": "NAPSA",
      "weight": 1.05,
      "reason": "Alveolar type II marker with strong cluster module correlation."
    }
  ],
  "suppress_genes": [],
  "modules": [
    {
      "name": "alveolar_type_ii_program",
      "genes": [
        "SFTPC",
        "SFTPA1",
        "SFTPB",
        "SFTPA2",
        "SFTPD",
        "SLC34A2",
        "NAPSA",
        "MUC1"
      ],
      "weight": 1.2,
      "reason": "Defines alveolar type II cell identity and separates from other lung lineages."
    },
    {
      "name": "clara_cell_program",
      "genes": [
        "SCGB1A1",
        "SCGB3A1",
        "SCGB3A2",
        "MUC1",
        "SFTPA1",
        "SFTPC"
      ],
      "weight": 1.15,
      "reason": "Defines Clara cell identity and separates from alveolar and immune cells."
    }
  ],
  "prototypes": [
    {
      "name": "prototype_1",
      "genes_up": [
        "SFTPC",
        "SFTPA1",
        "SCGB1A1",
        "LAMP3"
      ],
      "genes_down": [
        "RPLP1",
        "MT-RNR2"
      ]
    }
  ],
  "key_gene_sets": [
    "alveolar_type_ii_markers",
    "clara_cell_markers",
    "dendritic_cell_markers"
  ],
  "key_regulators": [
    "GATA3",
    "SPI1"
  ],
  "notes": [
    "Prioritize alveolar type II and Clara cell markers for epithelial separation.",
    "Use immune markers like LAMP3 and FTL for dendritic cell separation.",
    "Avoid housekeeping genes like RPLP1 and MT-RNR2 unless necessary for normalization."
  ]
}
```

