# Qwen Full Report

## 0. Dataset / Run Summary

- dataset_name: `BRCA mRNA top`
- raw_shape: `(671, 5000)`
- selected_sources: `{'ChEA': 2, 'MSigDB': 4, 'PanglaoDB': 1, 'PubMed': 2, 'Reactome': 6, 'RegNetwork': 1}`
- llm_selected_sources: `{'ChEA': 2, 'MSigDB': 2, 'PanglaoDB': 1, 'PubMed': 2, 'Reactome': 3}`
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


## Retrieved Knowledge Chunks

### Chunk 1
- source: ChEA
- type: tf_target_set
- title: ChEA term CREM 20920259 ChIP-Seq GC1-SPG Mouse
- genes: ACTR3, AFF3, AMD1, AURKB, CAP1, CDC20, CHRNA1, COQ7, COX4I1, CPLX1, DRAP1, EDF1, FAU, HEXIM2, LCMT2, MICALL1, MOAP1, MRPL55, NDC80, PARD6B, PLA2G12A, PLXNC1, PSAT1, RNF181, RRP1B, SERF2, SHE, SRPK1, TTK

#### text

```
ChEA tf_target_set ChEA term CREM 20920259 ChIP-Seq GC1-SPG Mouse 候选基因交集：ACTR3, AFF3, AMD1, AURKB, CAP1, CDC20, CHRNA1, COQ7, COX4I1, CPLX1, DRAP1, EDF1, FAU, HEXIM2, LCMT2, MICALL
```


### Chunk 2
- source: ChEA
- type: tf_target_set
- title: ChEA term HNF4A 19822575 ChIP-Seq HepG2 Human
- genes: AASS, ABCA8, ABCA9, ACTR3, AFF3, ARSB, AURKB, CAP1, COG7, COQ7, CPLX1, DIXDC1, ESR1, FAM171A1, FREM1, GATAD1, GPC6, HEXIM2, MRPL52, PARD6B, PLSCR4, PLXNC1, PSAT1, RNF181, SERPINF1, SH3D19, SHE, SRPK1, TGFBR2, UTRN

#### text

```
ChEA tf_target_set ChEA term HNF4A 19822575 ChIP-Seq HepG2 Human 候选基因交集：AASS, ABCA8, ABCA9, ACTR3, AFF3, ARSB, AURKB, CAP1, COG7, COQ7, CPLX1, DIXDC1, ESR1, FAM171A1, FREM1, GATAD1
```


### Chunk 3
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_CELL_CYCLE
- genes: ACTR3, AURKB, CDC20, CDCA8, GATA3, GPNMB, HEXIM2, NAA10, NDC80, ORC1, PARD6B, RAD17, SRPK1, STARD9, TGFBR1, TTC28, TTK

#### text

```
MSigDB gene_set MSigDB gene set GOBP_CELL_CYCLE 候选基因交集：ACTR3, AURKB, CDC20, CDCA8, GATA3, GPNMB, HEXIM2, NAA10, NDC80, ORC1, PARD6B, RAD17, SRPK1, STARD9, TGFBR1, TTC28, TTK
```


### Chunk 4
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_CYTOSKELETON_ORGANIZATION
- genes: ACTR3, AURKB, CAP1, CDC20, CDCA8, DIXDC1, FAM171A1, MICALL1, NDC80, PARD6B, SH3D19, STARD9, TGFBR1, THY1, TTK

#### text

```
MSigDB gene_set MSigDB gene set GOBP_CYTOSKELETON_ORGANIZATION 候选基因交集：ACTR3, AURKB, CAP1, CDC20, CDCA8, DIXDC1, FAM171A1, MICALL1, NDC80, PARD6B, SH3D19, STARD9, TGFBR1, THY1, TTK
```


### Chunk 5
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_CELL_CYCLE_PROCESS
- genes: ACTR3, AURKB, CDC20, CDCA8, GPNMB, HEXIM2, NAA10, NDC80, ORC1, PARD6B, RAD17, SRPK1, STARD9, TTK

