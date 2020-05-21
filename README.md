# awesome-neural-data-tools
Tools, algorithms, and frameworks for managing and analyzing neural data (derived from original notes from the 2018 BRAIN Initiative Investigators Meeting by Liam Paninski)

## Calcium+voltage imaging:
* https://github.com/flatironinstitute/CaImAn 
* https://github.com/zhoupc/CNMF_E
* https://github.com/cortex-lab/Suite2P
* https://github.com/jewellsean/FastLZeroSpikeInference 
* https://github.com/losonczylab/sima 
* https://www.biorxiv.org/content/early/2018/05/30/334706 (compression + denoising)
* https://github.com/bahanonu/calciumImagingAnalysis - Biafra Ahanonu (MIT) 

## Spike sorting:
* https://github.com/cortex-lab/KiloSort 
* https://github.com/mouseland/kilosort2
* http://www.jrclust.org/ 
* https://github.com/flatironinstitute/ironclust
* https://github.com/paninski-lab/yass 
* https://github.com/flatironinstitute/mountainsort 
* https://github.com/pillowlab/BinaryPursuitSpikeSorting 
* https://spyking-circus.readthedocs.io/en/latest/
* http://homepages.inf.ed.ac.uk/mhennig/herdingspikes/
* https://github.com/tridesclous/tridesclous
* http://neuralensemble.org/neo/ - Intracellular recording

## Optogenetic stimulation
* https://github.com/wjyangGithub/Holographic-Photostimulation-System  (matlab tools for SLM targeting and hologram generation)

## Behavioral + stimulus control (and analysis)
* https://bonsai-rx.org/
* http://www.openmaze.org/  
* https://pni.princeton.edu/pni-software-tools/virmen 
* https://github.com/dendritic/signals

## Fluorescence Imaging
* http://ilastik.org/index.html

## Compression 
* http://blosc.org/
* https://bellard.org/bpg/
* https://github.com/int-brain-lab/mtscomp

## Registration & stitching
* https://github.com/neurodata/ndreg - current reference registration for cleared brain data
* http://stnava.github.io/ANTs/ - reference for much human MRI
* https://github.com/khaledkhairy/EM_aligner
* https://abria.github.io/TeraStitcher/ - current reference implementation for linear stitching

## Electron microscopy
* https://github.com/google/neuroglancer WebGL-based viewer for volumetric data
* https://github.com/seung-lab/cloud-volume (for working with "precomputed" format of Neuroglancer)
* https://github.com/seung-lab/Alembic (aligning images of serial sections)
* https://github.com/saalfeldlab/render - current reference implementation for dynamic rendering of aligned data

## scRNAseq / FISH
* https://github.com/spacetx/starfish

## Eye tracking
* https://github.com/AllenInstitute/allensdk.eye_tracking
* https://github.com/kristinbranson/APT  
* https://github.com/mkrumin/EyeTracking 
* https://github.com/carsen-stringer/FaceMap 

## Animal part tracking
* https://github.com/kristinbranson/APT
* http://ilastik.org/ 
* https://github.com/AlexEMG/DeepLabCut 
* https://github.com/carsen-stringer/FaceMap 
* https://www.biorxiv.org/content/early/2018/05/30/331181

## Statistical Machine Learning
Spike train data analysis methods - encoding models, decoders, dimensionality reduction, etc
* http://xarray.pydata.org/en/stable/ 
* RF estimation (ASD prior): https://github.com/pillowlab/fastASD
* GLM fitting for trial-based data:  https://github.com/pillowlab/neuroGLM
* Entropy Estimation: https://github.com/pillowlab/CDMentropy/
* Hypothesis testing: https://github.com/neurodata/mgc
* Linear dimensionality reduction: https://github.com/neurodata/LOL
* Classification and regression: https://github.com/neurodata/R-RerF

## Visualization (2D, 3D, 4D, 5D)
### Web-Viz
* http://catmaid.readthedocs.io/en/stable/
* https://github.com/google/neuroglancer
* http://www.geppetto.org/ 
### Local-Viz
* https://imagej.net/BigDataViewer
* http://www.alleninstitute.org/what-we-do/brain-science/research/products-tools/vaa3d/

## Pipelines, data sharing, reproducibility
Tracking provenance of data / analysis outputs.  Automatic repopulation of databases as analysis algorithms are updated. Store both data and model simulation output
* https://datajoint.github.io/ 

## Data specifications
* https://neurodatawithoutborders.github.io/
* http://bids.neuroimaging.io/

## Reproducibility + knowledge sharing tools
* https://mybinder.org/
* http://gigantum.io/ 
* https://colab.research.google.com/notebooks/welcome.ipynb
* https://www.kaggle.com/kernels

## Data/Tool Repositories:
* https://crcns.org/
* https://neurodata.io/
* https://www.nitrc.org/
* http://datalad.org/ 
* https://portal.brain-map.org/

## Review articles
* Neural data science: accelerating the experiment-analysis-theory cycle in large-scale neuroscience; Liam Paninski, John Cunningham https://www.biorxiv.org/content/early/2017/10/02/196949 

