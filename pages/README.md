## About

The Washington University March of Dimes Prematurity Research Study (WUMOD) was a prospective, longitudinal cohort study performed at Washington University in St. Louis Medical Center between January 2017 and January 2020, aiming to assess the role of maternal sleep as a risk factor for adverse birth outcomes. A convenience sample size of 1000 participants was chosen as a balance between an aggressive enrollment target given annual delivery volumes, the need to recruit and retain participants in multiple projects, and the varied outcomes assessed in each project. Participants were enrolled in the first or early second trimester and followed through delivery, during which four study visits (one from each trimester and one at the delivery) were conducted. The primary outcome include preterm birth, while secondary outcomes include preeclampsia and other adverse birth outcomes. 

Women were approached for enrollment if they had a singleton pregnancy ≤20 weeks’ gestation and met the following inclusion criteria: plan to deliver at Barnes-Jewish Hospital, 18 years of age or older, and English speaking. Patients were not eligible if with multiple pregnancy, non-viable pregnancy, <18 years old, fetal anomaly, gestational age >19.9 weeks, incarcerated, non-English speaking, exceeds weight limit for cPAE, prior c-section, not delivering at BJH, IVF, medical comorbidities, unable to provide consent.
 
Biological samples (i.e., maternal blood, saliva, vaginal fluid, placenta, cord blood, amniotic fluid, infant buccal swab), imaging (i.e., cervical, uterine MRI, electromyometrial imaging), actigraphy, and questionnaire data (e.g., Perceived Stress Scale, Pittsburgh Sleep Quality Index, etc.) were collected during study visits. A comprehensive case report form was used to collect data from electronic medical records on the index pregnancy, previous pregnancies, maternal demographics and medical history, labor and delivery, neonatal outcomes until discharge from hospital, and maternal postpartum visits. 

The NSRR WUMOD dataset includes wrist activity and light exposure from 1,260 participants from three visits (one from each trimester) between 2017 to 2020. 

## Methods

### Study visits

Participants were seen at study visits longitudinally throughout pregnancy and at delivery. Study visits were scheduled to obtain data and samples in each of the three trimesters. All study visits were aligned as much as possible with routine obstetric care to minimize inconvenience to the participants.

### Actigraphy collection

Participants wore wrist actigraphy devices (Motionwatch8, CamNTech, United Kingdom) for two-week time periods during their first, second, and third trimesters. The actigraphy devices captured minute-level movement and light exposure and remained charged for approximately 90 days, ensuring continuous data collection.

## Data de-identification

All personally identifiable information (PII) has been removed from the data files by the NSRR team. Calendar dates in the actigraphy epoch-by-epoch files do not represent the actual dates of collection.

## Data overview

### Actigraphy epoch-by-epoch files

[Raw epoch-by-epoch actigraphy CSV files](:files_path:/actigraphy) are available for 1,278 subjects. The filenames are structured as the subject identifier (e.g., 1001), followed by the timeframe of the collection (e.g., T1 = First trimester; GA12 = Gestational age 12 weeks; GA34 = Gestational age 34 weeks; etc.)

These files were downloaded directly from the Motionwatch device. Data users should be mindful of the potential for non-wear (invalid) data within the actigraphy files. Sleep diary data are not available. 

The epoch-by-epoch files contain a file header and a raw data section that includes these columns:

1. Date (reset to the same day of week closest to 1/1/2000 as part of de-identification)
2. Time (clock time, with AM/PM)
3. Activity (Motionwatch counts)
4. Light (lux)

The month (i.e., 1 = January, 2 = February, etc.) in which the actigraphy recording started is available in the supplemental actigraphy_month_start.csv file.

## Access and usage restrictions

The WUMOD dataset is only available for non-commercial use.

## Citation and acknowledgement

When using this dataset, users must cite the following:

> [Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)
> 
> [Stout MJ, Chubiz J, Raghuraman N, Zhao P, Tuuli MG, Wang LV, Cahill AG, Cuculich PS, Wang Y, Jungheim ES, Herzog ED, Fay J, Schwartz AL, Macones GA, England SK. A multidisciplinary Prematurity Research Cohort Study. PLoS One. 2022 Aug 25;17(8):e0272155. doi: 10.1371/journal.pone.0272155. PMID: 36006907; PMCID: PMC9409532.](https://pmc.ncbi.nlm.nih.gov/articles/PMC9409532/)

Users must include the following text in any Acknowledgements:

> The WUMOD Prematurity Research Study was supported by the March of Dimes. The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002).

## Changelog

*December 2024*

- Make WUMOD dataset available for data requests

## References

- WUMOD on the National Sleep Research Resource (NSRR): https://sleepdata.org/datasets/wumod/
- WUMOD GitHub Documentation: https://github.com/nsrr/wumod-documentation

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
