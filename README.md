# NRF2_brain_single-cell-analysis

This is a repo that contains the code and data necessary to recreate the figures and analysis for the Slattery lab paper submitted to *Redox Biology* titled "Limited Expression of Nrf2 in Neurons Across the Central Nervous System". 

All code and replicated figures are contained within the Jupyter Notebook in this repo.  The Python environment used for the analysis is saved in an Anaconda environment file titled 'Conda_environment.yml'.  To run the notebook, replicate this environment by installing Anaconda/Miniconda and running `conda env create --file=Conda_environment.yml`.  Then simply open the Jupyter Notebook (using the `jupyter notebook` command in a terminal) and run the notebook.

---------------------------------------------------------------------------------------------------

**Raw data sources:**

[Linnarsson mouse brain atlas adolescent mouse brain aggregated data](https://storage.googleapis.com/linnarsson-lab-loom/l5_all.agg.loom)

[Linnarsson mouse brain atlas developmental mouse brain aggregated data](https://storage.googleapis.com/linnarsson-lab-loom/dev_all.agg.loom)

[Human brain UCSC CellBrowser data](https://cells.ucsc.edu/?ds=dev-brain-regions+wholebrain)

[Human brain Alzheimer's CELLxGENE data](https://cellxgene.cziscience.com/collections/180bff9c-c8a5-4539-b13b-ddbc00d643e6)

[Human brain Multiple Sclerosis UCSC CellBrowser data](https://cells.ucsc.edu/?ds=ms)

[Human brain Autism UCSC CellBrowser data](https://autism.cells.ucsc.edu/)

[Mouse brain snATAC-seq data (CATLAS)](http://catlas.org/mousebrain/#!/)

---------------------------------------------------------------------------------------------------

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