#### text

```
MSigDB gene_set MSigDB gene set GOBP_CELL_CYCLE_PROCESS 候选基因交集：ACTR3, AURKB, CDC20, CDCA8, GPNMB, HEXIM2, NAA10, NDC80, ORC1, PARD6B, RAD17, SRPK1, STARD9, TTK
```


### Chunk 6
- source: MSigDB
- type: gene_set
- title: MSigDB gene set MURARO_PANCREAS_MESENCHYMAL_STROMAL_CELL
- genes: ACTR3, CAP1, CTHRC1, FBN1, G6PD, GPC6, GPNMB, MMP1, PLSCR4, PSAT1, SERPINF1, SULF1, TGFBR1, THY1

#### text

```
MSigDB gene_set MSigDB gene set MURARO_PANCREAS_MESENCHYMAL_STROMAL_CELL 候选基因交集：ACTR3, CAP1, CTHRC1, FBN1, G6PD, GPC6, GPNMB, MMP1, PLSCR4, PSAT1, SERPINF1, SULF1, TGFBR1, THY1
```


### Chunk 7
- source: PanglaoDB
- type: cell_type_marker
- title: PanglaoDB markers for Fibroblasts
- genes: ADAM33, CTHRC1, FBN1

#### text

```
PanglaoDB cell_type_marker PanglaoDB markers for Fibroblasts 候选基因交集：ADAM33, CTHRC1, FBN1
```


### Chunk 8
- source: PubMed
- type: paper_abstract
- title: TRPS1: a highly sensitive and specific marker for breast carcinoma, especially for triple-negative breast cancer.
- genes: GATA3

#### text

```
PubMed paper_abstract TRPS1: a highly sensitive and specific marker for breast carcinoma, especially for triple-negative breast cancer. 候选基因交集：GATA3
```


### Chunk 9
- source: PubMed
- type: paper_abstract
- title: New generation breast cancer cell lines developed from patient-derived xenografts.
- genes: ESR1

#### text

```
PubMed paper_abstract New generation breast cancer cell lines developed from patient-derived xenografts. 候选基因交集：ESR1
```


### Chunk 10
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Signal Transduction
- genes: ACTR3, AURKB, CDC20, CDCA8, COL11A1, DRAP1, ESR1, FBN1, GATA3, GPNMB, NDC80, PARD6B, PCSK5, TGFBR1, TGFBR2

#### text

```
Reactome pathway_gene_set Reactome pathway Signal Transduction 候选基因交集：ACTR3, AURKB, CDC20, CDCA8, COL11A1, DRAP1, ESR1, FBN1, GATA3, GPNMB, NDC80, PARD6B, PCSK5, TGFBR1, TGFBR2
```


### Chunk 11
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Post-translational protein modification
- genes: ARSB, AURKB, CDC20, CDCA8, COG7, ELOB, ESR1, FBN1, GATA3, RNF181, TGFBR1, TGFBR2, THY1

#### text

```
Reactome pathway_gene_set Reactome pathway Post-translational protein modification 候选基因交集：ARSB, AURKB, CDC20, CDCA8, COG7, ELOB, ESR1, FBN1, GATA3, RNF181, TGFBR1, TGFBR2, THY1
```


### Chunk 12
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Developmental Biology
- genes: ACTR3, CAP1, COL11A1, DRAP1, ELOB, FAU, GATA3, PLXNC1, SRPK1, UTRN

#### text

```
Reactome pathway_gene_set Reactome pathway Developmental Biology 候选基因交集：ACTR3, CAP1, COL11A1, DRAP1, ELOB, FAU, GATA3, PLXNC1, SRPK1, UTRN
```


### Chunk 13
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Disease
- genes: ABCA3, ACTR3, ARSB, ELOB, ESR1, FAU, GPC6, RAD17, SRPK1, TGFBR1, TGFBR2

