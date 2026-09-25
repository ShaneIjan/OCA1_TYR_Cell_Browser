# OCA1_TYR_Cell_Browser
UCSC Cell Browser activity for TYR and Oculocutaneous albinism type 1 (OCA1)

---

# UCSC Cell Browser Activity

**Student Name:** Ijan, Shane Mae B.

## Assigned Gene and Disease

**Gene:** TYR (Tyrosinase)

**Associated Disease:** Oculocutaneous albinism type 1 (OCA1)

This activity uses the same assigned disease gene from the previous bioinformatics activity. The UCSC Cell Browser will be used to investigate the expression of TYR at the single-cell level and identify the cell types or clusters in which the gene is detectable.

---

## Organ/Tissue Choice and Dataset Information

The UCSC Cell Browser was used to identify a human single-cell dataset relevant to the assigned *TYR* gene and Oculocutaneous albinism type 1 (OCA1). The dataset information, including the tissue, organism, study title, publication, and dataset ID, was obtained from the **Dataset Information** window in the UCSC Cell Browser and is shown as evidence in Figure 1.

**Dataset:** Normal and Inflamed Human Epidermis

**Dataset ID:** `human-epidermis`

**Organ/Tissue:** Skin/Epidermis

**Organism:** Human (*Homo sapiens*)

**Study:** *Transcriptional Programming of Normal and Inflamed Human Epidermis at Single-Cell Resolution*

**Publication:** Cheng et al. (2018), *Cell Reports*

**PubMed:** 30355494

**Study Accession:** EGAS00001002927

**Dataset URL:** https://cells.ucsc.edu/?ds=human-epidermis 

### Why This Dataset Was Selected?

The human epidermis was selected because the TYR gene is associated with melanin production and Oculocutaneous albinism type 1 (OCA1), a disorder that affects pigmentation. This dataset is relevant because it represents human skin and contains a melanocyte cell population that can be examined for TYR expression. The selection and dataset information are supported by the UCSC Cell Browser evidence shown in the first screenshot (Figure 1).


![Normal and Inflamed Human Epidermis dataset information](screenshots/01_dataset.png)

**Figure 1.** Dataset information for the Normal and Inflamed Human Epidermis single-cell dataset in the UCSC Cell Browser.

Shown in Figure 1 is the Normal and Inflamed Human Epidermis dataset selected for the analysis of TYR. The displayed information identifies the dataset as human epidermal tissue and provides the corresponding study and dataset details used for the activity.

---

## Understanding the Cell Map

The UCSC Cell Browser was used to examine the cell map of the Normal and Inflamed Human Epidermis dataset. The visualization and cluster information were obtained from the Cell Browser interface.

### Cell Map Observations

**a. What type of visualization is being shown (UMAP, t-SNE, or another layout)?**  
The visualization is a UMAP (Uniform Manifold Approximation and Projection). After clicking the Layout tab, the Embedding option showed `umap_hm`, indicating that the cell map uses a UMAP embedding.

**b. What does one dot represent?**  
Each dot represents one measured cell in the human epidermis single-cell dataset. Cells positioned close to one another generally have more similar molecular profiles.

**c. What do the clusters represent in this particular dataset?**  
The clusters represent different cell types or cell states identified through the dataset's Re-annotation. The labels shown on the map correspond to different groups of cells, including melanocytes, basal cells, and immune cells.

---

## Assigned Gene Expression

The assigned gene *TYR* was searched using the Gene tab in the UCSC Cell Browser. After selecting TYR, the cell map was recolored according to TYR expression, and the expression legend on the right side of the map showed the distribution of expression values.

**a. Assigned gene symbol:**  
My assigned gene is TYR (tyrosinase).

**b. Dataset used:**  
The dataset used is Normal and Inflamed Human Epidermis.

**c. Is expression widespread, restricted, or low/undetected?**  
TYR expression appears restricted mainly to the melanocyte cluster and is low or undetected in most cells. The expression legend shows that approximately 92.7% of cells have a value of 0, while the remaining cells show detectable expression at different levels.

**d. Which cluster(s) appear to contain cells with stronger expression?**  
The melanocyte cluster appears to contain cells with the strongest TYR expression.

**e. Which cluster(s) appear to contain little or no detectable expression?**  
Most other clusters, including spinuous, basal1, basal2, follicular, mitotic, WNT1, channel, and immune, show little or no detectable TYR expression compared with the melanocyte cluster.


