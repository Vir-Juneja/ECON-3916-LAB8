# Hypothesis Testing — Is Job Training Worth It?

## Objective
I used hypothesis testing to examine whether job training increased participants' earnings in 1978 and whether the results were statistically significant.

## Methodology
- **Data:** I analyzed the LaLonde NSW job training experiment, which included 445 people: 185 trainees and 260 controls.
- **Hypothesis Testing:** I ran a one-sample t-test and a two-sample Welch's t-test on 1978 earnings.
- **Custom Function:** I wrote `welch_t()` to calculate Welch's t-statistic and checked my results against SciPy using the full sample and five subgroups.
- **Effect Size:** I calculated Cohen's d to measure the size of the treatment effect, rather than relying only on statistical significance.
- **Power Analysis:** I estimated the study's statistical power and the sample size needed to detect an effect size of d = 0.3.
- **Subgroup Analysis:** I tested treatment effects across five overlapping demographic subgroups.
- **Multiple Testing:** I applied Bonferroni and Benjamini-Hochberg corrections to account for testing multiple hypotheses.
- **Simulations:** I simulated p-value distributions under both true and false null hypotheses to understand how statistical significance behaves.

## Key Findings
- Trainees earned **$[YOUR VALUE] more** than controls in 1978.
- Welch's t-test produced a **t-statistic of [YOUR VALUE]** and a **p-value of [YOUR VALUE]**.
- The treatment effect had a **Cohen's d of [YOUR VALUE]**, which I used to assess its practical size.
- **[YOUR VALUE] out of 5** subgroup effects were statistically significant before correction, compared with **[YOUR VALUE] after Bonferroni correction**.
- The power analysis helped me understand whether the sample was large enough to detect an effect of d = 0.3.
- The p-value simulations showed me how results can differ depending on whether the null hypothesis is true or false.

Overall, this lab helped me distinguish statistical significance from effect size, understand the importance of statistical power, and see why correcting for multiple comparisons matters when interpreting subgroup results.