#### text

```
Reactome pathway_gene_set Reactome pathway Disease 候选基因交集：ABCA3, ACTR3, ARSB, ELOB, ESR1, FAU, GPC6, RAD17, SRPK1, TGFBR1, TGFBR2
```


### Chunk 14
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Metabolism of proteins
- genes: ABCA3, ARSB, AURKB, CDC20, CDCA8, COG7, COX4I1, ELOB, ESR1, FAU, FBN1, GADD45GIP1, GATA3, MMP1, MRPL52, MRPL55, RNF181, TGFBR1, TGFBR2, THY1

#### text

```
Reactome pathway_gene_set Reactome pathway Metabolism of proteins 候选基因交集：ABCA3, ARSB, AURKB, CDC20, CDCA8, COG7, COX4I1, ELOB, ESR1, FAU, FBN1, GADD45GIP1, GATA3, MMP1, MRPL52, MRPL55, RNF181, TGFBR1, TGFBR2, THY1
```


### Chunk 15
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Gene expression (Transcription)
- genes: AURKB, COX4I1, ELOB, ESR1, G6PD, GATA3, RAD17

#### text

```
Reactome pathway_gene_set Reactome pathway Gene expression (Transcription) 候选基因交集：AURKB, COX4I1, ELOB, ESR1, G6PD, GATA3, RAD17
```


### Chunk 16
- source: RegNetwork
- type: regulator_targets
- title: RegNetwork regulator TCF4
- genes: NECAB3, RUNX1T1, SULF1

#### text

```
RegNetwork regulator_targets RegNetwork regulator TCF4 候选基因交集：NECAB3, RUNX1T1, SULF1
```


## LLM Selected Chunks

### LLM Chunk 1
- source: ChEA
- type: tf_target_set
- title: ChEA term CREM 20920259 ChIP-Seq GC1-SPG Mouse
- genes: ACTR3, AFF3, AMD1, AURKB, CAP1, CDC20, CHRNA1, COQ7, COX4I1, CPLX1, DRAP1, EDF1, FAU, HEXIM2, LCMT2, MICALL1, MOAP1, MRPL55, NDC80, PARD6B, PLA2G12A, PLXNC1, PSAT1, RNF181, RRP1B, SERF2, SHE, SRPK1, TTK

#### text

```
ChEA tf_target_set ChEA term CREM 20920259 ChIP-Seq GC1-SPG Mouse 候选基因交集：ACTR3, AFF3, AMD1, AURKB, CAP1, CDC20, CHRNA1, COQ7, COX4I1, CPLX1, DRAP1, EDF1, FAU, HEXIM2, LCMT2, MICALL
```


### LLM Chunk 2
- source: ChEA
- type: tf_target_set
- title: ChEA term HNF4A 19822575 ChIP-Seq HepG2 Human
- genes: AASS, ABCA8, ABCA9, ACTR3, AFF3, ARSB, AURKB, CAP1, COG7, COQ7, CPLX1, DIXDC1, ESR1, FAM171A1, FREM1, GATAD1, GPC6, HEXIM2, MRPL52, PARD6B, PLSCR4, PLXNC1, PSAT1, RNF181, SERPINF1, SH3D19, SHE, SRPK1, TGFBR2, UTRN

#### text

```
ChEA tf_target_set ChEA term HNF4A 19822575 ChIP-Seq HepG2 Human 候选基因交集：AASS, ABCA8, ABCA9, ACTR3, AFF3, ARSB, AURKB, CAP1, COG7, COQ7, CPLX1, DIXDC1, ESR1, FAM171A1, FREM1, GATAD1
```


### LLM Chunk 3
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_CELL_CYCLE
- genes: ACTR3, AURKB, CDC20, CDCA8, GATA3, GPNMB, HEXIM2, NAA10, NDC80, ORC1, PARD6B, RAD17, SRPK1, STARD9, TGFBR1, TTC28, TTK

#### text

