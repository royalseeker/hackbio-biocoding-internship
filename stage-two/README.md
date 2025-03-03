## **Task Code 2.1: [Microbiology](/stage-two/Stage2_2_1.ipynb)**
- Microbial growth curve analysis (OD600 vs. Time)
- Strain comparison (knock-out vs. knock-in)
- Calculation of carrying capacity timepoints
- Data visualization:
  - Line plots (growth curves)
  - Scatter plots (time to carrying capacity)
  - Box plots (time distribution comparison)
- Statistical analysis (t-test/ANOVA for strain differences)
- Biological interpretation of growth dynamics

---

## **Task Code 2.3: [Botany and Plant Science](/stage-two/Stage2_2_3.ipynb)**
- Metabolic response analysis (ΔM calculation)
- Data visualization:
  - Scatter plots with residuals
  - Line plots (time-course metabolite dynamics)
- Linear regression (slope=1, intercept=0)
- Residual analysis and threshold filtering
- Identification of outlier metabolites
- Interpretation of pesticide resistance mechanisms

---

## **Task Code 2.4: [Biochemistry & Oncology](/stage-two/Stage2_2_4.ipynb)**
- Protein mutation impact analysis:
  - SIFT scores (functional impact)
  - FoldX scores (structural impact)
- Dataset merging and cleaning
- Deleterious mutation classification
- Amino acid substitution nomenclature
- Frequency analysis:
  - Bar plots
  - Pie charts
- Structural/functional property analysis of high-impact amino acids

---

## **Task Code 2.6: [Transcriptomics](/stage-two/Stage2_2_6.ipynb)**
- RNA-seq data analysis:
  - Volcano plots (log2FC vs. -log10(p-value))
- Differential expression analysis:
  - Upregulated genes (Log2FC > 1, p < 0.01)
  - Downregulated genes (Log2FC < -1, p < 0.01)
- Gene functional annotation (GeneCards)
- Interpretation of compound treatment effects

---

## **Task Code 2.7: [Public Health](/stage-two/Stage2_2_7.ipynb)**
- NHANES dataset processing:
  - NA handling strategies
  - Unit conversions (kg to lbs)
- Descriptive statistics:
  - Mean, range, variance, standard deviation
- Data visualization:
  - Histograms (BMI, weight, age)
  - Scatter plots (weight vs. height with grouping)
- Hypothesis testing:
  - T-tests for group comparisons
- Epidemiological interpretation

---

# **Cross-Task Technical Skills**
1. **Data Manipulation**
   - Missing value handling
   - Dataset merging (`specific_Protein_aa` concatenation)
   - Unit conversions
2. **Statistical Analysis**
   - T-tests
   - Variance/SD calculations
   - Residual analysis
3. **Visualization**
   - Multi-panel plots (`par(mfrow)`)
   - Grouped scatter plots (color by categories)
   - Volcano plots
   - Frequency plots (bar/pie charts)
4. **Biological Interpretation**
   - Gene functional annotation
   - Mutation impact analysis
   - Metabolic pathway inference
   - Public health metric evaluation
