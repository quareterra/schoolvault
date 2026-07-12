protein-ligand docking software

installation using conda (package and environment manager):
1. install miniconda3
2. conda tos accept --override-channels --channel https://repo.anaconda.com/pkgs/main
3. conda tos accept --override-channels --channel https://repo.anaconda.com/pkgs/r

3. echo "[ -f /opt/miniconda3/etc/profile.d/conda.sh ] && source /opt/miniconda3/etc/profile.d/conda.sh" >> ~/.zshrc
4. conda init zsh
5. conda create -n autodockvina python=3 -y
6. 