```
MSigDB gene_set MSigDB gene set GOBP_CELL_CYCLE 候选基因交集：ACTR3, AURKB, CDC20, CDCA8, GATA3, GPNMB, HEXIM2, NAA10, NDC80, ORC1, PARD6B, RAD17, SRPK1, STARD9, TGFBR1, TTC28, TTK
```


### LLM Chunk 4
- source: MSigDB
- type: gene_set
- title: MSigDB gene set GOBP_CYTOSKELETON_ORGANIZATION
- genes: ACTR3, AURKB, CAP1, CDC20, CDCA8, DIXDC1, FAM171A1, MICALL1, NDC80, PARD6B, SH3D19, STARD9, TGFBR1, THY1, TTK

#### text

```
MSigDB gene_set MSigDB gene set GOBP_CYTOSKELETON_ORGANIZATION 候选基因交集：ACTR3, AURKB, CAP1, CDC20, CDCA8, DIXDC1, FAM171A1, MICALL1, NDC80, PARD6B, SH3D19, STARD9, TGFBR1, THY1, TTK
```


### LLM Chunk 5
- source: PanglaoDB
- type: cell_type_marker
- title: PanglaoDB markers for Fibroblasts
- genes: ADAM33, CTHRC1, FBN1

#### text

```
PanglaoDB cell_type_marker PanglaoDB markers for Fibroblasts 候选基因交集：ADAM33, CTHRC1, FBN1
```


### LLM Chunk 6
- source: PubMed
- type: paper_abstract
- title: TRPS1: a highly sensitive and specific marker for breast carcinoma, especially for triple-negative breast cancer.
- genes: GATA3

#### text

```
PubMed paper_abstract TRPS1: a highly sensitive and specific marker for breast carcinoma, especially for triple-negative breast cancer. 候选基因交集：GATA3
```


### LLM Chunk 7
- source: PubMed
- type: paper_abstract
- title: New generation breast cancer cell lines developed from patient-derived xenografts.
- genes: ESR1

#### text

```
PubMed paper_abstract New generation breast cancer cell lines developed from patient-derived xenografts. 候选基因交集：ESR1
```


### LLM Chunk 8
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Signal Transduction
- genes: ACTR3, AURKB, CDC20, CDCA8, COL11A1, DRAP1, ESR1, FBN1, GATA3, GPNMB, NDC80, PARD6B, PCSK5, TGFBR1, TGFBR2

#### text

```
Reactome pathway_gene_set Reactome pathway Signal Transduction 候选基因交集：ACTR3, AURKB, CDC20, CDCA8, COL11A1, DRAP1, ESR1, FBN1, GATA3, GPNMB, NDC80, PARD6B, PCSK5, TGFBR1, TGFBR2
```


### LLM Chunk 9
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Post-translational protein modification
- genes: ARSB, AURKB, CDC20, CDCA8, COG7, ELOB, ESR1, FBN1, GATA3, RNF181, TGFBR1, TGFBR2, THY1

#### text

```
Reactome pathway_gene_set Reactome pathway Post-translational protein modification 候选基因交集：ARSB, AURKB, CDC20, CDCA8, COG7, ELOB, ESR1, FBN1, GATA3, RNF181, TGFBR1, TGFBR2, THY1
```


### LLM Chunk 10
- source: Reactome
- type: pathway_gene_set
- title: Reactome pathway Developmental Biology
- genes: ACTR3, CAP1, COL11A1, DRAP1, ELOB, FAU, GATA3, PLXNC1, SRPK1, UTRN

#### text

