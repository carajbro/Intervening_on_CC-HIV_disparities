# **Impact of cervical cancer and HIV interventions on cervical cancer burden among women living with HIV**

This repository includes model outputs for the DRIVE model (cervical cancer incident case counts, crude cervical cancer incidence rates, HIV prevalence) between 2001 and 2071, with projections beginning in 2021.

We modeled four additive scenarios:

**"Baseline":** (file suffix = "baseline")
- status quo scenario
- 60% of women and 44% of men aged 10-79 living with HIV are on ART with viral suppression; no ART scale-up from 2017
- HPV vaccination, cervical cancer screening and treatment, and the proportion of individuals with viral suppression remained at current levels (57% coverage of 9v HPV vaccination among girls aged 9-14; 48% cervical cancer screening coverage using cytology once per lifetime; three visit cervical cancer treatment algorithm: 72% return for colposcopy; 51% of those indicated for precancer treatment return for LLETZ and 40% of those with cancer return for hysterectomy. Effective treatment was lower for women living with HIV.

**"ART scale-up only":** (file suffix = "ARTonly")
- ART scaled-up to the UNAIDS 90-90-90 targets (72.9% of persons living with HIV virally suppressed) by 2030.

**"Enhanced cervical cancer interventions":** (file suffix = "enhancedAll")
- ART scaled-up to the UNAIDS 90-90-90 targets by 2030.
- Enhanced HPV vaccination and cervical cancer screening interventions provided regardless of HIV status (90% coverage of 9v HPV vaccination among girls aged 9-14; HPV DNA testing twice per lifetime, scaled up from 48% to 70% coverage by 2030, and to 90% coverage by 2045; Single-visit cervical cancer treatment algorithm: 95% of eligible women receive thermal ablation, 80% of those ineligible for ablation receive LLETZ, and 40% of women with cancer receive hysterectomy)

**"Enhanced cervical cancer interventions for women living with HIV":** (file suffix = "enhancedAllHIV")
- ART scaled-up to the UNAIDS 90-90-90 targets by 2030.
- Enhanced HPV vaccination and cervical cancer screening interventions.
- Additional HPV vaccination and cervical cancer screening interventions for women living with HIV (50% coverage of 9v HPV catch-up vaccination among young women living with HIV aged 15-24; HPV DNA testing every five years among women living with HIV)

The model outcome files include cervical cancer incident case counts among women aged 15+ ("crudeAnnualCC_[Scenario].xlsx"), crude cervical cancer incidence rates per 100,000 women aged 15+ ("crudeICC_[Scenario].xlsx"), and HIV prevalence among women aged 15+("crudeHivFaged15plus_[Scenario].xlsx"). The cervical cancer outcome files includes separate tabs for outcomes among all women aged 15+ ("General"), as well as outcomes stratified by HIV status: women without HIV ("HIV-"), women living with HIV without ART ("HIV+untreated"), women living with HIV with viral suppression ("HIV+ART"), and all women living with HIV ("HIV+all"). In each file tab, the 28 columns are organized as follows: median, min, max, 25 columns with the 25 best-fitting parameter sets. 
