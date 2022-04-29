## Fonville et al. 2014, Science

* `Fonville_2014_supplement.xls` contains the raw supplementary data. 

* `Fonville_human_data.csv` is a copy of table S3, which contains the human data from the Ha Nam study.

* `YOB_inferred.csv` are covariate data compiled manually by Kangchon Kim from supplementary figures. These can be merged with the main data file to aid analyses. Columns include:

      * `Subject number` corresponds to the same column in Table S3, and `Fonville_human_data.csv`.
      * YOB - is year of birth, which was filled in by hand after cross-referencing titers and other metadata with Fig. S15.
      * ID - The meaning of this column is unknown.
      * Sample - From Fonville 2014, why was the sample chosen for serological analysis? Original: member of the original household cohort. H3: PCR-confrimed infection with H3N2, Seroconverter: seroconverted to H3N2, Original: Control without PCR-confifrmed infection or seroconversion to H3N2. These are included as flags that can help identify individual in Fig. S15. See section 1.1.2, and Fig. S15 in the supplementary methods for greater detail. 
      * PCR+ - PCR+ if the subject had a PCR-confirmed H3N2 infection.
      * Seroconversion - TRUE if the subject meets the Fonville et al. definition of seroconversion (4-fold or greater rise in titer to the dominant circulating H3N2 cluster). Note that seroconversion can occur in individuals not labeled "seroconverter" in the Sample column, e.g. individuals with PCR-confirmed infection, or tose part of the original household cohort can also seroconvert.
      * Infection year - For individuals who seroconverted or had a PCR-confirmed H3N2 infection.
      * days_PCR_swab_to_serum_sample - Time elapsed between PCR-confirmed infection (time of swab), and annual serological sample, filled in by hand from Fig. S15. 

* `Fonville2014_FigS43.csv`


**Guide to tabs in .xlsx supplementary data file**
(Gleaned from the supplementary text)

* Table S1 - "Sera from 35 influenza-na ̈ıve ferrets each infected with a single influenza A/H3N2 virus (viruses isolated between1989 and 2010) were collected 13-20 (typically 14) days post-infection. These sera were tested with the hemaggluti-nation inhibition (HI) assay against 74 A/H3N2 influenza viruses isolated globally between 1992 and 2011; the fulltitration table is given in Table S1 (see additional excel files)."
* Table S3 - Titers from participants in the HaNam Cohort study

    * 36 participants are from 6 highly compliant households in the study, and their sera are titrated against 38 viruses (isolated between 1993-2011).
    * 40 participants were selected at random and their sera were titrated against a more extensive set of 40 viruses (viruses isolated between 1968 and 2011).

* Table S5 - Titers from sera of 106 volunteers pre- and post-vaccination with A/Nanchang/933/95 (vaccination study performed in 1997). 
* Table S6 - Titers from sera of 128 volunteers pre- and post-vaccination with A/Sydney/5/97 (vaccination study performed in 1998).
* Table S9 - Strain coordinates for antigenic map underlying antibody landscapes (estimated from ferret sera).
* Table S13- 2009 vaccine serology panel (human -- I'm unclear if this is from the HaNam cohort).
* Table S14 - 2010 vaccine serology panel (human -- I'm unclear if this is from the HaNam cohort).