```
Reactome pathway_gene_set Reactome pathway Developmental Biology 候选基因交集：ACTR3, CAP1, COL11A1, DRAP1, ELOB, FAU, GATA3, PLXNC1, SRPK1, UTRN
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
- disease_context=breast cancer molecular subtype ER PR HER2 basal luminal
- n_samples=671
- n_genes=19264
- cluster_count=5
- candidate_gene_count=80
- high variance genes=['TMEM154', 'SLC22A14', 'CIB1', 'FBXL8', 'LRRC8E', 'TMEM165', 'IFFO2', 'TSPAN2', 'TMEM168', 'LRRD1', 'TMEM17', 'TMEM170A', 'PITPNC1', 'SLC20A2', 'RARB', 'CHST6', 'TMEM167B', 'LRRC58', 'FBXL18', 'PKD1L1']

CLUSTER_MARKER_BLOCKS:
- cluster_module_0 | size=186: ['ESR1', 'GATA3', 'NECAB3', 'PARD6B', 'MOAP1', 'ABCA3', 'LCMT2', 'CPLX1', 'TSPAN13', 'COG7', 'HEXIM2', 'PLA2G12A', 'AFF3', 'COQ7', 'GATAD1', 'RAD17']
- cluster_module_1 | size=140: ['ARSB', 'GPNMB', 'SULF1', 'THY1', 'CTHRC1', 'MMP1', 'COL11A1', 'PLXNC1', 'GPC6', 'TGFBR1', 'SERPINF1', 'G6PD', 'ACTR3', 'FBN1', 'CHRNA1', 'CAP1']
- cluster_module_2 | size=72: ['BLOC1S1', 'EDF1', 'ELOB', 'GADD45GIP1', 'ZNF593', 'PET100', 'COX4I1', 'FAU', 'RNF181', 'SERF2', 'MRPL55', 'NAA10', 'UBL5', 'MRPL52', 'DRAP1', 'CNPY2']
- cluster_module_3 | size=177: ['ABCA9', 'PLSCR4', 'ABCA8', 'AASS', 'STARD9', 'ADAM33', 'TGFBR2', 'SH3D19', 'TTC28', 'ABCA10', 'RUNX1T1', 'DIXDC1', 'SHE', 'FREM1', 'UTRN', 'PCSK5']
- cluster_module_4 | size=96: ['PSAT1', 'FAM171A1', 'CDC20', 'TTK', 'PPP1R14C', 'CDCA8', 'AURKB', 'PIMREG', 'ORC1', 'SRPK1', 'EN1', 'NDC80', 'AMD1', 'MICALL1', 'DEPDC1', 'RRP1B']

CANDIDATE_GENES:
['ESR1', 'GATA3', 'NECAB3', 'PARD6B', 'MOAP1', 'ABCA3', 'LCMT2', 'CPLX1', 'TSPAN13', 'COG7', 'HEXIM2', 'PLA2G12A', 'AFF3', 'COQ7', 'GATAD1', 'RAD17', 'ARSB', 'GPNMB', 'SULF1', 'THY1', 'CTHRC1', 'MMP1', 'COL11A1', 'PLXNC1', 'GPC6', 'TGFBR1', 'SERPINF1', 'G6PD', 'ACTR3', 'FBN1', 'CHRNA1', 'CAP1', 'BLOC1S1', 'EDF1', 'ELOB', 'GADD45GIP1', 'ZNF593', 'PET100', 'COX4I1', 'FAU', 'RNF181', 'SERF2', 'MRPL55', 'NAA10', 'UBL5', 'MRPL52', 'DRAP1', 'CNPY2', 'ABCA9', 'PLSCR4', 'ABCA8', 'AASS', 'STARD9', 'ADAM33', 'TGFBR2', 'SH3D19', 'TTC28', 'ABCA10', 'RUNX1T1', 'DIXDC1', 'SHE', 'FREM1', 'UTRN', 'PCSK5', 'PSAT1', 'FAM171A1', 'CDC20', 'TTK', 'PPP1R14C', 'CDCA8', 'AURKB', 'PIMREG', 'ORC1', 'SRPK1', 'EN1', 'NDC80', 'AMD1', 'MICALL1', 'DEPDC1', 'RRP1B']

[EVIDENCE 1] source=ChEA type=tf_target_set title=ChEA term CREM 20920259 ChIP-Seq GC1-SPG Mouse
GENES=['ACTR3', 'AFF3', 'AMD1', 'AURKB', 'CAP1', 'CDC20', 'CHRNA1', 'COQ7', 'COX4I1', 'CPLX1', 'DRAP1', 'EDF1']
ChEA tf_target_set ChEA term CREM 20920259 ChIP-Seq GC1-SPG Mouse 候选基因交集：ACTR3, AFF3, AMD1, AURKB, CAP1, CDC20, CHRNA1, COQ7, COX4I1, CPLX1, DRAP1, EDF1, FAU, HEXIM2, LCMT2, MICALL

[EVIDENCE 2] source=ChEA type=tf_target_set title=ChEA term HNF4A 19822575 ChIP-Seq HepG2 Human
GENES=['AASS', 'ABCA8', 'ABCA9', 'ACTR3', 'AFF3', 'ARSB', 'AURKB', 'CAP1', 'COG7', 'COQ7', 'CPLX1', 'DIXDC1']
ChEA tf_target_set ChEA term HNF4A 19822575 ChIP-Seq HepG2 Human 候选基因交集：AASS, ABCA8, ABCA9, ACTR3, AFF3, ARSB, AURKB, CAP1, COG7, COQ7, CPLX1, DIXDC1, ESR1, FAM171A1, FREM1, GATAD1

[EVIDENCE 3] source=MSigDB type=gene_set title=MSigDB gene set GOBP_CELL_CYCLE
GENES=['ACTR3', 'AURKB', 'CDC20', 'CDCA8', 'GATA3', 'GPNMB', 'HEXIM2', 'NAA10', 'NDC80', 'ORC1', 'PARD6B', 'RAD17']
MSigDB gene_set MSigDB gene set GOBP_CELL_CYCLE 候选基因交集：ACTR3, AURKB, CDC20, CDCA8, GATA3, GPNMB, HEXIM2, NAA10, NDC80, ORC1, PARD6B, RAD17, SRPK1, STARD9, TGFBR1, TTC28, TTK

[EVIDENCE 4] source=MSigDB type=gene_set title=MSigDB gene set GOBP_CYTOSKELETON_ORGANIZATION
GENES=['ACTR3', 'AURKB', 'CAP1', 'CDC20', 'CDCA8', 'DIXDC1', 'FAM171A1', 'MICALL1', 'NDC80', 'PARD6B', 'SH3D19', 'STARD9']
MSigDB gene_set MSigDB gene set GOBP_CYTOSKELETON_ORGANIZATION 候选基因交集：ACTR3, AURKB, CAP1, CDC20, CDCA8, DIXDC1, FAM171A1, MICALL1, NDC80, PARD6B, SH3D19, STARD9, TGFBR1, THY1, TTK

[EVIDENCE 5] source=PanglaoDB type=cell_type_marker title=PanglaoDB markers for Fibroblasts
GENES=['ADAM33', 'CTHRC1', 'FBN1']
PanglaoDB cell_type_marker PanglaoDB markers for Fibroblasts 候选基因交集：ADAM33, CTHRC1, FBN1

[EVIDENCE 6] source=PubMed type=paper_abstract title=TRPS1: a highly sensitive and specific marker for breast carcinoma, especially for triple-negative breast cancer.
GENES=['GATA3']
PubMed paper_abstract TRPS1: a highly sensitive and specific marker for breast carcinoma, especially for triple-negative breast cancer. 候选基因交集：GATA3

[EVIDENCE 7] source=PubMed type=paper_abstract title=New generation breast cancer cell lines developed from patient-derived xenografts.
GENES=['ESR1']
PubMed paper_abstract New generation breast cancer cell lines developed from patient-derived xenografts. 候选基因交集：ESR1

[EVIDENCE 8] source=Reactome type=pathway_gene_set title=Reactome pathway Signal Transduction
GENES=['ACTR3', 'AURKB', 'CDC20', 'CDCA8', 'COL11A1', 'DRAP1', 'ESR1', 'FBN1', 'GATA3', 'GPNMB', 'NDC80', 'PARD6B']
Reactome pathway_gene_set Reactome pathway Signal Transduction 候选基因交集：ACTR3, AURKB, CDC20, CDCA8, COL11A1, DRAP1, ESR1, FBN1, GATA3, GPNMB, NDC80, PARD6B, PCSK5, TGFBR1, TGFBR2

[EVIDENCE 9] source=Reactome type=pathway_gene_set title=Reactome pathway Post-translational protein modification
GENES=['ARSB', 'AURKB', 'CDC20', 'CDCA8', 'COG7', 'ELOB', 'ESR1', 'FBN1', 'GATA3', 'RNF181', 'TGFBR1', 'TGFBR2']
Reactome pathway_gene_set Reactome pathway Post-translational protein modification 候选基因交集：ARSB, AURKB, CDC20, CDCA8, COG7, ELOB, ESR1, FBN1, GATA3, RNF181, TGFBR1, TGFBR2, THY1

[EVIDENCE 10] source=Reactome type=pathway_gene_set title=Reactome pathway Developmental Biology
GENES=['ACTR3', 'CAP1', 'COL11A1', 'DRAP1', 'ELOB', 'FAU', 'GATA3', 'PLXNC1', 'SRPK1', 'UTRN']
Reactome pathway_gene_set Reactome pathway Developmental Biology 候选基因交集：ACTR3, CAP1, COL11A1, DRAP1, ELOB, FAU, GATA3, PLXNC1, SRPK1, UTRN

Return ONLY JSON. No markdown. No extra text.
```