![TYR gene expression across the cell map](screenshots/02_gene_expression.png)

**Figure 2.** Expression of the human TYR gene across cells in the Normal and Inflamed Human Epidermis dataset.

Figure 2 presents the distribution of TYR expression across the cell map after the gene was selected in the UCSC Cell Browser. The color intensity represents different expression levels, with stronger *TYR* expression concentrated in the melanocyte cluster and little or no detectable expression observed in most other cell populations.

---

## Cell-Type/Cluster Expression of TYR

The cell-type distribution of *TYR* expression was examined using the annotated cell map in the UCSC Cell Browser. The map was viewed with the cell-type/cluster labels visible, and the melanocyte cluster was examined more closely to compare its *TYR* expression with the other cell populations. The observed expression pattern and cell-type annotations are shown in Figure 3.

**a. Cell type/cluster with the strongest visible expression:**  
The melanocyte cluster shows the strongest visible expression of *TYR*.

**b. Another cell type/cluster with detectable expression:**  
Another cell type was not selected because the expression was mainly concentrated in the melanocyte cluster.

**c. Cell type/cluster with relatively low or undetected expression:**  
Most of the other clusters, including **spinuous, basal1, basal2, follicular, mitotic, WNT1, channel, and immune**, showed little or no detectable *TYR* expression.

**d. Is the expression pattern broad or cell-type restricted?**  
The TYR expression pattern is cell-type restricted, with the strongest visible expression concentrated in the melanocyte cluster.

**e. Possible biological explanation:**  
The observed pattern suggests that TYR expression is concentrated in melanocytes in this dataset. This may be related to the role of tyrosinase in melanin production.


![TYR gene expression and cell-type annotation](screenshots/03_cell_types.png)

**Figure 3.** TYR gene-expression map showing cell-type/cluster annotations in the Normal and Inflamed Human Epidermis dataset.

A closer view of the TYR expression pattern and its corresponding cell-type annotation is provided in Figure 3. The melanocyte cluster is clearly identified and contains the strongest visible TYR expression. The annotation panel and expression legend further support the identification of the melanocyte cluster and the observed cell-type-restricted expression pattern.

---

## Selected Cells and Gene-Expression Comparison

The melanocyte cluster was selected while TYR remained active in the Gene tab of the UCSC Cell Browser. A violin plot was then examined to compare the distribution of *TYR* expression values between the selected melanocyte cells and the other cells. The resulting expression comparison is shown in Figure 4.

**a. Which cells/cluster did you select?**  
I selected cells from the melanocyte cluster, which consisted of 4,277 selected cells.

**b. Does your selected group show higher, lower, or similar expression compared with the comparison cells?**  
The selected melanocyte cells show higher TYR expression compared with the other cells. The expression values of the selected cells are distributed at higher levels, while the expression values of the comparison cells are concentrated mainly near zero.

**c. What does the expression plot add that was not obvious from the UMAP/t-SNE map?**  
The expression plot shows the distribution of TYR expression values in the selected melanocyte cells compared with the other cells. While the UMAP map shows where TYR-expressing cells are located, the violin plot provides a clearer comparison of the expression levels between the selected and comparison groups.

![TYR expression plot comparing selected melanocyte cells with other cells](screenshots/04_expression_plot.png)

**Figure 4.** Violin plot comparing *TYR* expression between selected melanocyte cells and other cells in the Normal and Inflamed Human Epidermis dataset.

The violin plot provides a direct comparison of the TYR expression distributions between the selected melanocyte cells and the other cells. The selected group shows expression values distributed at higher levels, whereas the comparison group is concentrated mainly near zero.

---

## Marker Genes of the Melanocyte Cluster

The melanocyte cluster was examined for marker genes using the cluster-marker table in the UCSC Cell Browser. Three marker genes were recorded from the displayed table: *MLANA*, *DCT*, and *TYRP1*. The marker gene *MLANA* was then selected to display its expression across the cell map, and its expression pattern was compared with the previously observed pattern of the assigned disease gene (TYR). Both genes showed strong expression in the melanocyte cluster, although the MLANA expression pattern was more visibly distributed across some additional cell populations. The marker-gene information for the melanocyte cluster is shown in Figure 5.

**a. Cluster/cell type examined:**  
The cluster examined was the melanocyte cluster.

