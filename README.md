# Hey, I'm Prithviraj 👋

I'm a cancer biologist who got curious about what the data could tell me that the bench couldn't.

I trained in microbiology, then did my MSc in Cancer Biology & Therapeutics at Cardiff University. There I explored synthetic lethality between BRCA2 loss and PARP inhibition, and wrote my dissertation on zinc transporters (ZnT/SLC30A) in cancer. Both left me with the same itch: a lot of the answers were already sitting in public datasets like DepMap and TCGA, and I wanted to be able to go and find them myself.

This GitHub is where I'm doing that. Every project here starts with a real biological question, uses open data, and is written so anyone can rerun it.

### 🔬 Projects

- **[BRCA2 & PARP inhibitors](https://github.com/prithviraj-dasgupta/brca2-parp-depmap):** do BRCA2-deficient cancer cells really respond better to PARP inhibitors? The answer was more complicated than the textbook story. *(DepMap · Python)*
- **[Zinc transporters in cancer](https://github.com/prithviraj-dasgupta/znt-slc30a-tcga):** turning my MSc literature review into data. Which SLC30A genes change in tumours, and do they track with patient survival? *(TCGA · Python · survival analysis)*
- **[Where did this tumour come from?](https://github.com/prithviraj-dasgupta/tcga-tissue-of-origin):** a model that names a tumour's tissue of origin from its gene expression, right 96% of the time across 33 cancer types. The part I liked most was using SHAP to look inside it. It had rediscovered the markers pathologists stain for, and it also caught the model using a shortcut it didn't need. *(TCGA · scikit-learn · LightGBM · SHAP)*
- **[Melanoma, one cell at a time](https://github.com/prithviraj-dasgupta/melanoma-scrnaseq):** my first single-cell project. I took about 4,600 cells from 19 melanomas (Tirosh et al. 2016), grouped and labelled them by cell type, and worked out which ones were cancer cells from copy-number changes alone, agreeing with the authors' labels 91.5% of the time. Then I asked whether melanoma cells split into an MITF-high state and the AXL-high state linked to drug resistance. They do, but mostly between patients rather than within one tumour. *(scRNA-seq · Scanpy · infercnvpy · tested pipeline with CI)*

### 🧰 Tools I use

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Scanpy](https://img.shields.io/badge/Scanpy-1F4E79)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

### 🎧 Outside the lab

I produce music and DJ as **mimo_gol**. It turns out finding patterns in sound and finding patterns in gene expression aren't so different.

### 📫 Say hi

[LinkedIn](https://www.linkedin.com/in/prithviraj-dasgupta-2a6127168) · always happy to talk cancer biology, data, or music.