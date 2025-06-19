# LLM-NLPOR-Work 2025


The SIPP codebook is [here](https://www.census.gov/data-tools/demo/uccb/sippdict?s_keyword=).

This [diagram](https://www2.census.gov/programs-surveys/sipp/Select_approp_wgt_2014SIPPpanel.pdf) showing which weights to use. 

## Data Description

Data come from Waves 1 through 4 of the 2014 SIPP covering calendar years 2013 through 2016. Each respondent is identified using the combination of `ssuid` and `pnum`.

Relevant variables include coverage in the following programs:

| SIPP Variable | Program   |
| ------------- | --------- |
| rfscov        | SNAP      |
| rwiccov       | WIC       |
| rtanfcov      | TANF      |
| emd_scrnr     | Medicaid  |
| emc_scrnr     | Medicare  |

Demographic variables include age, gender, race, ethncity, citizenship, employment status, state of residence, and education.