**b. Marker gene 1:**  
The first marker gene recorded was **MLANA**.

**c. Marker gene 2:**  
The second marker gene recorded was **DCT**.

**d. Marker gene 3:**  
The third marker gene recorded was **TYRP1**.

**e. Does your assigned gene behave like a cell-type marker in this dataset? Explain briefly.**  
Yes. The assigned disease gene TYR behaves like a cell-type marker in this dataset because its expression is mainly concentrated in the melanocyte cluster, with little or no detectable expression in most other cell types.


![Marker-gene information for the melanocyte cluster](screenshots/05_marker_genes.png)

**Figure 5.** Marker-gene information for the melanocyte cluster in the Normal and Inflamed Human Epidermis dataset.

Figure 5 presents the marker-gene table generated for the melanocyte cluster in the UCSC Cell Browser. Among the displayed marker genes are *MLANA*, *DCT*, and *TYRP1*, which were recorded for this activity. The table also provides the corresponding z scores and additional information for the marker genes associated with the selected cluster.

---

## Comparison of the Assigned Disease Gene and a Marker Gene

The assigned disease gene *TYR*, associated with **Oculocutaneous albinism type 1 (OCA1)**, was compared with *MLANA*, a marker gene identified from the **melanocyte cluster** in Part G. Each gene was viewed separately on the cell map in the UCSC Cell Browser, and their expression patterns across the annotated cell populations were compared. A direct multiple-gene plot was also attempted using Gene Expression Plots, but the two genes did not load together in the available interface.

**a. Assigned disease gene:**  
The assigned disease gene is *TYR* (tyrosinase), which is associated with **Oculocutaneous albinism type 1 (OCA1)**.

**b. Marker gene:**  
The marker gene selected for comparison is *MLANA*, which was identified in the marker-gene table for the **melanocyte cluster**.

**c. Which gene shows a more cell-type-restricted expression pattern?**  
*TYR* shows a **more cell-type-restricted expression pattern** in this dataset. Its strongest visible expression is concentrated in the melanocyte cluster, while most of the other cell populations show little or no detectable expression.

**d. Which gene appears more broadly expressed?**  
*MLANA* appears **more broadly expressed** in this dataset. Although strong *MLANA* expression is visible in the melanocyte cluster, detectable expression is also distributed across additional cell populations compared with the more restricted pattern observed for *TYR*.

**e. What does this comparison teach you about the difference between a disease-associated gene and a cell-type marker gene?**  
The comparison shows that a **disease-associated gene** and a **cell-type marker gene** can both be strongly associated with the same cell type while still having different expression patterns. In this dataset, the disease-associated gene *TYR* showed a more restricted expression pattern in melanocytes, whereas the melanocyte marker gene *MLANA* showed a broader visible distribution across the cell map. This indicates that being disease-associated or being used as a cell-type marker does not necessarily determine how broadly or narrowly a gene is expressed.

### Comparison of TYR and MLANA Expression

The expression patterns of the assigned disease gene TYR, associated with Oculocutaneous albinism type 1 (OCA1), and the melanocyte marker gene MLANA were compared across the annotated cell populations in the dataset. Both genes showed strong expression in the melanocyte cluster, but their expression across the other cell types differed. The table below summarizes the observed expression patterns of the two genes.

| Comparison | Assigned Disease Gene (*TYR*) | Melanocyte Marker Gene (*MLANA*) |
|---|---|---|
| Role in this activity | Assigned disease gene associated with OCA1 | Marker gene selected from the melanocyte cluster |
| Expression in melanocytes | Strongest visible expression was concentrated in the melanocyte cluster | Strong expression was also visible in the melanocyte cluster |
| Expression outside melanocytes | Little or no detectable expression was observed in most other clusters | Detectable expression was visible across additional cell populations |
| Overall observed pattern | More cell-type restricted | More broadly expressed |

Based on the observed cell maps, *TYR* showed a more cell-type-restricted expression pattern, whereas *MLANA* appeared more broadly expressed in this dataset. Although both genes were strongly associated with the melanocyte cluster, their distributions were not identical. This comparison shows that a disease-associated gene and a cell-type marker gene can be associated with the same cell type without having the same expression pattern. A gene's association with a disease does not necessarily determine how broadly it is expressed, while a marker gene is useful for helping characterize or distinguish a particular cell type.



