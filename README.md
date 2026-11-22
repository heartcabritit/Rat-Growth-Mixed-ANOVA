# Mixed-Design Repeated Measures ANOVA of Rat Growth

**Course:** BIO2105 – Biostatistics  
**Assessment:** Formative Assessment 11  
**Repository:** `Rat-Growth-Mixed-ANOVA`

## Research Objectives
This project analyzes longitudinal body weight data from a rat growth experiment to determine:
1. Whether average rat body weight (`y`, in grams) differs significantly across three treatment groups (**Control**, **Thiouracil**, and **Thyroxin**).
2. Whether average body weight changes significantly across five measurement occasions (**Week 0**, **Week 1**, **Week 2**, **Week 3**, and **Week 4**).
3. Whether the pattern of body weight change over time differs depending on the treatment group (**Treatment × Time** interaction).

## Dataset Overview
- **Dataset:** `rats` from the `nlmm` R package (based on Box, 1950).
- **Sample Size:** 27 rats and 135 observations across five measurement occasions (originally 30 rats with 10 per group; 3 rats in the Thyroxin group were removed following an accident, leaving unequal group sizes that are retained as provided).
- **Variables:**
  - `id`: Individual rat identifier (nominal / subject ID)
  - `trt`: Treatment group — `Control`, `Thiouracil`, `Thyroxin` (between-subjects factor)
  - `time`: Measurement occasion — `Week 0` through `Week 4` (within-subjects factor)
  - `y`: Body weight in grams (continuous dependent variable)

## Repository Structure
- `README.md`: Project overview, research objectives, dataset summary, file descriptions, and reproduction instructions.
- `Rat_Growth_Mixed_ANOVA.R`: Complete, commented R script executing data preparation, descriptive statistics, plots, assumption checks, mixed-design repeated measures ANOVA, and post hoc/simple main effects analyses.
- `Rat_Growth_Mixed_ANOVA.Rmd`: R Markdown report integrating narrative, code chunks, statistical outputs, tables, visualizations, and interpretations.
- `Rat_Growth_Mixed_ANOVA.html` (or `.pdf`): Knitted/rendered report generated from the R Markdown source file.
- `data/Rat_Growth_Dataset.csv`: Optional local copy of the dataset (if used).
