# Hi, I'm Amirtesh Raghuram  

I have a strong interest in **Machine Learning**, **Deep Learning**, and **Bioinformatics**. I am currently in my second year, pursuing a B.Tech in Biotechnology at VIT, Vellore, where I am actively developing my computational and bioinformatics skills.  

## **Current Skills**  

### **Data Science and Machine Learning**  
#### Python:  
- Proficient in **Scikit-learn**, **XGBoost**, **LightGBM**, and **CatBoost** for building predictive models.  
- Proficient in implementing **Deep Learning** techniques using **PyTorch** for tabular and image data, with experience in building neural networks.  
- Basics of **TensorFlow** for deep learning tasks.  
- Knowledge of **data manipulation** and **visualization** libraries, including:  
  - **NumPy** and **Pandas** for data manipulation and analysis.  
  - **Matplotlib** and **Seaborn** for creating insightful visualizations.  
- Developed a library called [**Torchify**](https://github.com/Amirtesh/Pytorch-Torchify) to simplify PyTorch workflows with features like **model.compile()**, **model.fit()**, **model.predict()**, and **model.performance()**.  

#### R:  
- Basics of data analysis and visualization using **dplyr** and **ggplot2**.  
- Basics of machine learning workflows in R.  

---  

### **Computational Drug Discovery**  
- Performing **Protein-Ligand Docking** using tools like **AutoDock Vina**, **Smina**, **QVina**, **SwissDock**, **AutoDock 4.2**, and **ADFR suite** for both rigid and flexible docking.  
- Performing **Molecular Dynamics Simulations** with **GROMACS**.  
- Performing **MMPBSA analysis** using **gmx_MMPBSA** to calculate binding free energies.  
- Using molecular visualization and modification tools such as **PyMol**, **Chimera**, **Python Molecular Viewer (PMV)**, **AutoDock Tools**, and **Discovery Studio Visualizer**.  
- Usage of **RDKit** in Python for cheminformatics, including molecular descriptor calculation, fingerprint generation, and chemical property prediction.  
- Utilizing computational tools for drug discovery, including **SwissADME**, **Swiss Target Prediction**, **Swiss Similarity**, **Protox**, **MolSoft**, and **pkcsm**.  

---  

### **BioPython**  
- Usage of **BioPython** for bioinformatics tasks, including:  
  - Reading and processing sequence files in formats like **FASTA** and **GenBank**.  
  - Creating and manipulating **SeqRecord** and **SeqFeature** objects.  
  - Performing sequence alignment using tools like **ClustalW**, **MUSCLE**, and **EMBOSS Needle/Water** (both within Python and via EMBL web tools).  
  - Using **BLAST** for sequence similarity searches - **blastn**, **blastp**, **blastx**, and **tblastn**.  
  - Working with phylogenetic data using **Bio.Phylo**.  
  - Writing output files in various biological formats.  
  - Familiar with **pairwise sequence alignment** for similarity studies.  

---  

### **RNA-Seq Analysis**  
- Performing **quality checks** on FASTQ files using **fastqc**.  
- **Trimming raw reads** with **trimmomatic**.  
- Aligning sequences to reference genomes using **HISAT2**.  
- Building a **feature count matrix** using the **featureCounts** tool from **Subread**.  
- Automating RNA-seq workflows for multiple FASTQ files to create combined counts data and metadata using **bash scripts**.  
- Performing **Differential Expression Analysis** using **DESeq2** and **edgeR** in R and using **PyDESeq2** and **DEGA** in Python, including:  
  - Loading counts and metadata to create DESeq datasets.  
  - Performing quality control on input data (e.g., row/column name checks and removing low-count reads).  
  - Running differential expression analysis and saving results.  
  - Interpreting p-values and adjusted p-values (**padj**) and identifying significantly expressed genes.  
  - Filtering results based on cutoff values (e.g., alpha and fold change).  
  - Converting **ENSEMBL IDs** to gene names for better biological interpretation.  
  - Performing quality checks on the data after differential expression analysis by building **PCA plots**, estimating **size factors**, and building **dispersion plots**.  
- Visualizing RNA-seq results by creating **MA plots**, **volcano plots**, and **heatmaps** in R.  
- Performing **Gene Ontology (GO)** and **KEGG pathway analysis** of top genes after differential expression analysis using the **DAVID tool** online.
- Performing **Geno Ontology (GO)** and **Gene Set Enrichment Analysis (GSEA)** analysis using **clusterProfiler** package in R.

---  

### **In Silico Vaccine Design**  
- **Epitope Prediction**: Prediction of **B-cell, Tc-cell, and Th-cell epitopes** using **IEDB (all 6 methods), NetCTL, and IEDB Class I/II**.  
- **Epitope Property Analysis**: Proficient in evaluating **antigenicity (ANTIGENpro, VaxiJen), allergenicity (AllerCatPro, AllerTOP, AllerFP), and toxicity (ToxinPred)** of predicted epitopes.  
- **Vaccine Construct Design**: **Constructing primary vaccine sequences** by fusing epitopes with appropriate **linkers and adjuvants**.  
- **Physicochemical Property Analysis**: Experienced in analyzing **molecular weight, pI, GRAVY, instability index (ProtParam), and solubility (SolPro)**.  
- **Structural Predictions**:  
  - **Secondary structure prediction** using **SOPMA and PSIPRED**.  
  - **Tertiary structure modeling** using **Swiss-Model, I-TASSER, and AlphaFold**.  
  - **Structural validation** through **Ramachandran plots** and **Z score analysis**.  
- **Molecular Docking**:  
  - **Protein-protein (receptor-vaccine) docking** using **HADDOCK**.  
- **Molecular Dynamics Simulation**: Experienced in performing **MD simulations of vaccine-receptor complexes** using **GROMACS** to assess stability and interactions.  

---  

### **Single-Cell RNA-Seq (scRNA-Seq) Analysis using Seurat package of R**  
- **Preprocessing & Quality Control**: Filtering low-quality cells, removing doublets using **DoubletFinder**.  
- **Normalization & Scaling**: Using default methods in **Seurat** and using **SCTransform** for faster and more accurate normalization.  
- **Dimensionality Reduction & Clustering**: Performing **PCA, UMAP, t-SNE** for visualizing cell populations.  
- **Differential Gene Expression Analysis**: Identifying **marker genes for each cluster**.  
- **Cell Type Annotation**: Assigning biological identities to clusters using marker genes.
- **Trajectory Analysis**: Using **Monocle3** with Seurat objects to infer **cell differentiation pathways** and **pseudotime trajectories**.
- **Chromatin Accessibility Analysis (scATAC-Seq)**: Using **Signac** to analyze **open chromatin regions** and integrate chromatin accessibility with gene expression. 

---

### **Weighted Gene Co-expression Network Analysis (WGCNA) in R**  
- **Gene Co-expression Analysis**: Identifying highly co-expressed gene modules from RNA-Seq data.  
- **Soft Thresholding Power Selection**: Using scale-free topology model fit to determine optimal soft threshold.  
- **Module Detection**: Constructing **signed networks** and identifying gene modules using hierarchical clustering.  
- **Trait Correlation Analysis**: Associating gene modules with phenotypic traits (e.g., disease severity).  
- **Hub Gene Identification**: Detecting key hub genes in significant modules for further functional analysis.  
- **Visualization & Interpretation**: Heatmaps, dendrograms, and module-trait correlation plots for better insights.  

---

### **Variant Calling Analysis**  
- **Quality Control & Trimming**: Using **FastQC** and **MultiQC** for QC, and **Trimmomatic**/**Fastp** for adapter trimming.  
- **Read Alignment**: Mapping reads to a **reference genome** using **HISAT2 (whole genome)** and **BWA (specific chromosome)**.  
- **BAM File Processing**: Sorting, fixing coordinates, marking/removing duplicates, and indexing BAM files using **Samtools**.  
- **Variant Calling & Filtering**: Identifying **SNPs and Indels** using **FreeBayes**, and filtering variants with **Bcftools**.  
- **Variant Visualization**: Using **plotVCF** in **R** for visualizing called variants.

---

### **ChIP-Seq Data Analysis**  
- **Data Acquisition & Preprocessing**: Downloading ChIP-Seq data in **SRA format** and converting to **FASTQ** using **fastq-dump** or **fasterq-dump** from the NCBI toolkit.  
- **Quality Control & Trimming**: Performing QC using **FastQC**, and trimming reads with **Fastp**.  
- **Genome Alignment**: Mapping reads to a **reference genome** using **BWA**.  
- **BAM File Processing**: Sorting BAM files, filtering reads with a Q value using **Samtools**.  
- **Peak Calling**: Identifying enriched regions using **MACS2**.  
- **Peak Annotation & Motif Finding**:  
  - Using **HOMER suite** (**annotatePeaks.pl**, **findMotifsGenome.pl**) to analyze regulatory elements.  
  - Using **ChIPSeeker (R)** for **peak annotation** and performing **Gene Ontology (GO) and KEGG pathway analysis** on identified genes.  

---

### **Genome/Reads Assembly**  
- **Short-Read Assembly**:  
  - **Quality Control & Trimming**: Using **FastQC**, **MultiQC**, and **Porechop** for adapter trimming.  
  - **Genome Assembly**: Assembling short reads using **SPAdes**.  
  - **Visualization**: Inspecting assembly graphs using **Bandage**.  

- **Long-Read Assembly**:  
  - **Quality Control & Trimming**: Using **FastQC** and **Porechop** for long-read preprocessing.  
  - **Genome Assembly**: Assembling long reads using **Flye**.  
  - **Visualization**: Exploring assembly graphs with **Bandage**.

---

### **Metagenomics Data Analysis**  
- **Quality Control & Trimming**: Performing QC using **FastQC** and trimming reads with **appropriate tools**.  
- **Taxonomic Classification**: Using **Kraken2** with appropriate reference databases for microbial identification.  
- **Abundance Estimation**: Quantifying microbial abundance using **Bracken**.  
- **Visualization**: Creating taxonomy-based visualizations of identified microbes using **ktImportTaxonomy**.

---

### **Genome-Wide Association Studies (GWAS) using PLINK**  
- **Data Preparation & Conversion**: Converting input data into **PLINK binary format (BED, BIM, FAM)** for efficient computation.  
- **Quality Control (QC)**:  
  - Filtering samples and SNPs based on **missingness thresholds**.  
  - Filtering based on **Minor Allele Frequency (MAF)** and **Hardy-Weinberg Equilibrium (HWE)** p-values.  
- **Association Testing**:  
  - Performing association tests using **plink --assoc**, **--logistic**, **--linear**, and **--model** commands depending on trait type (binary/quantitative).  
- **Visualization**:  
  - Creating **Manhattan plots** and **QQ plots** in **R** for GWAS result interpretation.  
- **Result Interpretation**:  
  - Extracting and filtering **top hits** based on p-value thresholds.  
  - Annotating significant SNPs to genes for biological interpretation.

---

### **DNA Methylation Data Analysis**
- **Trimming**: Using **Trim Galore!** for adapter and quality trimming of bisulfite sequencing data.
- **Alignment & Methylation Extraction**:  
  - **Bismark** for genome preparation, alignment of bisulfite-treated reads, deduplication, and methylation extraction.
- **Downstream Differential Methylation Analysis**:  
  - **methylKit** to identify significantly differentially methylated cytosines (DMCs) across chromosomes.
  - **annotatr** for annotation of DMCs with genomic features (promoters, CpG islands, etc.).
  - **clusterProfiler** for **GO and KEGG pathway enrichment** analysis on annotated genes.

---


### **Let’s Connect**  
Feel free to reach out if you’d like to discuss projects, research, or opportunities!  
[LinkedIn](https://in.linkedin.com/in/amirtesh-raghuram-90161828a)  

**Email**: amirtesh21.5@gmail.com  
