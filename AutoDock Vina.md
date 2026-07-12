protein-ligand docking software

installation using conda (package and environment manager):
1. install miniconda3
2. conda tos accept --override-channels --channel https://repo.anaconda.com/pkgs/main
3. conda tos accept --override-channels --channel https://repo.anaconda.com/pkgs/r
4. echo "[ -f /opt/miniconda3/etc/profile.d/conda.sh ] && source /opt/miniconda3/etc/profile.d/conda.sh" >> ~/.zshrc
5. conda init zsh
6. conda create -n autodockvina python=3 -y
7. conda activate autodock vina
8. conda config --env --add channels conda-forge\
9. conda install -c bioconda vina -y\
