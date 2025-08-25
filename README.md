# Dementia-prediction-using-OASIS-dataset

## Abstract
Dementia is a progressive neurological disorder that impairs memory, thinking,
 and behavior, posing a growing burden on aging populations worldwide. There
 is no cure; we can only slow down the progression of the disease. This study exam
ines gender-based differences in feature importance for predicting dementia using
 two datasets: the OASIS-1 and a publicly available Kaggle dementia prediction
 dataset. Each dataset was split on the basis of gender and was analysed separately
 using the Random Forest, LightGBM, and Logistic Regression models. The result
 indicated only a slight difference in feature importance between male and female
 sets. Notably, socioeconomic status was seen as a more significant predictor for
 males than females in the OASIS dataset, while the Kaggle dataset showed mini
mal gender related differences. These findings suggest that the minimal differences
 in feature importance across genders may be attributed to the limited and shared
 set of features used in the datasets, which did not include gender-specific factors
 such as hormonal or biological variables

## Result
 From the SHAP analysis of the Random Forest model, MMSE emerged as the most influential predictor for both male and female sub
sets in the OASIS dataset. This finding aligns with prior studies establishing MMSE as a
 reliable cognitive screening tool, strongly correlated with dementia severity and progression.
 The second most important feature differed by gender, ASF for males and nWBV
 for females. Gender-specific neuroanatomical differences may explain this divergence.
 ASF, an automated proxy for head-size normalization, correlates strongly with manually
 measured total intracranial volume and effectively accounts for head size—typically larger
 in males making it especially relevant in analyses sensitive to male anatomical variance. By contrast, nWBV, as a normalized measure of whole-brain volume relative to
 intracranial volume, is a well-established MRI biomarker for dementia and may be more
 sensitive to pathological changes in females.
 Education also appeared more prominent for females, a finding consistent with the
 cognitive reserve hypothesis where lower educational attainment increases dementia sus
ceptibility. Longitudinal meta-analyses show that higher educational levels are associated
 with a significantly reduced risk of dementia across life stages. Additionally, work
 suggesting more pronounced effects of educational protection in women than men further
 supports our finding.
 Interestingly, SES exhibited opposite associations across genders: higher SES was
 linked to increased dementia risk in males, whereas lower SES was associated with higher
risk in females. This aligns with recent evidence showing sex differences in how socioe
conomic factors and brain structure interrelate in dementia risk. Socio-behavioral
 dynamics—such as differential occupational exposure, healthcare access, and prolonged
 stressors—likely underpin these gender-based variations.
