<h2>pRD-data repository</h2>

This directory contains all input, preprocessed BCRseq (AIRR) datasets for the article titled *"Partial RAG deficiency in humans induces dysregulated peripheral lymphocyte development and humoral tolerance defect with accumulation of T-bet+ B cells"*.

All filenames are consistent with the data referenced in the above article. All files contain properly aligned and annotated sequences for each subject.

**Important**: Strict file naming and placing conventions are used. If you want to process this data with <a href="https://github.com/blazsop/airrmine">AIRRMINE</a> system, DO NOT CHANGE the names of the files and read its documantation carefully (see the example data) on where to copy these files before running data analysis.

<h3>Dataset files:</h3>

* **iRepertoire_preprocessed.zip** : raw output of iRepertoire, Inc. BCR sequencing service (CSV formatted) - from ALL subjects - IgH, IgL and IgK 
* **prepared_AIRR_HC.zip** : IMGT V-Quest re-annotated iRepertoire datasets (standard AIRR TSV formatted) - only healthy controls - IgH, IgL and IgK 
* **prepared_AIRR_pRD.zip** : IMGT V-Quest re-annotated iRepertoire datasets (standard AIRR TSV formatted) - only partially RAG Deficient patients - IgH, IgL and IgK 
* **prepared_AIRR_single_clone_IgH_sequences.zip** :  IMGT V-Quest re-annotated iRepertoire datasets (standard AIRR TSV formatted) - from ALL subjects - only IgH

*Note: <a href="http://www.imgt.org/IMGT_vquest">IMGT V-Quest</a> v3.4.17 (ref db: 201915-3) was used to annotate all IgH and v3.5.21 (ref db: 202049-2) was used in case of all IgK/IgL sequences.*
