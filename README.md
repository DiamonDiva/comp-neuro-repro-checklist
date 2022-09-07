# My first line in my comp-neuro-repro-checklist markdown file


# Group 1
- [ ]  write down the explicit aim/hypothesis
- [ ]  experimental parameters
- [ ]  dataset — where did the data come from.  needs to be well organized (filename/hierarchy)
    - [ ]  description
    - [ ]  metadata
        - [ ]  data origin location (where is it from)
        - [ ]  sample size
        - [ ]  date of data collection
        - [ ]  data standard/units
        - [ ]  dictionary of variables/symbols
        - [ ]  format of data stored
- [ ]  data storage location (clearly named)
- [ ]  etc. files (figures/photos/histology) storage location (clearly named)
- [ ]  documentation
    - [ ]  data pipeline protocol documentation
    - [ ]  experimental protocol documentation
        - [ ]  documentation of failures as well
    - [ ]  documentation of code used
        - [ ]  pre-processing
        - [ ]  data analysis
        - [ ]  figure creation
        - [ ]  data conversion
    - [ ]  complete documentation of the primary record (e.g. lab notebook)
- [ ]  Responsibility (hierarchy) of people in the experiment: who was responsible for what parts of the experiment/code/data collection/etc.

# Group 2


# Group 3
Based on "Reproducibility Criteria", EMNLP 2020: https://2020.emnlp.org/call-for-papers#new-reproducibility-criteria

For all reported experimental results:

- [ ] A clear description of the mathematical setting, algorithm, and/or model.
- [ ] A link to a downloadable source code, with specification of all dependencies, including external libraries
- [ ] Description of computing infrastructure used
- [ ] Average runtime for each approach
- [ ] Number of parameters in each model
- [ ] Corresponding validation performance for each reported test result
- [ ] Explanation of evaluation metrics used, with links to code
- [ ] * Code reviews
- [ ] * Pre-registration encouraged

For all experiments with hyperparameter search:

- [ ] Bounds for each hyperparameter
- [ ] Hyperparameter configurations for best-performing models
- [ ] Number of hyperparameter search trials
- [ ] The method of choosing hyperparameter values (e.g., uniform sampling, manual tuning, etc.) and the criterion used to select among them (e.g., accuracy)
- [ ] Expected validation performance, as introduced in Section 3.1 in Dodge et al, 2019, or another measure of the mean and variance as a function of the number of hyperparameter trials.

For all datasets used:

- [ ] Relevant statistics such as number of examples
- [ ] Details of train/validation/test splits
- [ ] Explanation of any data that were excluded, and all pre-processing steps
- [ ] A link to a downloadable version of the data * (if not possible, provide a reason)
- [ ] For new data collected, a complete description of the data collection process, such as instructions to annotators and methods for quality control.

*new additions

