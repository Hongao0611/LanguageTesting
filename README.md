# Data Analysis: Item analysis + Test analysis

We calculate the following metrics for every item:
- Item difficulty (IF)
- B-index (threshold = 50%)
- Item discrimination (ID, three tiers)

and these between questionnaires (or between phenomena):
- Correlation (Pearson)
- Distribution of scores
- Pairwise scatter plots
- ANOVA

### Item analysis
We calculate the following metrics for every questionnaire:
- Item difficulty
    - $IF = \frac{N_{\text{correct}}}{N_{\text{total}}}$
    - $B-index=IF_{\text{pass}}-IF_{\text{fail}}$
- Item discrimination
    - $ID = IF_{\text{upper}}-IF_{\text{lower}}$
- Distractor efficiency
    - (no enough data)

### Test analysis
We calculate the reliability metrics for the whole test:
- Parallel/Alternate Forms reliability (Pearson correlation between the observed test scores.)

*We did not choose IRT due to the limit in sample size