## Qwen Raw Response

```
{
  "global_gene_weights": [
    {"gene": "ESR1", "weight": 1.5, "reason": "Strong luminal marker supported by multiple evidence sources."},
    {"gene": "GATA3", "weight": 1.4, "reason": "Key luminal regulator with strong literature support."},
    {"gene": "GPNMB", "weight": 1.3, "reason": "High variance and cluster-specific marker for separation."},
    {"gene": "ACTR3", "weight": 1.2, "reason": "Supported by cell cycle and cytoskeleton pathway evidence."},
    {"gene": "AURKB", "weight": 1.2, "reason": "Cell cycle regulator with multi-source pathway support."},
    {"gene": "CDC20", "weight": 1.2, "reason": "Cell cycle marker supported by MSigDB and Reactome."},
    {"gene": "CDCA8", "weight": 1.2, "reason": "Cell cycle marker with consistent pathway evidence."},
    {"gene": "NDC80", "weight": 1.2, "reason": "Chromosome segregation marker supported by multiple sources."},
    {"gene": "PARD6B", "weight": 1.2, "reason": "Cluster-specific marker with cell cycle pathway support."},
    {"gene": "RAD17", "weight": 1.2, "reason": "Cluster-specific marker supported by cell cycle gene set."},
    {"gene": "TGFBR1", "weight": 1.2, "reason": "Signaling pathway marker with Reactome support."},
    {"gene": "TGFBR2", "weight": 1.2, "reason": "Signaling pathway marker with Reactome support."}
  ],
  "suppress_genes": [],
  "modules": [
    {
      "name": "module_luminal",
      "genes": ["ESR1", "GATA3", "GPNMB", "ACTR3", "AURKB", "CDC20", "CDCA8", "NDC80", "PARD6B", "RAD17"],
      "weight": 1.3,
      "reason": "Combines luminal identity with cell cycle activity for subtype separation."
    },
    {
      "name": "module_mesenchymal",
      "genes": ["TGFBR1", "TGFBR2", "COL11A1", "THY1", "MMP1", "GPNMB", "ARSB", "SULF1"],
      "weight": 1.1,
      "reason": "Captures EMT and stromal interaction signals for cluster distinction."
    }
  ],
  "prototypes": [
    {
      "name": "prototype_luminal",
      "genes_up": ["ESR1", "GATA3", "GPNMB"],
      "genes_down": ["TGFBR1", "COL11A1"]
    }
  ],
  "key_gene_sets": ["Luminal_Program", "Cell_Cycle_Activity", "EMT_Transition"],
  "key_regulators": ["ESR1", "GATA3", "TGFBR1"],
  "notes": ["Prioritizes luminal markers ESR1/GATA3 for class separation.", "Integrates cell cycle genes to distinguish proliferative clusters.", "Uses TGFBR1/2 to capture EMT-like cluster differences."]
}
```


