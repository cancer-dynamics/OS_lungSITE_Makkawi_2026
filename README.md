# OS lungSITE: ERK signaling and MCL1-inhibitor response in osteosarcoma
**Authors:** Rawan Makkawi, Jeremy Copperman, Alexander Davies

This repository has the analysis code for Makkawi et al. (2026), a study of how osteosarcoma (OS17) cells in lung tissue respond to MCL1 inhibitor treatment. The analysis uses imaging data obtained from Lung-SITE (Serial Imaging of the Tumor and microEnvironment) to quantify spatiotemporal single-cell ERK activity, Fra-1 reporter expression, contacts within the microenvironment, and cell death in response to treatment. It shows how ERK signaling, contact niche states and neighborhood deaths (Nd) relate to cell fate, and builds a Markov model of cell state and death that is used to simulate ERK inhibition in silico.

**Usage**

This notebook is the downstream step of the SITE pipeline. Run the SITE Image_Processing_and_Feature_Extraction and SITE Analysis_pipeline notebooks first to produce the ROI .h5 files from a .nd2 file, or download the processed .h5 files from Kaggle: [].

**References**

* Spatially coordinated RTK-ERK signaling dynamics shape osteosarcoma single-cell drug response in the lung microenvironment. Rawan Makkawi, Carol Halsey, Vaibhav Murthy, Elise C. Manalo, Hugo Cros, Xin Yi, Jessie May Cartier, Matthew Chang, Mark Flory, Kelly Guptell, Amy Gross, Ryan D. Roberts, Jeremy Copperman, Alexander E. Davies. bioRxiv 2026.09.30.755770; doi: https://doi.org/10.64898/2026.09.30.755770
* Serial Imaging of Tumor and microEnvironment (SITE) platform for live-cell ex vivo modeling of primary and metastatic cancer dynamics. Vaibhav Murthy, Rawan Makkawi, Francis Anderson, Carol Halsey, Elise Manalo-Hall, Sanjay Srikanth, Gabriella Tangkilisan, Ting Zheng, James McGann, Marc R. Birtwistle, Jeremy Copperman, Alexander E. Davies. bioRxiv 2025.09.08.674915; doi: https://doi.org/10.1101/2025.09.08.674915
* SITE Pipeline was built upon and using the celltraj toolset
