# Test in linux CentOS 7 
# esm_conda_yaml
The conda env to install esmfold
```bash
conda env create -f esm_myself_conda.yml
```
# Then run cmd
```bash
conda activate esmfold
pip install "fair-esm[esmfold]"
# OpenFold and its remaining dependency
pip install 'dllogger @ git+https://github.com/NVIDIA/dllogger.git'
pip install 'openfold @ git+https://github.com/aqlaboratory/openfold.git@4b41059694619831a7db195b7e0988fc4ff3a307'
```
# command-line useage
cp the fold.py from https://github.com/facebookresearch/esm/blob/main/scripts/fold.py
```bash
python fold.py -h
```