## Parsed Prior JSON

```json
{
  "global_gene_weights": [
    {
      "gene": "ESR1",
      "weight": 1.5,
      "reason": "Strong luminal marker supported by multiple evidence sources."
    },
    {
      "gene": "GATA3",
      "weight": 1.4,
      "reason": "Key luminal regulator with strong literature support."
    },
    {
      "gene": "GPNMB",
      "weight": 1.3,
      "reason": "High variance and cluster-specific marker for separation."
    },
    {
      "gene": "ACTR3",
      "weight": 1.2,
      "reason": "Supported by cell cycle and cytoskeleton pathway evidence."
    },
    {
      "gene": "AURKB",
      "weight": 1.2,
      "reason": "Cell cycle regulator with multi-source pathway support."
    },
    {
      "gene": "CDC20",
      "weight": 1.2,
      "reason": "Cell cycle marker supported by MSigDB and Reactome."
    },
    {
      "gene": "CDCA8",
      "weight": 1.2,
      "reason": "Cell cycle marker with consistent pathway evidence."
    },
    {
      "gene": "NDC80",
      "weight": 1.2,
      "reason": "Chromosome segregation marker supported by multiple sources."
    },
    {
      "gene": "PARD6B",
      "weight": 1.2,
      "reason": "Cluster-specific marker with cell cycle pathway support."
    },
    {
      "gene": "RAD17",
      "weight": 1.2,
      "reason": "Cluster-specific marker supported by cell cycle gene set."
    },
    {
      "gene": "TGFBR1",
      "weight": 1.2,
      "reason": "Signaling pathway marker with Reactome support."
    },
    {
      "gene": "TGFBR2",
      "weight": 1.2,
      "reason": "Signaling pathway marker with Reactome support."
    }
  ],
  "suppress_genes": [],
  "modules": [
    {
      "name": "module_luminal",
      "genes": [
        "ESR1",
        "GATA3",
        "GPNMB",
        "ACTR3",
        "AURKB",
        "CDC20",
        "CDCA8",
        "NDC80",
        "PARD6B",
        "RAD17"
      ],
      "weight": 1.3,
      "reason": "Combines luminal identity with cell cycle activity for subtype separation."
    },
    {
      "name": "module_mesenchymal",
      "genes": [
        "TGFBR1",
        "TGFBR2",
        "COL11A1",
        "THY1",
        "MMP1",
        "GPNMB",
        "ARSB",
        "SULF1"
      ],
      "weight": 1.1,
      "reason": "Captures EMT and stromal interaction signals for cluster distinction."
    }
  ],
  "prototypes": [
    {
      "name": "prototype_luminal",
      "genes_up": [
        "ESR1",
        "GATA3",
        "GPNMB"
      ],
      "genes_down": [
        "TGFBR1",
        "COL11A1"
      ]
    }
  ],
  "key_gene_sets": [
    "Luminal_Program",
    "Cell_Cycle_Activity",
    "EMT_Transition"
  ],
  "key_regulators": [
    "ESR1",
    "GATA3",
    "TGFBR1"
  ],
  "notes": [
    "Prioritizes luminal markers ESR1/GATA3 for class separation.",
    "Integrates cell cycle genes to distinguish proliferative clusters.",
    "Uses TGFBR1/2 to capture EMT-like cluster differences."
  ]
}
```

