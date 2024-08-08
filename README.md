# Analysis of Medicare Part D: Insights on Prescription Drug Coverage (2018 - 2022)

## Description
This project focuses on analyzing data related to Medicare Part D, the prescription drug coverage plan in the United States. Using SQL and Python, 
the analysis aims to uncover trends, patterns, and key insights into the usage and costs associated with Medicare Part D. 
The study highlights the highest prescribed drugs, payment structures, and specialties involved. 
The findings provide valuable information on how prescription drug coverage impacts various demographics, identifies areas for cost optimization, and suggests potential improvements in policy and administration.

## Methodology
The analysis involves:
- Data extraction and cleaning using SQL.
- Data analysis and visualization using Python.
- Identification of the highest prescribed drugs.
- Analysis of payment structures.
- Examination of specialties involved in prescription drug coverage.

## Key Insights
- **Healthcare Industry Payments:** Experienced a significant decline in 2020 following a peak in 2019 but rebounded to near-peak levels by 2022.
- **Gender Gap:** Persistent gender gap in payment distribution within the healthcare sector, with male providers consistently receiving a predominant share.
- **Prescription vs. Payments:** Weak and slightly inverse relationship between average payments to healthcare providers and the average number of prescriptions they write.
- **Medical Specialties:** Internal Medicine and Family Practice lead substantially in total claims over other specialties, with Endocrinology, Neurology, and Cardiology receiving relatively high payments.
- **Costly Drugs:** Levothyroxine Sodium, despite not being the most frequently prescribed drug, incurs a high average cost per prescription.
- **Prescription Volumes:** Providers without payment filled more prescriptions on average, especially those who graduated in 2010 and later.
- **Clinical Training:** Variations in prescription volumes highlight differences in clinical training at U.S. medical schools.

## Files
- `medicare_project_analysis.py`: Python script containing the analysis performed using SQL and Python.
- `Final Project Presentation.pptx`: PowerPoint presentation with visualizations of the analysis.

## Data Sources
- [Medicare Part D Prescribers by Provider and Drug](https://data.cms.gov/provider-summary-by-type-of-service/medicare-part-d-prescribers/medicare-part-d-prescribers-by-provider-and-drug)
- [Medicare Physician and Other Practitioners by Provider and Service](https://data.cms.gov/provider-summary-by-type-of-service/medicare-physician-other-practitioners/medicare-physician-other-practitioners-by-provider-and-service)
- [Open Payments Data](https://openpaymentsdata.cms.gov/datasets?theme%5B0%5D=General+Payments)

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Ivie-Irivbogbe/medicare-part-d-analysis.git
