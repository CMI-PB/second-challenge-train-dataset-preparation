The CMI-PB team conducted data harmonization and processing to provide datasets in the form of computable matrices. The pipeline involves assessing data noise, feature filtering, and batch effects between 2020 and 2021 CMI-PB datasets.

**Key Steps:**
- **Download Raw data files.**
The training dataset for the second challenge comprises two multi-omics datasets (designated as 2020 and 2021) that require processing and normalization to generate computable matrices suitable for subsequent model development. While the procedures for data processing and normalization are inherently user-specific, the CMI-PB team has devised a data processing method, drawing inspiration from the approach used in the internal 1st CMI-PB challenge. The codebase is also available on GitHub. If you have specific questions, please contact us via the Solutions Center.

- **Read downloaded files into R environment** and perform feature filtering and save harmonized data files (Code: ./scripts/step1_read_data.Rmd)

- **Assess and remove batch effects** and then save processed data files (Code: ./scripts/step2_batch_effect_correction.Rmd).
- **Access processed data files.** These datafiles are available as R objects [here](https://www.cmi-pb.org/downloads/cmipb_challenge_datasets/current/2nd_challenge/processed_datasets/).
