# Differentially Expressed Genes Analysis of Saccharomyces cerevisiae Cultivated in Lignocellulosic Hydrolysate Using R

## 📌 Project Overview
This project aims to identify differentially expressed genes (DEGs) in *Saccharomyces cerevisiae* cultivated in lignocellulosic hydrolysate compared to a sugar-based control medium. Transcriptomic data were obtained from the Gene Expression Omnibus (GEO) and analyzed using R.

The analysis includes differential expression testing, Gene Ontology (GO) enrichment, KEGG pathway analysis, and multiple data visualizations to explore molecular adaptation mechanisms.

---

## 🧬 Objectives
- Identify upregulated and downregulated genes under hydrolysate conditions
- Perform functional enrichment analysis (GO and KEGG)
- Visualize gene expression patterns using heatmap, volcano plot, and boxplot
- Map significant genes to metabolic pathways using KEGG Mapper

---

## 🗂 Project Structure

---

## 🛠 Tools and Packages

Analysis was performed using:

- R (version X.X.X)
- limma
- clusterProfiler
- org.Sc.sgd.db
- enrichplot
- ggplot2
- pheatmap

---

## 📊 Analysis Workflow

1. Data retrieval from GEO
2. Data preprocessing and filtering
3. Differential expression analysis using limma
4. Gene annotation and ID conversion
5. GO enrichment analysis
6. KEGG pathway enrichment analysis
7. Data visualization (boxplot, volcano plot, heatmap)
8. KEGG Mapper pathway visualization

---

## 📈 Key Results

- Significant DEGs identified using FDR < 0.05 and |log2FC| > 1
- Enriched biological processes related to carbohydrate metabolism
- KEGG pathways associated with galactose metabolism and glycolysis were significantly enriched

---

## 📌 Biological Interpretation

The results suggest that *S. cerevisiae* activates carbohydrate metabolic pathways and stress-response mechanisms when cultivated in lignocellulosic hydrolysate. These findings provide insight into transcriptional adaptation under hydrolysate-induced stress conditions.

---

## 📎 Data Source

Gene Expression Omnibus (GEO)  
Accession Number: [GSE218764]

---

## 📄 License
This project is intended for academic and educational purposes.
