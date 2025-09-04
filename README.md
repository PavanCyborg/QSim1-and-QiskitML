# QSim1-and-QiskitML

## Installation Procedure:

**Step-1:** Create new repository and activate it.

```bash
conda create -n QSim1 python==3.8
conda activate QSim1
```

**Step-2:** Clone the repository.

```bash
git clone https://gitlab.com/zubair257/qiskit-aer-cdachyd.git -b qasm_vector
```

**Step-3:** Installation
```bash
pip install scikit-build jupyter lab
export PATH=/home/cdac/anaconda3/envs/Qsim1/bin:$PATH
sudo apt-get update
sudo apt-get install libblas-dev liblapack-dev
git checkout remotes/origin/dmsim_multicpu
conda install -c conda-forge libstdcxx-ng -y
python setup.py sdist
pip install dist/qiskit_aer-0.14.1.tar.gz 
```


## Installation of Qiskit Machine Learning :

To install qiskit machine learning run the following command in the terminal 

```bash
pip install qiskit-machine-learning==0.7.1
``` 
