# Deep Learning
### Installation process for Apple M1 MAC 
- brew install miniforge
- conda install -y jupyter
- Run the command in a folder: conda env create -f tensorflow-apple-metal.yml -n tensorflow
- conda activate tensorflow
- conda install nb_conda
- python -m ipykernel install --user --name tensorflow --display-name "Python 3.9 (tensorflow)"
- check the test jupyter notebook to check installation.