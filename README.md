## Janssen-project: Deep learning enhanced multi-modal phenomics and spatial transcriptomics for predicting response to oncolytic virotherapy in PDAC

### Dataset: 
- Public data ovarian cancer from Vizgen https://vizgen.com/data-release-program/
  - cell by gene: number of gene expressed in each cell
  - metadata: coordinates of cell in physical space of ovarian cancer tissue
  - detected transcripts
  - images of ovarian cancer tissue
### Script:
- UMAP_histogramme: histograms cell by genes and its visualizations with umap
- Auto_encodeur_mARN:
  - Implementing autoencoder model and then generating encoded data in latent space

    <img src="https://github.com/VeraPancaldiLab/Janssen/assets/48489836/cd454237-bc5c-4aa2-a93d-7300ae112742" width="500" height="400">
    
  - Tysserand: create network of cells from encoded data
    
    <img src="https://github.com/VeraPancaldiLab/Janssen/assets/48489836/04420c95-ab51-4073-a454-bdb1bfe81e0a" width="500" height="400">
    
  - Mosna: calculate the assortativity and z-score
  - Squidpy: assign cell types
    
    <img src="https://github.com/VeraPancaldiLab/Janssen/assets/48489836/2d8b5283-c40a-470b-96c2-b86b07ae2e98" width="500" height="400"> <img src="https://github.com/VeraPancaldiLab/Janssen/assets/48489836/0d2a0e9e-664a-49f2-8bb3-ec89dc7f18cc" width="500" height="400">

