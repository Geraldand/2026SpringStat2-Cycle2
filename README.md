# Project Cycle 2: Weight of Expectation
### Gendered Impacts of Body Image on Adolescent Psychological Well-being

## Group & Members
* **Group Number**: 15
* **Members**: 
    * 112370234 張智源 (Geraldand)
    * 113370201 簡愷毅 (kaibao8171)
    * 113370218 彭鈺芳 (Vickyfang77)

## Dataset
raw data:
* `YRBS_2007.csv`
  
processed data:
* `yrbs_cleaned.csv`
  
## Selected Variables & Benchmarks
* **Behavior Variable**: `SadOrHopeless`
    * **Benchmark ($p_0$)**: 0.30
* **Continuous Variable**: `BMIPCT`
    * **Benchmark ($\mu_0$)**: 65.0

## Research Questions
* **Proportion Analysis**: Does the proportion of adolescents feeling sad or hopeless significantly differ from the 0.30 (30%) national benchmark?
* **Mean Analysis**: Does the average BMI percentile (BMIPCT) of the adolescents significantly differ from the 65.0 benchmark?

## Final Conclusion
At a 5% significance level, we **failed to reject the null hypothesis ($H_0$)** for both variables. This indicates that the overall sample data does not deviate significantly from the expected benchmarks (0.30 and 65.0). 

However, our advanced Exploratory Data Analysis (EDA) revealed a clear **"J-Curve" effect**. While the overall population averages remain stable, female students with extreme body weights particularly those in the "Underweight" category experience a significantly higher probability of depression. This highlights the unique body image pressures faced by specific subgroups, a critical insight that is masked when only looking at the overall population mean.
