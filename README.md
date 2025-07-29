# SINGLE-CELL GENOMIC ANALYSIS USING MACHINE LEARNING

## BACKGROUND

**Single-cell genomics** is a cutting-edge field within biology that focuses on the genomic analysis of individual cells, enabling a more **precise understanding** of cellular **heterogeneity**. Unlike bulk sequencing methods which average signals across large populations of cells, single-cell approaches uncover the unique genetic makeup and variability present at the individual cell level. This granularity allows researchers to explore **cellular diversity**, **discover novel cell types**, and investigate the role of **genetic variation** in development, disease progression, and treatment response.

The most widely used technologies in single-cell studies is **RNA sequencing (RNA-seq)**. This next-generation sequencing (NGS) technique enables comprehensive profiling of the transcriptome, capturing both the identity and abundance of RNA molecules in a biological sample. The workflow typically involves RNA isolation, reverse transcription into complementary DNA (cDNA), and high-throughput sequencing. When applied to single cells, RNA-seq provides a powerful tool to dissect gene expression patterns at an unprecedented resolution.

As single-cell RNA-seq (scRNA-seq) datasets grow in **size** and **complexity**, **Machine Learning (ML)** has emerged as a transformative approach for their analysis. ML encompasses computational techniques that learn from data to make predictions or decisions without relying on explicit programming for each task. In the context of scRNA-seq, ML models can be trained to improve tasks such as clustering, dimensionality reduction, and biomarker discovery.

This project is grounded in the study of **Ewing Sarcoma**, a rare but aggressive cancer primarily affecting children, adolescents, and young adults, typically between the ages of 10 and 20. Originating from primitive nerve or stem cells, this tumor often arises in the long bones, pelvis, ribs, or spine. As the second most common bone cancer in young people (after osteosarcoma), Ewing Sarcoma presents a compelling case for high-resolution, cell-level investigation to better understand its biology and discover diagnostic or therapeutic markers.

The scRNA-seq data used in this study is publicly available on Kaggle and can be accessed [here](https://www.kaggle.com/datasets/alexandervc/rna-seq-data).

## What We Want to Do

This study aims to **compare two approaches to analyzing single-cell RNA-seq data** from Ewing Sarcoma samples:

- **Conventional (Normal) Pipeline:** Using established analysis steps such as quality control, normalization, dimensionality reduction, clustering, and marker gene identification with commonly used tools like Scanpy.

- **Machine Learning-Based Pipeline:** Leveraging the scvi-tools framework, which employs deep probabilistic models (variational autoencoders) to learn latent representations of the data that can enhance clustering, integrate batch effects, improve gene expression denoising, and yield more robust biological insights.

The comparison will focus on evaluating the performance of these pipelines regarding clustering quality, biological relevance of identified markers, reproducibility of results across datasets, and computational efficiency. This direct comparison will inform whether the advanced modeling capabilities of scvi-tools provide tangible benefits over conventional methods in analyzing complex single-cell datasets.

## RESULTS
---

## REFERENCES

1. **Durer, S., Gasalberti, D. P., & Shaikh, H.** (2024). *Ewing Sarcoma*. In **StatPearls \[Internet]**. Treasure Island (FL): StatPearls Publishing.
   [PubMed: 32644609](https://pubmed.ncbi.nlm.nih.gov/32644609/)

2. **Subbiah, V., Somaiah, N., & Trent, J. C.** (2019). *Ewing sarcoma: Current management and future approaches*. **Journal of Clinical Oncology**, 37(27), 2900–2909.
   [https://doi.org/10.1200/JCO.19.00978](https://doi.org/10.1200/JCO.19.00978)

3. **Gaspar, N., Hawkins, D. S., Dirksen, U., Lewis, I. J., Ferrari, S., Le Deley, M. C., ... & Ladenstein, R.** (2015). *Ewing sarcoma: Current management and future approaches—Results of the EICESS and Euro-E.W\.I.N.G. clinical trial groups*. **Pediatric Blood & Cancer**, 62(8), 1248–1258.
   [https://doi.org/10.1002/pbc.25552](https://doi.org/10.1002/pbc.25552)

4. **Crompton, B. D., Stewart, C., Taylor-Weiner, A., Alexe, G., Kurek, K. C., Calicchio, M. L., ... & Meyerson, M.** (2014). *The genomic landscape of pediatric Ewing sarcoma*. **Nature Genetics**, 46(5), 503–509.
   [https://doi.org/10.1038/ng.2938](https://doi.org/10.1038/ng.2938)


5. **Haque, A., Engel, J., Teichmann, S. A., & Lönnberg, T.** (2017). *A practical guide to single-cell RNA-sequencing for biomedical research and clinical applications*. **Genome Medicine**, 9(1), 75.
   [PubMed: 28821273](https://pubmed.ncbi.nlm.nih.gov/28821273/)
   [Full Text](https://genomemedicine.biomedcentral.com/articles/10.1186/s13073-017-0467-4)

6. **Zheng, G. X. Y., et al.** (2022). *Single-cell RNA sequencing technologies and applications*. **Clinical and Translational Medicine**, 12, e703.
   [PubMed: 35352511](https://pubmed.ncbi.nlm.nih.gov/35352511/)

7. **Qu, H.-Q., Kao, C., & Hakonarson, H.** (2024). *Single-Cell RNA Sequencing Technology Landscape in 2023*. **Stem Cells**, 42(1), 1–12.
   [PubMed: 37934608](https://pubmed.ncbi.nlm.nih.gov/37934608/)

8. **Luecken, M. D., & Theis, F. J.** (2019). *Current best practices in single-cell RNA-seq analysis: a tutorial*. **Molecular Systems Biology**, 15(6), e8741.
   [PubMed: 37566049](https://pubmed.ncbi.nlm.nih.gov/37566049/)
---

