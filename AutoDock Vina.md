protein-ligand docking software

installation using conda (package and environment manager):
1. install miniconda3
2. install vina, create and activate environment
```bash
conda tos accept --override-channels --channel https://repo.anaconda.com/pkgs/main
conda tos accept --override-channels --channel https://repo.anaconda.com/pkgs/r
echo "[ -f /opt/miniconda3/etc/profile.d/conda.sh ] && source /opt/miniconda3/etc/profile.d/conda.sh" >> ~/.zshrc
conda init zsh
conda create -n autodockvina python=3 -y
conda activate autodock vina
conda config --env --add channels conda-forge
conda install -c bioconda vina -y
```
