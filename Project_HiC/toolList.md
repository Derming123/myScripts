# preprocessing tool
- **`HiC-Pro`** and downstream analysis tools, see http://nservant.github.io/HiC-Pro/COMPATIBILITY.html
- **`Juicebox`** : dynamic visualization of HiC contact maps, `http://aidenlab.org/juicebox/`
- **`HiCPlotter`** : Hi-C data visualization, `https://github.com/kcakdemir/HiCPlotter`
- **`TAD calling`** : generated the input file using the sparseTodense.py utility.
- **`Fit-Hi-C`** : detect significant interaction on intra-chromosoml contact map, 
use the hicpro2fithic.py utility to connvert HiC-Pro output to Fit-Hi-C input files.
- **`HiTC`** R package 
function to import HiC-Pro output into the R environment. 
Contact matrices are then stored as sparse Matrix, which can be used for any downstream analysis.