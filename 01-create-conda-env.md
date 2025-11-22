# Create Conda Environment with Miniconda
I am creating a conda environment for DESeq2 data analysis with R anD Bioconductor in my windows system using windows substem Linux (WSL)

## Code in WSL terminal
-Start the WSL in Windows
-Type the following to create a conda environment for R4.5 name as R4.5WS

```(cmd)
conda create --name R4.5WS
```
Activate the R4.5WS conda environment as follows
```(cmd)
conda activate R4.5WS
```
-install R4.5 IN THE r4.5WS conda environment
```{CMD}
conda install conda-forge::r-base
```
`conda-forge` is the channel from anaconda.org. [conda-forge/r-base](https://anaconda.org/conda-forge/r-base) 

